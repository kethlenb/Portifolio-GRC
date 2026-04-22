# POLÍTICA DE GESTÃO DE VULNERABILIDADES

## Tabela de Controle Documental

| Campo | Informação |
|---|---|
| Título do Documento | Política de Gestão de Vulnerabilidades |
| Organização | TechCorp |
| Código do Documento | POL-VM-001 |
| Versão | 1.0 |
| Classificação da Informação | Uso Interno |
| Proprietário do Documento | Gestão / GRC / Segurança |
| Aprovador | Diretoria / Patrocínio Executivo |
| Data de Emissão | 21/04/2026 |
| Data de Vigência | 01/05/2026 |
| Próxima Revisão | 21/04/2027 |
| Periodicidade de Revisão | Anual ou sob mudança relevante |
| Referenciais Normativos | ISO/IEC 27001, NIST CSF, CIS Controls, NIST RMF, ISO/IEC 27005, CVSS |
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
- [4. Princípios](#4-princípios)
- [5. Diretrizes Gerais](#5-diretrizes-gerais)
- [6. Identificação de Vulnerabilidades](#6-identificação-de-vulnerabilidades)
- [7. Classificação e Priorização com CVSS](#7-classificação-e-priorização-com-cvss)
- [8. Tratamento e Remediação](#8-tratamento-e-remediação)
- [9. Exceções e Aceite de Risco](#9-exceções-e-aceite-de-risco)
- [10. Ambientes Co-Managed IT e Shadow IT](#10-ambientes-co-managed-it-e-shadow-it)
- [11. Monitoramento Contínuo](#11-monitoramento-contínuo)
- [12. Indicadores](#12-indicadores)
- [13. Responsabilidades](#13-responsabilidades)
- [14. Matriz RACI](#14-matriz-raci)
- [15. Aprovação](#15-aprovação)
- [16. Anexo A – Tabela de Priorização](#16-anexo-a--tabela-de-priorização)
- [17. Anexo B – Mapeamento de Frameworks](#17-anexo-b--mapeamento-de-frameworks)

---

## 1. Objetivo

Estabelecer diretrizes para identificação, classificação, priorização, tratamento, monitoramento e reporte de vulnerabilidades em ativos e ambientes sob responsabilidade, administração ou monitoramento da TechCorp.

---

## 2. Escopo

Esta Política aplica-se a:

- endpoints;
- servidores;
- ativos em nuvem;
- identidades e sistemas de autenticação;
- ferramentas administrativas;
- ativos registrados em CMDB;
- ambientes de clientes gerenciados ou co-gerenciados pela TechCorp.

---

## 3. Referenciais Normativos

- ISO/IEC 27001
- ISO/IEC 27005
- NIST RMF
- NIST CSF
- CIS Controls
- CVSS (FIRST)

---

## 4. Princípios

A TechCorp adota os seguintes princípios para gestão de vulnerabilidades:

- abordagem contínua e baseada em risco;
- priorização orientada ao impacto no negócio;
- objetividade técnica com uso de CVSS;
- rastreabilidade;
- tempestividade na remediação;
- monitoramento contínuo;
- reporte formal de exposição residual;
- responsabilidade compartilhada em ambientes Co-Managed.

---

## 5. Diretrizes Gerais

A TechCorp deve:

- identificar vulnerabilidades em ativos monitorados ou administrados;
- classificar vulnerabilidades com base em criticidade técnica e impacto ao negócio;
- priorizar ativos de missão crítica;
- definir tratamento compatível com severidade e exposição;
- acompanhar remediação até saneamento, mitigação compensatória ou aceite de risco;
- registrar evidências e decisões.

---

## 6. Identificação de Vulnerabilidades

A identificação pode ocorrer por meio de:

- ferramentas de varredura;
- alertas de fabricantes;
- inteligência de ameaças;
- monitoramento da Solução EDR;
- monitoramento da Plataforma RMM;
- análise técnica de incidentes;
- auditorias e revisões de conformidade.

Devem ser priorizadas vulnerabilidades presentes em:
- sistemas expostos à internet;
- contas e identidades privilegiadas;
- ativos de produção;
- servidores centrais;
- soluções de acesso remoto;
- ferramentas de administração.

---

## 7. Classificação e Priorização com CVSS

Toda vulnerabilidade deve ser classificada com base no CVSS, conforme padrão FIRST.

Faixas de referência:
- 9.0 a 10.0: crítica;
- 7.0 a 8.9: alta;
- 4.0 a 6.9: média;
- abaixo de 4.0: baixa.

A priorização final deve considerar também:
- ativo afetado;
- exposição externa;
- existência de exploração conhecida;
- controles compensatórios;
- impacto ao negócio;
- criticidade operacional.

---

## 8. Tratamento e Remediação

O tratamento pode envolver:

- aplicação de patches;
- ajuste de configuração;
- hardening;
- isolamento do ativo;
- restrição de acesso;
- compensação por controle adicional;
- substituição tecnológica;
- descontinuação do ativo vulnerável.

Vulnerabilidades críticas devem receber tratamento imediato ou mitigação compensatória documentada.

---

## 9. Exceções e Aceite de Risco

Quando a vulnerabilidade não puder ser corrigida no prazo esperado:

- a justificativa deve ser formalizada;
- o risco deve ser avaliado;
- controles compensatórios devem ser considerados;
- o cliente deve ser comunicado quando o ativo for de sua titularidade ou operação compartilhada;
- o aceite residual deve ser documentado quando aplicável.

---

## 10. Ambientes Co-Managed IT e Shadow IT

Nos ambientes em que a TI interna do cliente realize alterações sem governança conjunta:

- a TechCorp deve monitorar e reportar desvios que ampliem exposição;
- a recusa do cliente em corrigir vulnerabilidades críticas deve ser formalmente registrada;
- a manutenção deliberada de exposição deve resultar em aceite formal do risco pelo cliente;
- a responsabilidade associada deve ser transferida e documentada quando fora da recomendação técnica.

---

## 11. Monitoramento Contínuo

A TechCorp deve manter monitoramento contínuo de:

- ativos com vulnerabilidades críticas;
- reincidência de falhas;
- atrasos de remediação;
- sistemas com patching pendente;
- quebra de baseline;
- controles compensatórios aplicados.

---

## 12. Indicadores

Indicadores mínimos:
- quantidade de vulnerabilidades por severidade;
- tempo médio de remediação;
- percentual de ativos críticos corrigidos no prazo;
- volume de exceções abertas;
- quantidade de aceites de risco por cliente;
- reincidência de vulnerabilidades em ativos já tratados.

---

## 13. Responsabilidades

### 13.1 Gestão / GRC
- definir diretrizes e supervisionar aderência.

### 13.2 Segurança / Operações
- identificar, classificar, priorizar e acompanhar remediação.

### 13.3 Analistas Técnicos
- executar correções conforme procedimento;
- registrar evidências;
- escalar impedimentos.

### 13.4 Cliente / PoC
- aprovar janelas de mudança quando necessário;
- responder a reportes;
- formalizar aceite de risco quando optar por não tratar exposição relevante.

---

## 14. Matriz RACI

| Atividade | Diretoria | Gestão/GRC | Segurança/Operações | Analistas Técnicos | Cliente PoC | TI Interna do Cliente |
|---|---|---|---|---|---|---|
| Aprovar a política | A | R | C | I | I | I |
| Identificar vulnerabilidades | I | C | A/R | R | I | C |
| Classificar com CVSS | I | C | A/R | R | I | I |
| Definir prioridade | I | C | A/R | C | C | C |
| Executar remediação | I | I | C | A/R | C | C |
| Reportar exposição residual | I | C | A/R | C | C | I |
| Formalizar aceite de risco | I | C | C | I | A/R | C |

**Legenda:**  
- **R** = Responsible  
- **A** = Accountable  
- **C** = Consulted  
- **I** = Informed

---

## 15. Aprovação

| Nome | Cargo | Responsabilidade | Assinatura | Data |
|---|---|---|---|---|
| [preencher] | Diretoria Executiva | Aprovação final | [preencher] | [preencher] |
| [preencher] | Gestão / GRC | Elaboração e manutenção | [preencher] | [preencher] |
| [preencher] | Segurança / Operações | Validação técnica | [preencher] | [preencher] |

---

## 16. Anexo A – Tabela de Priorização

| Faixa CVSS | Severidade | Diretriz |
|---|---|---|
| 9.0 – 10.0 | Crítica | Tratamento imediato |
| 7.0 – 8.9 | Alta | Tratamento prioritário |
| 4.0 – 6.9 | Média | Planejamento conforme risco |
| 0.1 – 3.9 | Baixa | Tratamento oportunístico ou aceite |

---

## 17. Anexo B – Mapeamento de Frameworks

| Tema | ISO/IEC 27001 | ISO/IEC 27005 | NIST RMF / CSF | CIS Controls | SOC 2 |
|---|---|---|---|---|---|
| Gestão de vulnerabilidades | Anexo A 8.8, 8.9 | Análise e tratamento de risco | ID.RA, PR.IP | Control 7 | Risk Assessment |
| Priorização por criticidade | Cláusula 6 | Avaliação de risco | ID.RA | Control 4, 7 | Risk Mitigation |
| Monitoramento contínuo | Anexo A 8.15, 8.16 | Monitoramento | DE.CM | Control 8 | Monitoring Activities |
| Aceite de risco | Cláusula 6 | Tratamento / aceite | GV.RM | Control 17 | Risk Assessment |
| Exposição em Co-Managed IT | Anexo A 5.19, 5.23 | Contexto e risco compartilhado | ID.GV | Control 1, 13 | Monitoring Activities |
