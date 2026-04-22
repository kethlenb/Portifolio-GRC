# Threat Modeling STRIDE – TechCorp

Baseado na **Business Risk Policy (2026)** da TechCorp e na metodologia STRIDE (Microsoft), este documento apresenta a modelagem de ameaças dos principais componentes do ambiente.

---

## 📌 O que é STRIDE

STRIDE é um modelo de categorização de ameaças utilizado para identificar riscos de segurança em sistemas, baseado em seis categorias:

| Letra | Ameaça | Descrição | Impacto principal |
|------|------|-----------|------------------|
| S | Spoofing | Falsificação de identidade | Quebra de autenticação |
| T | Tampering | Alteração indevida de dados | Integridade |
| R | Repudiation | Negação de ações realizadas | Não-repúdio |
| I | Information Disclosure | Exposição de informação | Confidencialidade |
| D | Denial of Service | Indisponibilidade de serviço | Disponibilidade |
| E | Elevation of Privilege | Escalada de privilégios | Autorização |

---

## 🎯 Escopo da Modelagem

A modelagem considera os seguintes domínios descritos na política:

- Portal de chamados (ITSM)
- Plataforma Omnichannel
- Atendimento telefônico
- RMM / EDR
- Entra ID (IAM)
- Ambientes Cloud
- Endpoints e servidores
- E-mail corporativo
- Shadow IT
- Logs e auditoria

---

## 🧠 Modelagem de Ameaças

### Portal de Chamados (ITSM)

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Falsificação de usuário | Ausência de MFA | Abertura fraudulenta de chamados | MFA, SSO |
| T | Alteração de tickets | Falta de validação server-side | Manipulação de fluxo | Auditoria + RBAC |
| R | Negação de ação | Logs insuficientes | Falta de rastreabilidade | SIEM + trilhas |
| I | Vazamento de dados | Controle de acesso fraco | Exposição de dados sensíveis | Criptografia + RBAC |
| D | Indisponibilidade | Sem proteção contra abuso | Paralisação operacional | WAF + rate limit |
| E | Escalada de privilégio | Perfis excessivos | Acesso administrativo indevido | Least privilege |

---

### Plataforma Omnichannel

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Impersonação via chat | Falta de validação forte | Engenharia social | Validação cruzada |
| T | Manipulação de mensagens | Sem integridade | Fraude operacional | Logs + retenção |
| R | Negação | Sem registro formal | Falta de evidência | Integração com ITSM |
| I | Vazamento | Exposição de chats | Dados sensíveis expostos | DLP |
| D | Sobrecarga | Sem controle de abuso | Queda do atendimento | Rate limiting |
| E | Acesso indevido | Permissões amplas | Execução indevida | PAM |

---

### Atendimento Telefônico

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Engenharia social | Confiança em voz | Reset de credenciais | Validação por outro canal |
| R | Negação | Sem gravação | Falta de prova | Gravação + protocolo |
| I | Vazamento | Exposição verbal | Divulgação indevida | Scripts + treinamento |

---

### Entra ID / Identidade

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Phishing | MFA fraco | Comprometimento de contas | MFA forte |
| T | Alteração de políticas | Falta de controle | Ambiente inseguro | PIM |
| R | Negação | Logs insuficientes | Falta de auditoria | SIEM |
| I | Exposição de diretório | Permissões abertas | Enumeração de usuários | RBAC |
| D | Bloqueio de acesso | Dependência do IdP | Parada geral | Contas break-glass |
| E | Escalada de privilégio | Roles mal geridas | Domínio do tenant | Revisão de privilégios |

---

### RMM / EDR

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Uso indevido | Credenciais expostas | Controle remoto indevido | MFA |
| T | Alteração de scripts | Sem controle | Execução maliciosa | Assinatura |
| R | Negação | Falta de logs | Sem rastreabilidade | Auditoria |
| I | Vazamento | Console centralizada | Exposição de dados | Criptografia |
| D | Indisponibilidade | Dependência | Falha operacional | Redundância |
| E | Controle total | Privilégios altos | Comprometimento massivo | PAM |

---

### Cloud

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Credenciais expostas | IAM fraco | Acesso indevido | MFA |
| T | Mudanças não autorizadas | Falta de governança | Comprometimento | IaC |
| R | Falta de logs | Logging insuficiente | Sem investigação | CloudTrail |
| I | Buckets públicos | Má configuração | Vazamento | CSPM |
| D | Falha de arquitetura | Sem resiliência | Indisponibilidade | Auto scaling |
| E | Escalada IAM | Policies abertas | Domínio do ambiente | Least privilege |

---

### Endpoints

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Uso indevido | Sessões abertas | Acesso não autorizado | MFA |
| T | Malware | Admin local | Comprometimento | Hardening |
| R | Falta de logs | Baixa visibilidade | Sem auditoria | EDR |
| I | Dados locais | Sem criptografia | Vazamento | BitLocker |
| D | Ransomware | Falta de patch | Parada | Backup |
| E | Escalada local | Vulnerabilidades | Controle total | Patching |

---

### Shadow IT

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Contas paralelas | Fora do controle | Acesso oculto | Inventário |
| T | Mudanças fora do fluxo | Sem governança | Quebra de segurança | Change mgmt |
| R | Falta de rastreio | Sem logs | Sem accountability | Auditoria |
| E | Privilégios excessivos | Concessão informal | Escalada | Revisão de acessos |

---

### E-mail Corporativo

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| S | Phishing | Falta de proteção | Fraude | DMARC/MFA |
| T | Alteração de mensagens | Conta comprometida | Aprovação falsa | Proteção de mailbox |
| R | Negação | Sem retenção | Falta de prova | Journaling |
| I | Vazamento | Erro humano | Exposição | DLP |

---

### Logs / SIEM

| STRIDE | Ameaça | Vulnerabilidade | Risco | Mitigação |
|--------|--------|----------------|------|-----------|
| T | Alteração de logs | Logs mutáveis | Ocultação | Imutabilidade |
| R | Falta de cobertura | Logs incompletos | Falha investigativa | Correlação |
| I | Exposição | Acesso amplo | Vazamento | RBAC |
| D | Sobrecarga | Falha de ingestão | Perda de visibilidade | Escalabilidade |

---

## ✅ Conclusão

A aplicação do STRIDE evidencia que os maiores riscos da TechCorp concentram-se em:

- **Gestão de identidade (IAM)**
- **Canais informais (chat e telefone)**
- **Ferramentas com alto privilégio (RMM/EDR)**
- **Shadow IT**

A mitigação deve priorizar:

- MFA e controle de identidade forte  
- Princípio do menor privilégio  
- Auditoria e rastreabilidade centralizada  
- Formalização de fluxos críticos via ITSM  

---

## 📎 Referências

- Microsoft STRIDE Model
- NIST SP 800-53
- ISO/IEC 27001 / 27005
- TechCorp Business Risk Policy (2026)
