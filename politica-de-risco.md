# POLÍTICA DE GESTÃO DE RISCOS

## Tabela de Controle Documental

| Campo | Informação |
|---|---|
| Título do Documento | Política de Gestão de Riscos |
| Organização | TechCorp |
| Código do Documento | POL-GRC-001 |
| Versão | 1.0 |
| Classificação da Informação | Uso Interno |
| Proprietário do Documento | Gestão / GRC |
| Aprovador | Diretoria / Patrocínio Executivo |
| Data de Emissão | 21/04/2026 |
| Data de Vigência | 01/05/2026 |
| Próxima Revisão | 21/04/2027 |
| Periodicidade de Revisão | Anual ou sob mudança relevante |
| Referenciais Normativos | CIS Controls, NIST CSF, ISO/IEC 27001, SOC 2, NIST RMF, ISO/IEC 27005, CVSS |
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
- [3. Hierarquia Documental](#3-hierarquia-documental)
- [4. Referenciais Normativos e Frameworks](#4-referenciais-normativos-e-frameworks)
- [5. Contexto Organizacional e Operacional](#5-contexto-organizacional-e-operacional)
- [6. Objetivos da Gestão de Riscos](#6-objetivos-da-gestão-de-riscos)
- [7. Princípios da Gestão de Riscos](#7-princípios-da-gestão-de-riscos)
- [8. Diretrizes Gerais de Gestão de Riscos](#8-diretrizes-gerais-de-gestão-de-riscos)
- [9. Identificação de Riscos](#9-identificação-de-riscos)
- [10. Critérios de Avaliação de Riscos](#10-critérios-de-avaliação-de-riscos)
- [11. Matriz Central de Riscos](#11-matriz-central-de-riscos)
- [12. Priorização de Vulnerabilidades com CVSS](#12-priorização-de-vulnerabilidades-com-cvss)
- [13. Tratamento de Riscos](#13-tratamento-de-riscos)
- [14. Governança de Ambientes Co-Managed IT e Shadow IT](#14-governança-de-ambientes-co-managed-it-e-shadow-it)
- [15. Controles de Governança e Segurança](#15-controles-de-governança-e-segurança)
- [16. Automação de Identidade e Redução de Risco Operacional](#16-automação-de-identidade-e-redução-de-risco-operacional)
- [17. Fator Humano, Engenharia Social e Modelo Zero Trust](#17-fator-humano-engenharia-social-e-modelo-zero-trust)
- [18. Atendimento Omnichannel e Regras de Solicitações Críticas](#18-atendimento-omnichannel-e-regras-de-solicitações-críticas)
- [19. Script Padrão de Recusa Educada](#19-script-padrão-de-recusa-educada)
- [20. Monitoramento Contínuo e Supervisão de Baseline](#20-monitoramento-contínuo-e-supervisão-de-baseline)
- [21. Indicadores e Métricas](#21-indicadores-e-métricas)
- [22. Cultura, Conscientização e Comportamentos de Risco](#22-cultura-conscientização-e-comportamentos-de-risco)
- [23. Papéis e Responsabilidades](#23-papéis-e-responsabilidades)
- [24. Matriz RACI](#24-matriz-raci)
- [25. Conformidade, Auditoria e Revisão](#25-conformidade-auditoria-e-revisão)
- [26. Violações e Exceções](#26-violações-e-exceções)
- [27. Disposições Finais](#27-disposições-finais)
- [28. Seção de Aprovação](#28-seção-de-aprovação)
- [29. Anexo A – Matriz Central de Riscos Robusta](#29-anexo-a--matriz-central-de-riscos-robusta)
- [30. Anexo B – Matriz Visual de Risco (Heatmap)](#30-anexo-b--matriz-visual-de-risco-heatmap)
- [31. Anexo C – Diretriz de Priorização de Vulnerabilidades](#31-anexo-c--diretriz-de-priorização-de-vulnerabilidades)
- [32. Anexo D – Mapeamento para ISO 27001, NIST CSF, CIS Controls e SOC 2](#32-anexo-d--mapeamento-para-iso-27001-nist-csf-cis-controls-e-soc-2)
- [33. Anexo E – Glossário](#33-anexo-e--glossário)

---

## 1. Objetivo

Estabelecer diretrizes formais para identificação, análise, avaliação, tratamento, monitoramento e comunicação de riscos relacionados aos serviços de TI gerenciados prestados pela TechCorp, garantindo alinhamento com os frameworks CIS Controls, NIST CSF, ISO/IEC 27001, SOC 2, NIST RMF e ISO/IEC 27005.

---

## 2. Escopo

Esta Política aplica-se a todos os serviços prestados pela TechCorp, incluindo:

- suporte técnico e atendimento de helpdesk;
- monitoramento remoto de ativos e infraestrutura por meio de Plataforma RMM;
- gestão de segurança da informação, incluindo controles de endpoint por Solução EDR, antivírus, autenticação e gestão de acesso;
- administração, consultoria, migração e gestão de ambientes em nuvem;
- operação de atendimento por Plataforma Omnichannel, telefone, chat integrado e Portal de chamados;
- gestão de ativos e registros por Sistema ITSM com CMDB Integrado;
- ambientes operados em modelo Co-Managed IT;
- ambientes com presença de Shadow IT ou administrações paralelas mantidas pelo cliente.

---

## 3. Hierarquia Documental

Para fins de governança, a TechCorp adota a seguinte hierarquia documental:

### 3.1 Política
Documento normativo que define princípios, diretrizes, regras de negócio, obrigações e limites institucionais. A Política descreve o que deve ser feito.

### 3.2 Procedimento
Documento operacional que descreve o passo a passo técnico e administrativo necessário para execução de uma atividade. O Procedimento descreve como fazer.

### 3.3 Guideline
Documento orientativo que apresenta recomendações, boas práticas e padrões desejáveis de adoção. O Guideline descreve como deveria ser feito, sem substituir exigências obrigatórias contidas em políticas e procedimentos.

---

## 4. Referenciais Normativos e Frameworks

Esta Política é fundamentada nos seguintes referenciais:

### 4.1 Governança e Controles
- CIS Controls
- NIST Cybersecurity Framework (NIST CSF)
- ISO/IEC 27001
- SOC 2

### 4.2 Gestão de Riscos
- NIST Risk Management Framework (NIST RMF)
- ISO/IEC 27005

### 4.3 Métrica de Vulnerabilidades
- CVSS – Common Vulnerability Scoring System, conforme padrão FIRST

---

## 5. Contexto Organizacional e Operacional

A TechCorp atua como provedor de serviços gerenciados, exercendo, na prática, funções equivalentes a um departamento de TI terceirizado para múltiplas empresas no modelo B2B.

Seu escopo operacional inclui, de forma integral ou parcial:

- suporte diário a usuários;
- monitoramento contínuo de ambientes tecnológicos;
- administração remota de infraestrutura;
- gestão de controles de segurança da informação;
- suporte a identidade e acesso;
- consultoria técnica e estratégica;
- migração e gestão de ambientes em nuvem.

A operação é realizada por equipe reduzida de 5 analistas, atendendo múltiplas empresas clientes em modelo omnichannel, o que impõe necessidade elevada de padronização, automação, priorização por risco e rigor de governança.

Adicionalmente, a TechCorp opera em cenários com:

- Co-Managed IT, nos quais o cliente mantém equipe interna de TI;
- Shadow IT, incluindo contas paralelas com privilégios elevados, como administradores locais;
- resistência cultural a controles de segurança, como uso de computadores compartilhados, armazenamento de senhas em navegadores e informalidade em solicitações críticas.

---

## 6. Objetivos da Gestão de Riscos

A gestão de riscos da TechCorp tem por objetivos:

- proteger os ativos de missão crítica dos clientes e da própria TechCorp;
- reduzir a probabilidade e o impacto de incidentes de segurança e falhas operacionais;
- apoiar a tomada de decisão baseada em risco;
- assegurar conformidade com requisitos contratuais, regulatórios e normativos;
- sustentar o monitoramento contínuo e a melhoria dos controles;
- formalizar a responsabilidade compartilhada em ambientes híbridos e Co-Managed.

---

## 7. Princípios da Gestão de Riscos

A gestão de riscos da TechCorp observará os seguintes princípios:

- abordagem estruturada, contínua e documentada;
- alinhamento ao contexto de negócio e aos ativos de missão crítica;
- priorização por impacto ao negócio;
- adoção de controles proporcionais ao risco;
- monitoramento contínuo e revisão periódica;
- rastreabilidade das decisões de tratamento;
- formalização de aceites de risco quando cabível;
- responsabilidade compartilhada claramente definida com o cliente.

---

## 8. Diretrizes Gerais de Gestão de Riscos

A TechCorp deve:

- identificar riscos associados a ativos, processos, pessoas, tecnologias, fornecedores e canais de atendimento;
- avaliar riscos considerando probabilidade, impacto e contexto operacional;
- priorizar o tratamento dos riscos que afetem ativos de missão crítica;
- implementar controles preventivos, detectivos e corretivos compatíveis com o nível de risco;
- monitorar continuamente desvios, quebras de baseline e fragilidades operacionais;
- registrar evidências de avaliação, tratamento, monitoramento e comunicação de riscos;
- reportar ao cliente situações que impliquem aceitação, transferência ou agravamento do risco.

---

## 9. Identificação de Riscos

Os riscos devem ser identificados considerando, no mínimo:

- ativos de informação;
- identidades privilegiadas;
- endpoints e servidores;
- ambientes em nuvem;
- ferramentas de administração remota;
- canais de atendimento e autenticação;
- dependências de terceiros;
- falhas humanas e comportamentais;
- práticas de Shadow IT;
- acessos administrativos paralelos;
- ausência, desativação ou bypass de controles de segurança.

Exemplos de eventos de risco relevantes ao contexto da TechCorp:

- desativação da Solução EDR por equipe interna do cliente;
- criação de contas administrativas locais fora do baseline aprovado;
- redefinição indevida de senha por canal informal;
- solicitação de acesso crítico por telefone ou mensagem sem validação formal;
- armazenamento de credenciais em navegadores;
- uso compartilhado de estações de trabalho;
- exploração de vulnerabilidades críticas em ativos monitorados;
- comprometimento de identidade por phishing, engenharia social ou deepfake de voz.

---

## 10. Critérios de Avaliação de Riscos

A avaliação de riscos deve considerar, de forma combinada:

- impacto ao negócio;
- probabilidade de ocorrência;
- exposição operacional;
- criticidade do ativo afetado;
- eficácia dos controles existentes;
- severidade técnica de vulnerabilidades, quando aplicável.

### 10.1 Impacto ao Negócio

A classificação de impacto deve observar especialmente os ativos de missão crítica.

#### Alto
Quando o evento puder resultar em:
- indisponibilidade relevante de operação do cliente;
- perda, exposição ou corrupção de dados sensíveis;
- impacto regulatório, contratual, financeiro ou reputacional significativo;
- comprometimento de contas privilegiadas ou sistemas centrais.

#### Médio
Quando o evento puder resultar em:
- degradação operacional relevante, porém contornável;
- retrabalho significativo;
- impacto limitado sobre produtividade ou serviços de suporte.

#### Baixo
Quando o evento puder resultar em:
- impacto restrito, localizado e reversível;
- pequeno atraso operacional;
- baixo potencial de dano financeiro, regulatório ou reputacional.

---

## 11. Matriz Central de Riscos

A TechCorp deve manter matriz central de riscos corporativos e operacionais, em conformidade com a ISO/IEC 27005 e com o modelo de categorização e monitoramento contínuo previsto no NIST RMF.

A matriz deve conter, no mínimo:

- identificação do risco;
- ativo ou processo afetado;
- causa e evento de risco;
- impacto ao negócio;
- probabilidade;
- controles existentes;
- nível de risco inerente;
- plano de tratamento;
- risco residual;
- responsável;
- status;
- aceite formal, quando aplicável.

A matriz deve priorizar riscos que afetem ativos de missão crítica, serviços centrais de autenticação, ferramentas administrativas, ambientes em nuvem, infraestrutura monitorada e operações de atendimento.

---

## 12. Priorização de Vulnerabilidades com CVSS

Toda vulnerabilidade identificada em ativos sob monitoramento ou administração da TechCorp deve ser classificada com base no CVSS, conforme padrão FIRST, a fim de garantir objetividade, rastreabilidade e consistência na triagem técnica.

A priorização de tratamento deve observar:

- CVSS de 9.0 a 10.0: prioridade crítica, com tratamento imediato;
- CVSS de 7.0 a 8.9: prioridade alta;
- CVSS de 4.0 a 6.9: prioridade média;
- CVSS abaixo de 4.0: prioridade baixa.

A severidade técnica da vulnerabilidade não substitui a análise de impacto ao negócio. A decisão final de priorização deve considerar a combinação entre criticidade do ativo, exposição, exploração conhecida, contexto operacional e impacto ao negócio.

---

## 13. Tratamento de Riscos

A TechCorp adota as seguintes respostas ao risco:

### 13.1 Mitigar
Aplicação de controles técnicos, processuais ou administrativos para reduzir probabilidade e/ou impacto.

### 13.2 Transferir
Transferência parcial do impacto ou da responsabilidade por meio contratual, securitário ou de aceite formal do cliente.

### 13.3 Evitar
Descontinuação de práticas, acessos ou arquiteturas que gerem risco incompatível com os requisitos de segurança e governança.

### 13.4 Aceitar
Aceitação formal do risco residual, preferencialmente pelo ponto focal designado pelo cliente, com registro no Sistema ITSM ou documento equivalente.

---

## 14. Governança de Ambientes Co-Managed IT e Shadow IT

Nos cenários em que o cliente mantém equipe interna de TI, acessos administrativos paralelos, contas locais privilegiadas ou mecanismos próprios de alteração do ambiente, a TechCorp adotará abordagem de monitoramento contínuo, supervisão e reporte.

Nesses casos:

- a TechCorp deve monitorar o ambiente por meio da Plataforma RMM e demais controles disponíveis;
- toda quebra de baseline, desativação de ferramenta de segurança ou criação de privilégio não autorizado deve ser registrada;
- desvios devem ser comunicados formalmente ao ponto focal do cliente;
- quando o cliente optar por manter a condição de risco, deverá ocorrer formalização de aceite de risco;
- a responsabilidade decorrente de decisões do cliente fora da baseline recomendada deverá ser transferida e registrada.

---

## 15. Controles de Governança e Segurança

Em alinhamento com CIS Controls, NIST CSF, ISO/IEC 27001 e SOC 2, a TechCorp estabelece como diretrizes mínimas:

- inventário e rastreabilidade de ativos por CMDB;
- controle de acesso baseado em menor privilégio;
- segregação de funções, quando aplicável;
- autenticação multifator para acessos críticos;
- supervisão contínua de endpoints e servidores por Solução EDR;
- monitoramento remoto e detecção de desvios por Plataforma RMM;
- gestão formal de chamados, aprovações e evidências por Sistema ITSM com CMDB Integrado;
- revisão periódica de contas privilegiadas;
- registro e retenção de trilhas de auditoria;
- proteção de identidades e credenciais;
- monitoramento de conformidade de baseline.

---

## 16. Automação de Identidade e Redução de Risco Operacional

Para reduzir exposição decorrente de interação humana desnecessária em processos sensíveis, a TechCorp deve priorizar mecanismos de automação segura.

Como diretriz obrigatória, deve ser promovido o uso de SSPR (Self-Service Password Reset) no Entra ID/Azure, sempre que tecnicamente aplicável, com os seguintes objetivos:

- reduzir a carga operacional da equipe de suporte;
- evitar redefinições manuais de senha por atendentes;
- assegurar que a autenticação e validação sejam realizadas pelo próprio usuário;
- diminuir o risco de fraude por engenharia social;
- padronizar o processo de recuperação de acesso.

---

## 17. Fator Humano, Engenharia Social e Modelo Zero Trust

Com base no NIST CSF, a TechCorp adota princípios de Zero Trust para validação de identidades e execução de ações críticas.

Nenhuma solicitação de alto impacto deve ser executada com base exclusiva em confiança implícita, familiaridade com o solicitante, reconhecimento de voz, histórico de contato ou canal isolado.

### 17.1 Diretrizes Obrigatórias

- toda solicitação crítica deve ser validada com autenticação e/ou aprovação formal adequada;
- pedidos recebidos por canal informal não devem, isoladamente, fundamentar ações críticas;
- aprovações devem ser realizadas por responsável previamente cadastrado;
- deve ser adotada verificação cruzada de canais para reduzir risco de fraude.

### 17.2 Riscos Explicitamente Considerados

- phishing;
- pretexting;
- engenharia social por familiaridade;
- deepfakes de voz;
- spoofing de identidade;
- bypass de portal por contato telefônico, mensagem instantânea ou chat informal.

### 17.3 Controle de Validação Cruzada

Como diretriz mínima, pedidos críticos realizados por telefone, chat ou mensageria devem exigir aprovação formal por canal independente, tal como e-mail corporativo do gestor ou ponto focal previamente designado, ou submissão formal no Portal de chamados conforme regra de negócio aplicável.

Exemplo:
- pedido via telefone;
- validação adicional via e-mail corporativo do gestor responsável ou registro formal em Portal de chamados;
- somente após confirmação formal o atendimento poderá prosseguir.

---

## 18. Atendimento Omnichannel e Regras de Solicitações Críticas

O atendimento omnichannel da TechCorp deve operar sob controles consistentes entre canais, assegurando que conveniência não comprometa governança, rastreabilidade e segurança.

Aplicam-se as seguintes regras:

- toda solicitação deve ser registrada no Sistema ITSM;
- solicitações críticas devem ter vínculo com identidade validada;
- ações privilegiadas exigem evidência formal de autorização;
- o Portal de chamados é o canal preferencial para solicitações sensíveis;
- interações por telefone, Plataforma Omnichannel e chat integrado devem ser tratadas como canais de recepção, não como mecanismo isolado de aprovação;
- exceções devem ser justificadas, registradas e aprovadas conforme regra vigente.

São consideradas ações críticas, entre outras:

- redefinição de senha administrativa;
- remoção de MFA;
- concessão de privilégio elevado;
- liberação de acesso a dados sensíveis;
- desativação de controles de segurança;
- instalação de software fora de padrão;
- alteração de conta privilegiada;
- autorização para acesso remoto excepcional.

---

## 19. Script Padrão de Recusa Educada

Sempre que houver solicitação de acesso crítico, redefinição sensível ou ação privilegiada por canal informal ou sem a devida validação, os analistas devem utilizar linguagem padronizada e objetiva.

### Script padrão

> “Para sua segurança e em conformidade com nossa política de governança e controle de acessos, não podemos executar essa solicitação por este canal sem a validação formal exigida. Por gentileza, registre o pedido no Portal de chamados ou solicite a aprovação do responsável designado pelo cliente por meio do canal corporativo formalmente cadastrado. Assim garantimos a proteção do ambiente, a rastreabilidade do atendimento e a conformidade do processo.”

### Diretriz complementar

Em nenhuma hipótese o analista deve flexibilizar a exigência de validação formal com base em urgência alegada, relacionamento prévio, reconhecimento de voz, pressão hierárquica informal ou conveniência operacional.

---

## 20. Monitoramento Contínuo e Supervisão de Baseline

Em alinhamento com SOC 2 e com os princípios de detecção e monitoramento contínuo do NIST CSF e do NIST RMF, a TechCorp deve manter supervisão ativa dos ambientes sob sua gestão ou monitoramento.

Essa supervisão deve incluir, no mínimo:

- conformidade de endpoints e servidores com a baseline aprovada;
- estado de operação da Solução EDR;
- integridade da Plataforma RMM;
- eventos de desativação de controles;
- criação ou uso de contas privilegiadas fora do padrão;
- alterações relevantes de configuração;
- indicadores de vulnerabilidades em ativos críticos;
- evidências de falha de processo ou bypass de governança.

Toda quebra de baseline identificada deve ser:
- registrada;
- classificada quanto ao risco;
- comunicada ao cliente;
- acompanhada até saneamento, aceite de risco ou transferência formal de responsabilidade.

---

## 21. Indicadores e Métricas

A TechCorp deve definir e acompanhar indicadores mínimos de risco e segurança, incluindo:

- quantidade de vulnerabilidades críticas por ativo ou cliente;
- tempo médio de tratamento de vulnerabilidades por severidade;
- volume de incidentes relacionados a identidade e acesso;
- número de solicitações críticas recusadas por ausência de validação formal;
- número de quebras de baseline registradas;
- quantidade de desativações de Solução EDR ou controles correlatos;
- reincidência de comportamentos inseguros relacionados ao fator humano;
- tempo médio de resposta e contenção de incidentes;
- volume de riscos aceitos formalmente por cliente.

---

## 22. Cultura, Conscientização e Comportamentos de Risco

A TechCorp reconhece que fatores culturais e comportamentais representam risco relevante à segurança da informação e à continuidade operacional.

Devem ser tratados como riscos, entre outros:

- uso de computadores compartilhados;
- armazenamento de senhas em navegadores;
- compartilhamento de credenciais;
- uso de contas genéricas;
- resistência ao MFA;
- informalidade na solicitação de acessos;
- tentativa de contornar fluxos formais de aprovação.

A TechCorp deve:

- orientar os clientes sobre os riscos associados a essas práticas;
- recomendar medidas corretivas e preventivas;
- registrar desvios recorrentes;
- escalar situações de risco ao ponto focal do cliente;
- formalizar aceite de risco quando o cliente optar por manter a prática.

---

## 23. Papéis e Responsabilidades

### 23.1 TechCorp
Compete à TechCorp:

- manter processo estruturado de gestão de riscos;
- monitorar ativos e eventos sob sua responsabilidade contratual;
- registrar e reportar desvios, vulnerabilidades e incidentes;
- recomendar controles e medidas de tratamento;
- preservar evidências de atendimento, análise e comunicação;
- operar processos de suporte e segurança conforme esta Política.

### 23.2 Analistas
Compete aos analistas:

- seguir estritamente os fluxos de validação e aprovação;
- registrar atendimentos no sistema corporativo;
- recusar solicitações críticas sem formalização adequada;
- escalar situações de exceção, fraude suspeita ou quebra de governança;
- observar os procedimentos aplicáveis.

### 23.3 Cliente
Compete ao cliente:

- designar pontos focais e aprovadores formais;
- manter governança mínima sobre sua equipe interna;
- comunicar alterações relevantes no ambiente;
- avaliar e responder aos reportes da TechCorp;
- formalizar aceites de risco quando optar por manter exposição não recomendada.

### 23.4 Equipes Internas de TI do Cliente
Quando existentes, devem atuar de forma coordenada com a TechCorp, respeitando baselines, fluxos de comunicação e responsabilidades definidas. Alterações unilaterais que comprometam controles, rastreabilidade ou segurança poderão resultar em reporte formal e transferência de responsabilidade pelo risco.

---

## 24. Matriz RACI

| Atividade | Diretoria TechCorp | GRC / Gestão | Analistas | Segurança / Operações | Cliente PoC | TI Interna do Cliente |
|---|---|---|---|---|---|---|
| Aprovar a Política | A | R | I | I | C | I |
| Revisar periodicamente a Política | C | A/R | I | C | I | I |
| Identificar riscos | I | A/R | C | R | C | C |
| Avaliar riscos | I | A/R | I | R | C | C |
| Definir tratamento de riscos | C | A/R | I | R | C | C |
| Implementar controles técnicos | I | C | I | A/R | C | C |
| Registrar chamados e evidências | I | C | A/R | C | I | I |
| Validar solicitação crítica | I | C | R | C | A/R | I |
| Reportar quebra de baseline | I | C | R | A/R | C | C |
| Aceitar risco residual | I | C | I | C | A/R | C |
| Monitorar conformidade contínua | I | C | C | A/R | I | C |
| Auditar aderência à Política | C | A/R | I | C | I | I |

**Legenda:**  
- **R** = Responsible  
- **A** = Accountable  
- **C** = Consulted  
- **I** = Informed  

---

## 25. Conformidade, Auditoria e Revisão

Esta Política deve ser revisada periodicamente, no mínimo uma vez ao ano, ou sempre que ocorrer:

- mudança relevante no modelo operacional;
- alteração significativa de serviços ou tecnologias adotadas;
- incidente relevante de segurança;
- mudança regulatória ou contratual aplicável;
- atualização substancial dos frameworks de referência.

A aderência a esta Política poderá ser verificada por meio de:
- auditorias internas;
- revisões gerenciais;
- análise de evidências operacionais;
- monitoramento técnico e administrativo;
- avaliações de maturidade e conformidade.

---

## 26. Violações e Exceções

Descumprimentos desta Política devem ser registrados, avaliados e tratados conforme sua gravidade e impacto.

Exceções somente poderão ser admitidas quando:
- houver justificativa formal;
- o risco for claramente avaliado;
- existir aprovação adequada;
- o aceite residual estiver devidamente documentado.

Na ausência de aprovação formal, a exceção não será considerada válida.

---

## 27. Disposições Finais

Esta Política entra em vigor na data de sua aprovação e deve ser observada por todos os profissionais da TechCorp envolvidos na prestação, supervisão, gestão ou suporte dos serviços abrangidos.

O não cumprimento desta Política poderá resultar em:
- aumento da exposição a riscos operacionais e de segurança;
- necessidade de escalonamento formal ao cliente;
- registro de não conformidade;
- limitação de determinadas ações operacionais;
- formalização de aceite de risco pelo cliente, quando aplicável.

A TechCorp reafirma, por meio deste documento, seu compromisso com governança, segurança, rastreabilidade, monitoramento contínuo e gestão de riscos orientada ao negócio.

---

## 28. Seção de Aprovação

| Nome | Cargo | Responsabilidade | Assinatura | Data |
|---|---|---|---|---|
| [preencher] | Diretoria Executiva | Aprovação final | [preencher] | [preencher] |
| [preencher] | Gestão / GRC | Elaboração e manutenção | [preencher] | [preencher] |
| [preencher] | Segurança / Operações | Validação técnica | [preencher] | [preencher] |

---

## 29. Anexo A – Matriz Central de Riscos Robusta

| ID | Risco | Categoria | Ativo de Missão Crítica | Cenário / Evento | Ameaça | Vulnerabilidade / Fraqueza | Impacto no Negócio | Probabilidade | Controles Existentes | CVSS | Nível Inerente | Tratamento | Responsável | Prazo | Risco Residual | Aceite Formal | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R-001 | Desativação da Solução EDR por TI interna do cliente | Segurança / Governança | Endpoints administrativos | Controle é desligado sem alinhamento | Shadow IT | Admin paralelo | Alto | Médio | RMM, alertas, ITSM, reporte formal | N/A | Alto | Reportar, exigir saneamento ou formalizar aceite | Operações / Cliente | Imediato | Médio | Sim, se mantido | Em acompanhamento |
| R-002 | Reset indevido de senha por canal informal | Identidade e Acesso | Contas corporativas | Usuário solicita reset por telefone ou chat | Engenharia social | Processo informal | Alto | Médio | Portal, aprovação formal, SSPR | N/A | Alto | Bloquear execução sem validação formal | Service Desk | Imediato | Baixo | Não | Mitigando |
| R-003 | Armazenamento de senhas em navegador | Fator Humano | Credenciais corporativas | Usuários mantêm credenciais salvas localmente | Furto de credenciais | Má prática do usuário | Médio | Alto | Awareness, orientação, reporte | N/A | Alto | Conscientização, política, aceite se reincidente | Cliente / TechCorp | 30 dias | Médio | Sim, se mantido | Monitorado |
| R-004 | Vulnerabilidade crítica em servidor gerenciado | Vulnerabilidades | Servidor de produção | Exploração de falha conhecida | Exploit remoto | Patch ausente | Alto | Médio | Scan, priorização CVSS, patching | 9.8 | Crítico | Correção imediata | Infra / Segurança | Imediato | Médio | Não | Aberto |
| R-005 | Deepfake de voz para solicitação crítica | Engenharia Social | Identidade privilegiada | Fraudador simula gestor por telefone | Fraude | Validação fraca por voz | Alto | Médio | Validação cruzada, Portal, PoC | N/A | Alto | Exigir dupla validação por canal independente | Service Desk / Gestão | Imediato | Baixo | Não | Mitigando |
| R-006 | Bypass do Portal de chamados via WhatsApp | Processo / Atendimento | Fluxo de autorização | Solicitação crítica fora do processo formal | Bypass processual | Dependência excessiva de canal informal | Alto | Alto | Script de recusa, ITSM, PoC | N/A | Crítico | Reforçar bloqueio processual e registro obrigatório | Service Desk | Imediato | Médio | Não | Em acompanhamento |
| R-007 | Uso de computadores compartilhados | Fator Humano / Operacional | Sessões de usuário | Múltiplos usuários acessam mesma estação | Uso indevido | Ausência de segregação | Médio | Alto | Orientação, hardening, controle de sessão | N/A | Alto | Restringir prática e formalizar risco | Cliente | 60 dias | Médio | Sim | Monitorado |
| R-008 | Criação de administrador local não homologado | Governança / Acesso | Endpoints críticos | TI interna cria privilégio elevado | Shadow IT | Falta de controle central | Alto | Médio | RMM, baseline, relatório | N/A | Alto | Reportar e exigir regularização | Operações / Cliente | 7 dias | Médio | Sim, se mantido | Aberto |
| R-009 | Remoção de MFA de conta crítica | Identidade e Acesso | Conta administrativa | Usuário solicita exceção indevida | Fraude / erro operacional | Processo de exceção fraco | Alto | Médio | Aprovação formal, trilha de auditoria | N/A | Alto | Proibir sem aprovação formal do PoC | Gestão / IAM | Imediato | Baixo | Não | Controlado |
| R-010 | Ferramenta remota não homologada instalada pela TI interna | Terceiros / Shadow IT | Ambiente administrado | Ferramenta paralela cria novo vetor de acesso | Acesso indevido | Falta de homologação | Alto | Médio | Monitoramento RMM, inventário CMDB | N/A | Alto | Reportar, remover ou formalizar aceite | Operações / Cliente | 15 dias | Médio | Sim | Monitorado |

---

## 30. Anexo B – Matriz Visual de Risco (Heatmap)

### 30.1 Escala de Probabilidade
| Valor | Classificação |
|---|---|
| 1 | Rara |
| 2 | Improvável |
| 3 | Possível |
| 4 | Provável |
| 5 | Quase certa |

### 30.2 Escala de Impacto
| Valor | Classificação |
|---|---|
| 1 | Insignificante |
| 2 | Baixo |
| 3 | Moderado |
| 4 | Alto |
| 5 | Crítico |

### 30.3 Heatmap Qualitativo

| Impacto \ Probabilidade | 1 Rara | 2 Improvável | 3 Possível | 4 Provável | 5 Quase certa |
|---|---|---|---|---|---|
| 5 Crítico | Médio | Alto | Alto | Crítico | Crítico |
| 4 Alto | Médio | Médio | Alto | Alto | Crítico |
| 3 Moderado | Baixo | Médio | Médio | Alto | Alto |
| 2 Baixo | Baixo | Baixo | Médio | Médio | Alto |
| 1 Insignificante | Baixo | Baixo | Baixo | Médio | Médio |

### 30.4 Referência Visual Simplificada
- **Baixo** = aceitável sob monitoramento
- **Médio** = requer plano de ação e acompanhamento
- **Alto** = requer tratamento prioritário
- **Crítico** = requer ação imediata e escalonamento

### 30.5 Exemplo de Posicionamento de Riscos

| ID | Risco | Impacto | Probabilidade | Classificação |
|---|---|---|---|---|
| R-001 | Desativação de EDR por TI interna | 4 | 3 | Alto |
| R-002 | Reset de senha por canal informal | 4 | 3 | Alto |
| R-004 | Vulnerabilidade crítica em servidor | 5 | 3 | Alto |
| R-005 | Deepfake de voz | 4 | 3 | Alto |
| R-006 | Bypass do portal via WhatsApp | 4 | 4 | Alto |
| R-007 | Computadores compartilhados | 3 | 4 | Alto |

---

## 31. Anexo C – Diretriz de Priorização de Vulnerabilidades

| Faixa CVSS | Classificação | Diretriz de Priorização |
|---|---|---|
| 9.0 – 10.0 | Crítica | Tratamento imediato |
| 7.0 – 8.9 | Alta | Tratamento prioritário |
| 4.0 – 6.9 | Média | Planejamento e tratamento conforme risco |
| 0.1 – 3.9 | Baixa | Tratamento oportunístico ou aceitação justificada |

---

## 32. Anexo D – Mapeamento para ISO 27001, NIST CSF, CIS Controls e SOC 2

| Tema da Política | ISO/IEC 27001 | NIST CSF | CIS Controls | SOC 2 |
|---|---|---|---|---|
| Governança e definição de diretrizes | Cláusulas 4, 5 e 6 | Govern (GV) | Control 17 | Control Environment |
| Gestão de riscos | Cláusula 6; Anexo A 5.7, 5.9 | Identify (ID.RA) | Control 4, 7, 15 | Risk Assessment |
| Inventário de ativos e CMDB | Anexo A 5.9, 5.10 | ID.AM | Control 1, 2 | Logical and Physical Access Controls |
| Controle de acesso e privilégios | Anexo A 5.15, 5.16, 5.18 | PR.AA | Control 5, 6 | Logical Access |
| MFA e autenticação forte | Anexo A 5.17, 5.18 | PR.AA | Control 6 | Logical Access |
| SSPR e automação segura de identidade | Anexo A 5.17, 8.1 | PR.AA, PR.PT | Control 6 | Logical Access / Change Management |
| Gestão de vulnerabilidades com CVSS | Anexo A 8.8, 8.9 | ID.RA, PR.IP | Control 7 | Risk Mitigation |
| Monitoramento contínuo com RMM e EDR | Anexo A 8.15, 8.16 | DE.CM | Control 8, 13 | System Operations |
| Atendimento omnichannel com rastreabilidade | Anexo A 5.24, 5.25, 8.15 | PR.PS, DE.CM | Control 8, 17 | Monitoring Activities |
| Zero Trust e validação cruzada | Anexo A 5.15, 5.17 | PR.AA, PR.PS | Control 5, 6, 14 | Logical Access / Risk Mitigation |
| Engenharia social e conscientização | Anexo A 6.3 | PR.AT | Control 14 | Control Environment / Training |
| Co-Managed IT e Shadow IT | Anexo A 5.19, 5.20, 5.23 | ID.GV, DE.CM | Control 1, 5, 13 | Monitoring Activities / Risk Assessment |
| Reporte de desvios e aceite de risco | Cláusulas 6, 9 e 10 | ID.RA, GV.RM | Control 17 | Risk Assessment / Monitoring |
| Trilhas de auditoria e evidências | Anexo A 8.15, 8.16 | DE.CM, RC.RP | Control 8 | Monitoring Activities |
| Revisão da política e melhoria contínua | Cláusulas 9 e 10 | Govern (GV) | Control 17 | Monitoring Activities / Control Environment |

## 33. Anexo E – Glossário

- **MSP**: Managed Service Provider.
- **Co-Managed IT**: modelo em que a operação é compartilhada entre o provedor e a equipe interna do cliente.
- **Shadow IT**: uso ou gestão de tecnologia sem alinhamento formal com a governança definida.
- **RMM**: plataforma de monitoramento e gerenciamento remoto.
- **EDR**: solução de detecção e resposta em endpoints.
- **ITSM**: sistema de gestão de serviços de TI.
- **CMDB**: base de dados de configuração.
- **SSPR**: Self-Service Password Reset.
- **PoC**: ponto focal designado pelo cliente.
- **Baseline**: configuração mínima aprovada e monitorada.
- **CVSS**: modelo padronizado de pontuação de severidade de vulnerabilidades.
- **Zero Trust**: modelo de segurança baseado em verificação contínua e ausência de confiança implícita.
