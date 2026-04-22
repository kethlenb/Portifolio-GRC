# POLÍTICA DE CONTROLE DE ACESSO 

## Tabela de Controle Documental

| Campo | Informação |
|---|---|
| Título do Documento | Política de Controle de Acesso |
| Organização | TechCorp |
| Código do Documento | POL-IAM-001 |
| Versão | 1.0 |
| Classificação da Informação | Uso Interno |
| Proprietário do Documento | Gestão / GRC / Segurança |
| Aprovador | Diretoria / Patrocínio Executivo |
| Data de Emissão | 21/04/2026 |
| Data de Vigência | 01/05/2026 |
| Próxima Revisão | 21/04/2027 |
| Periodicidade de Revisão | Anual ou sob mudança relevante |
| Referenciais Normativos | ISO/IEC 27001, NIST CSF, CIS Controls, SOC 2 |
| Status | Em vigor após aprovação formal |

---

## Histórico de Versões

| Versão | Data | Descrição da Alteração | Autor | Aprovador |
|---|---|---|---|---|
| 1.0 | 21/04/2026 | Emissão inicial do documento | Kethlen B | Liderança Z |

---

## Sumário

- [1. Objetivo](#1-objetivo)
- [2. Escopo](#2-escopo)
- [3. Referenciais Normativos](#3-referenciais-normativos)
- [4. Princípios de Controle de Acesso](#4-princípios-de-controle-de-acesso)
- [5. Diretrizes Gerais](#5-diretrizes-gerais)
- [6. Identidades e Contas](#6-identidades-e-contas)
- [7. Concessão de Acesso](#7-concessão-de-acesso)
- [8. Acessos Privilegiados](#8-acessos-privilegiados)
- [9. Autenticação](#9-autenticação)
- [10. Reset de Senha e Recuperação de Acesso](#10-reset-de-senha-e-recuperação-de-acesso)
- [11. Atendimento Omnichannel e Validação de Identidade](#11-atendimento-omnichannel-e-validação-de-identidade)
- [12. Ambientes Co-Managed IT e Shadow IT](#12-ambientes-co-managed-it-e-shadow-it)
- [13. Monitoramento e Revisão de Acessos](#13-monitoramento-e-revisão-de-acessos)
- [14. Responsabilidades](#14-responsabilidades)
- [15. Matriz RACI](#15-matriz-raci)
- [16. Violações e Exceções](#16-violações-e-exceções)
- [17. Aprovação](#17-aprovação)
- [18. Anexo A – Script de Recusa Educada](#18-anexo-a--script-de-recusa-educada)
- [19. Anexo B – Mapeamento de Frameworks](#19-anexo-b--mapeamento-de-frameworks)

---

## 1. Objetivo

Estabelecer diretrizes para concessão, revisão, monitoramento, revogação e proteção de acessos a sistemas, ambientes, plataformas e informações administradas ou monitoradas pela TechCorp, assegurando confidencialidade, integridade, disponibilidade, rastreabilidade e conformidade.

---

## 2. Escopo

Esta Política aplica-se a:

- colaboradores da TechCorp;
- analistas;
- administradores e operadores técnicos;
- terceiros autorizados;
- contas de serviço;
- acessos a ambientes de clientes sob gestão ou co-gestão;
- plataformas de nuvem, Solução EDR, Plataforma RMM, Sistema ITSM com CMDB Integrado, Portal de chamados e demais sistemas corporativos.

---

## 3. Referenciais Normativos

Esta Política é fundamentada em:

- ISO/IEC 27001;
- NIST Cybersecurity Framework (NIST CSF);
- CIS Controls;
- SOC 2.

---

## 4. Princípios de Controle de Acesso

A TechCorp adota os seguintes princípios:

- menor privilégio;
- necessidade de negócio;
- segregação de funções;
- rastreabilidade;
- autenticação forte;
- revisão periódica;
- aprovação formal;
- ausência de confiança implícita;
- verificação contínua alinhada ao modelo Zero Trust.

---

## 5. Diretrizes Gerais

A TechCorp deve assegurar que:

- todo acesso seja individualizado, sempre que tecnicamente viável;
- contas genéricas sejam proibidas, salvo exceções formalmente justificadas;
- acessos sejam concedidos mediante necessidade comprovada e aprovação adequada;
- acessos privilegiados recebam controles adicionais;
- toda concessão, alteração e revogação de acesso seja registrada;
- todo acesso crítico possua trilha de auditoria;
- solicitações críticas por canal informal não sejam atendidas sem validação formal.

---

## 6. Identidades e Contas

As identidades e contas devem observar as seguintes diretrizes:

- cada usuário deve possuir credencial individual;
- contas compartilhadas devem ser evitadas e tratadas como exceção de risco;
- contas de serviço devem possuir finalidade definida, proprietário designado e revisão periódica;
- contas inativas, obsoletas ou sem proprietário devem ser desabilitadas;
- contas privilegiadas devem ser segregadas das contas de uso comum;
- o cadastro de pontos focais e aprovadores do cliente deve permanecer atualizado.

---

## 7. Concessão de Acesso

A concessão de acesso deve:

- ser baseada em função, necessidade operacional e menor privilégio;
- ser formalmente solicitada e aprovada;
- considerar perfil de acesso compatível com a responsabilidade do usuário;
- ser registrada em sistema corporativo;
- prever validade, escopo e responsável pela aprovação.

Nenhum acesso privilegiado deve ser concedido com base exclusivamente em solicitação verbal, mensagem instantânea ou relacionamento prévio.

---

## 8. Acessos Privilegiados

Os acessos privilegiados devem ser submetidos a controles reforçados.

Aplicam-se as seguintes regras:

- concessão somente mediante justificativa formal;
- aprovação por responsável autorizado;
- uso restrito ao necessário para a atividade;
- monitoramento reforçado;
- revisão periódica;
- revogação imediata quando cessar a necessidade;
- vedação de uso de contas privilegiadas para atividades rotineiras não administrativas, quando aplicável.

São considerados acessos privilegiados, entre outros:

- administrador global;
- administrador local;
- acesso à Plataforma RMM;
- administração da Solução EDR;
- administração de diretório e identidade;
- permissões elevadas em nuvem;
- acesso a configurações críticas de segurança.

---

## 9. Autenticação

A autenticação deve seguir os seguintes requisitos:

- uso de senhas fortes conforme padrão corporativo;
- habilitação obrigatória de MFA para acessos críticos e administrativos;
- proibição de compartilhamento de credenciais;
- proibição de armazenamento de credenciais em meios inseguros, incluindo navegadores, quando não aprovados;
- uso preferencial de autenticação centralizada;
- revisão periódica dos métodos de autenticação.

---

## 10. Reset de Senha e Recuperação de Acesso

A TechCorp deve priorizar automação segura de identidade, com adoção preferencial de SSPR no Entra ID/Azure, quando aplicável.

Diretrizes:

- resets manuais devem ser exceção;
- o usuário deve realizar sua própria autenticação sempre que houver mecanismo seguro disponível;
- redefinições de senha por telefone, chat ou mensageria informal não devem ser executadas sem validação formal;
- qualquer exceção deve ser registrada com justificativa e evidência.

---

## 11. Atendimento Omnichannel e Validação de Identidade

Nos canais telefone, Plataforma Omnichannel e Portal de chamados, devem ser observadas regras consistentes de validação de identidade.

Para ações críticas:

- a solicitação deve ser registrada;
- a identidade deve ser validada;
- a aprovação deve ser confirmada por canal formal e independente, quando aplicável;
- pedidos de alto impacto devem exigir validação cruzada.

Exemplo mínimo:
- pedido recebido por telefone;
- aprovação por e-mail corporativo do PoC cadastrado ou submissão formal no Portal;
- execução somente após confirmação válida.

---

## 12. Ambientes Co-Managed IT e Shadow IT

Nos ambientes em que exista TI interna do cliente com acessos administrativos paralelos:

- a TechCorp deve monitorar desvios de baseline;
- contas privilegiadas fora do padrão devem ser registradas e reportadas;
- a criação de admins paralelos deve ser tratada como risco de governança;
- se o cliente optar por manter tal condição, deve haver aceite formal do risco;
- a responsabilidade associada à manutenção desses acessos deve ser transferida e documentada quando fora da recomendação da TechCorp.

---

## 13. Monitoramento e Revisão de Acessos

A TechCorp deve:

- revisar periodicamente contas ativas;
- revisar acessos privilegiados;
- monitorar falhas de autenticação e comportamentos anômalos;
- manter trilhas de auditoria;
- registrar desvios e não conformidades;
- reportar ao cliente riscos associados a acessos indevidos, paralelos ou sem governança.

---

## 14. Responsabilidades

### 14.1 Gestão / GRC
- definir diretrizes;
- supervisionar aderência;
- revisar esta Política.

### 14.2 Segurança / Operações
- implementar controles;
- monitorar acessos privilegiados;
- reportar desvios.

### 14.3 Analistas
- validar identidade conforme procedimento;
- não executar ações críticas sem aprovação adequada;
- registrar evidências.

### 14.4 Cliente / PoC
- aprovar acessos conforme alçada;
- manter cadastro de aprovadores;
- formalizar aceite de risco quando aplicável.

---

## 15. Matriz RACI

| Atividade | Diretoria | Gestão/GRC | Segurança/Operações | Analistas | Cliente PoC | TI Interna do Cliente |
|---|---|---|---|---|---|---|
| Aprovar a política | A | R | C | I | I | I |
| Definir padrão de acesso | C | A/R | R | I | C | C |
| Conceder acesso privilegiado | I | C | A/R | I | C | I |
| Validar identidade em atendimento | I | C | C | A/R | C | I |
| Revisar contas privilegiadas | I | C | A/R | I | C | C |
| Reportar admin paralelo | I | C | A/R | R | C | C |
| Aceitar risco residual | I | C | C | I | A/R | C |

**Legenda:**  
- **R** = Responsible  
- **A** = Accountable  
- **C** = Consulted  
- **I** = Informed

---

## 16. Violações e Exceções

Qualquer concessão, alteração ou manutenção de acesso em desacordo com esta Política deve ser tratada como desvio de governança e segurança.

Exceções somente poderão ocorrer com:
- justificativa formal;
- análise de risco;
- aprovação adequada;
- registro do aceite residual.

---

## 17. Aprovação

| Nome | Cargo | Responsabilidade | Assinatura | Data |
|---|---|---|---|---|
| [preencher] | Diretoria Executiva | Aprovação final | [preencher] | [preencher] |
| [preencher] | Gestão / GRC | Elaboração e manutenção | [preencher] | [preencher] |
| [preencher] | Segurança / Operações | Validação técnica | [preencher] | [preencher] |

---

## 18. Anexo A – Script de Recusa Educada

> “Para sua segurança e em conformidade com nossa política de controle de acesso e governança, não podemos executar essa solicitação por este canal sem a validação formal exigida. Por gentileza, registre o pedido no Portal de chamados ou solicite a aprovação do responsável designado pelo cliente por meio do canal corporativo formalmente cadastrado.”

---

## 19. Anexo B – Mapeamento de Frameworks

| Tema | ISO/IEC 27001 | NIST CSF | CIS Controls | SOC 2 |
|---|---|---|---|---|
| Controle de acesso | Anexo A 5.15, 5.16, 5.18 | PR.AA | Control 5, 6 | Logical Access |
| MFA | Anexo A 5.17 | PR.AA | Control 6 | Logical Access |
| Revisão de privilégios | Anexo A 5.18 | PR.AA | Control 5 | Logical Access |
| Trilhas de auditoria | Anexo A 8.15, 8.16 | DE.CM | Control 8 | Monitoring Activities |
| Zero Trust / validação | Anexo A 5.15 | PR.AA, PR.PS | Control 6, 14 | Risk Mitigation |
| SSPR | Anexo A 5.17, 8.1 | PR.AA | Control 6 | Logical Access |
