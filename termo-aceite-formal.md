# TERMO DE ACEITE FORMAL DE RISCO

## Tabela de Controle Documental

| Campo                        | Informação                                                              |
|------------------------------|-------------------------------------------------------------------------|
| Título do Documento          | Termo de Aceite Formal de Risco                                         |
| Organização                  | TechCorp                                                                |
| Código do Documento          | TMPL-GRC-001                                                            |
| Versão                       | 1.0                                                                     |
| Classificação da Informação  | Uso Interno / Confidencial                                              |
| Proprietário do Documento    | Gestão / GRC                                                            |
| Aprovador                    | Diretoria / Patrocínio Executivo                                        |
| Data de Emissão              | 21/04/2026                                                             |
| Periodicidade de Revisão     | Anual ou sob mudança relevante                                          |
| Referenciais Normativos      | ISO/IEC 27001, ISO/IEC 27005, NIST RMF, CIS Controls, SOC 2            |
| Status                       | Em vigor após aprovação formal                                          |

---

## Histórico de Versões

| Versão | Data         | Descrição da Alteração        | Autor        | Aprovador    |
|--------|--------------|-------------------------------|--------------|--------------|
| 1.0    | 21/04/2026  | Emissão inicial do documento  | Kethlen B  | Liderança Z  |

---

## Sumário

- [1. Finalidade](#1-finalidade)
- [2. Base Normativa](#2-base-normativa)
- [3. Quando Utilizar](#3-quando-utilizar)
- [4. Instruções de Preenchimento](#4-instruções-de-preenchimento)
- [5. Identificação do Termo](#5-identificação-do-termo)
- [6. Identificação das Partes](#6-identificação-das-partes)
- [7. Identificação e Descrição do Risco](#7-identificação-e-descrição-do-risco)
- [8. Análise do Risco](#8-análise-do-risco)
- [9. Recomendação Técnica da TechCorp](#9-recomendação-técnica-da-techcorp)
- [10. Decisão do Cliente](#10-decisão-do-cliente)
- [11. Condições e Limitações de Responsabilidade](#11-condições-e-limitações-de-responsabilidade)
- [12. Controles Compensatórios Acordados](#12-controles-compensatórios-acordados)
- [13. Prazo de Vigência e Revisão do Aceite](#13-prazo-de-vigência-e-revisão-do-aceite)
- [14. Declaração de Ciência e Aceite](#14-declaração-de-ciência-e-aceite)
- [15. Assinaturas](#15-assinaturas)
- [16. Uso Interno – Registro TechCorp](#16-uso-interno--registro-techcorp)
- [Anexo A – Tabela de Classificação de Risco](#anexo-a--tabela-de-classificação-de-risco)
- [Anexo B – Tabela de Priorização por CVSS](#anexo-b--tabela-de-priorização-por-cvss)
- [Anexo C – Exemplos de Situações que Requerem Aceite Formal](#anexo-c--exemplos-de-situações-que-requerem-aceite-formal)

---

## 1. Finalidade

Este documento tem por finalidade registrar formalmente a ciência, a avaliação e a
decisão do cliente quanto à aceitação de risco identificado pela TechCorp no âmbito
dos serviços de TI gerenciados, transferindo ao cliente a responsabilidade pelas
consequências decorrentes da manutenção da exposição identificada.

O presente Termo integra o processo de gestão de riscos da TechCorp, em
conformidade com as políticas internas e os referenciais normativos aplicáveis.

---

## 2. Base Normativa

Este Termo fundamenta-se em:

- Política de Gestão de Riscos da TechCorp (POL-GRC-001);
- Política de Controle de Acesso da TechCorp (POL-IAM-001);
- Política de Gestão de Vulnerabilidades da TechCorp (POL-VM-001);
- ISO/IEC 27001;
- ISO/IEC 27005;
- NIST Risk Management Framework (NIST RMF);
- CIS Controls;
- SOC 2.

---

## 3. Quando Utilizar

Este Termo deve ser utilizado sempre que:

- o cliente optar por manter uma condição de risco identificada e formalmente
  comunicada pela TechCorp;
- o cliente recusar ou adiar a implementação de controle recomendado;
- o cliente solicitar exceção a requisito previsto nas políticas de segurança;
- a TI interna do cliente realizar alterações que gerem exposição fora da baseline
  aprovada e optar por mantê-las;
- houver desativação de controle de segurança por decisão do cliente;
- vulnerabilidade crítica não for corrigida no prazo recomendado por decisão do
  cliente;
- qualquer outro cenário em que o risco residual seja mantido por escolha do
  cliente.

---

## 4. Instruções de Preenchimento

- Todos os campos obrigatórios devem ser preenchidos antes da coleta de assinaturas.
- O Termo deve ser emitido pela TechCorp e apresentado ao cliente para leitura,
  avaliação e assinatura.
- Após assinado, o documento deve ser registrado no Sistema ITSM com CMDB Integrado
  e arquivado conforme política de retenção.
- O Termo não exonera a TechCorp de reportar reincidências ou agravamentos do risco
  aceito.
- O aceite não é permanente. Deve ser revisado conforme prazo definido na
  Seção 13 ou sempre que houver mudança relevante no contexto do risco.

---

## 5. Identificação do Termo

| Campo                          | Preenchimento                         |
|-------------------------------|---------------------------------------|
| Número do Termo                | [ex.: TAFR-2025-001]                  |
| Data de Emissão                | [dd/mm/aaaa]                          |
| Data de Vencimento do Aceite   | [dd/mm/aaaa]                          |
| Número do Chamado Vinculado    | [ex.: ITSM-00001]                     |
| Classificação do Risco         | [ ] Baixo  [ ] Médio  [ ] Alto  [ ] Crítico |
| CVSS (se aplicável)            | [pontuação / N/A]                     |

---

## 6. Identificação das Partes

### 6.1 TechCorp – Responsável pela Emissão

| Campo                      | Preenchimento   |
|----------------------------|-----------------|
| Razão Social               | TechCorp        |
| Analista Responsável       | [preencher]     |
| Cargo                      | [preencher]     |
| E-mail Corporativo         | [preencher]     |
| Data de Emissão do Termo   | [preencher]     |

### 6.2 Cliente – Responsável pelo Aceite

| Campo                          | Preenchimento   |
|-------------------------------|-----------------|
| Razão Social do Cliente        | [preencher]     |
| Nome do Ponto Focal (PoC)      | [preencher]     |
| Cargo                          | [preencher]     |
| E-mail Corporativo             | [preencher]     |
| Telefone                       | [preencher]     |

---

## 7. Identificação e Descrição do Risco

| Campo                          | Preenchimento   |
|-------------------------------|-----------------|
| ID do Risco                    | [ex.: R-001]    |
| Categoria do Risco             | [preencher]     |
| Ativo ou Processo Afetado      | [preencher]     |
| Sistema / Ambiente             | [preencher]     |

### 7.1 Descrição Técnica do Risco

> Descrever de forma objetiva e clara o risco identificado, incluindo o contexto
> operacional, o evento que pode ocorrer e o ativo exposto.

[preencher]

### 7.2 Causa e Origem

> Descrever a causa raiz identificada, tal como configuração inadequada, controle
> ausente, decisão operacional do cliente, Shadow IT, acesso paralelo, entre outros.

[preencher]

### 7.3 Potencial de Impacto

> Descrever os possíveis impactos ao negócio do cliente em caso de materialização
> do risco, incluindo operacional, financeiro, reputacional e regulatório.

[preencher]

---

## 8. Análise do Risco

| Dimensão                          | Avaliação                                         |
|-----------------------------------|---------------------------------------------------|
| Probabilidade de Ocorrência       | [ ] Rara  [ ] Improvável  [ ] Possível  [ ] Provável  [ ] Quase certa |
| Impacto ao Negócio                | [ ] Insignificante  [ ] Baixo  [ ] Moderado  [ ] Alto  [ ] Crítico |
| Nível de Risco Resultante         | [ ] Baixo  [ ] Médio  [ ] Alto  [ ] Crítico       |
| Pontuação CVSS (se aplicável)     | [preencher / N/A]                                 |
| Severidade CVSS (se aplicável)    | [ ] Baixa  [ ] Média  [ ] Alta  [ ] Crítica  [ ] N/A |
| Controles Existentes              | [descrever controles ativos, se houver]           |
| Risco Inerente                    | [classificação antes dos controles]               |
| Risco Residual Estimado           | [classificação após controles existentes]         |

---

## 9. Recomendação Técnica da TechCorp

### 9.1 Tratamento Recomendado

> Descrever a ação técnica recomendada pela TechCorp para mitigar, eliminar ou
> reduzir o risco identificado.

[preencher]

### 9.2 Prazo Recomendado para Tratamento

| Severidade | Prazo recomendado |
|------------|-------------------|
| Crítico    | Imediato          |
| Alto       | Até 7 dias        |
| Médio      | Até 30 dias       |
| Baixo      | Até 90 dias       |

Prazo aplicável a este caso: [preencher]

### 9.3 Justificativa Técnica

> Descrever por que a TechCorp recomenda o tratamento indicado, com referência ao
> impacto potencial e ao nível de exposição.

[preencher]

---

## 10. Decisão do Cliente

### 10.1 Decisão Formal

O cliente, após leitura e análise do presente Termo, declara a seguinte decisão:

[ ] **Aceitar o risco** – O cliente opta por manter a condição de exposição
identificada, ciente das possíveis consequências e das limitações de
responsabilidade da TechCorp decorrentes dessa decisão.

[ ] **Aceitar temporariamente** – O cliente opta por manter o risco por prazo
determinado, comprometendo-se a tratar a exposição até a data informada na
Seção 13.

[ ] **Tratar o risco** – O cliente concorda em implementar o tratamento
recomendado conforme prazo acordado. Neste caso, o presente Termo é encerrado
e o tratamento será acompanhado por chamado vinculado.

### 10.2 Justificativa do Cliente para o Aceite (quando aplicável)

> Descrever a justificativa apresentada pelo cliente para manter a condição de risco,
> quando a decisão for aceite total ou temporário.

[preencher]

---

## 11. Condições e Limitações de Responsabilidade

Ao assinar este Termo, o cliente reconhece e declara:

- ter sido formalmente informado sobre o risco identificado e sua classificação;
- ter recebido a recomendação técnica da TechCorp;
- ter compreendido os potenciais impactos decorrentes da não implementação do
  tratamento recomendado;
- que a TechCorp não poderá ser responsabilizada por incidentes, perdas,
  interrupções ou danos que tenham como causa direta ou indireta o risco
  formalmente aceito por meio deste Termo;
- que o aceite não exonera o cliente de suas responsabilidades contratuais e
  regulatórias;
- que a TechCorp manterá o monitoramento do ambiente e reportará agravamentos
  ou recorrências identificadas;
- que o aceite não impede a TechCorp de emitir novo Termo caso o risco seja
  agravado ou reidentificado em condição mais crítica.

---

## 12. Controles Compensatórios Acordados

> Descrever eventuais controles alternativos que o cliente e a TechCorp acordam
> implementar ou manter como compensação ao risco aceito. Caso não haja controles
> compensatórios, registrar "Nenhum".

| Controle Compensatório | Responsável | Prazo | Status |
|------------------------|-------------|-------|--------|
| [preencher]            | [preencher] | [preencher] | [preencher] |
| [preencher]            | [preencher] | [preencher] | [preencher] |

---

## 13. Prazo de Vigência e Revisão do Aceite

| Campo                              | Preenchimento   |
|------------------------------------|-----------------|
| Data de Início do Aceite           | [preencher]     |
| Data de Vencimento do Aceite       | [preencher]     |
| Periodicidade de Revisão           | [preencher]     |
| Responsável pela Revisão           | [preencher]     |

O aceite deverá ser revisado:

- na data de vencimento definida;
- em caso de agravamento do risco aceito;
- em caso de incidente relacionado ao risco aceito;
- em caso de mudança relevante no ambiente ou nos controles compensatórios;
- a qualquer momento, mediante solicitação da TechCorp ou do cliente.

---

## 14. Declaração de Ciência e Aceite

Eu, abaixo identificado, na qualidade de representante autorizado do cliente,
declaro que:

- li e compreendi integralmente o presente Termo;
- estou ciente do risco identificado, de sua classificação e do potencial de impacto
  ao negócio;
- recebi e analisei a recomendação técnica emitida pela TechCorp;
- a decisão registrada na Seção 10 foi tomada de forma consciente e voluntária;
- autorizo o registro e o arquivamento deste Termo nos sistemas da TechCorp;
- reconheço os limites de responsabilidade descritos na Seção 11.

---

## 15. Assinaturas

### 15.1 Representante do Cliente

| Campo              | Preenchimento   |
|--------------------|-----------------|
| Nome completo      | [preencher]     |
| Cargo              | [preencher]     |
| E-mail corporativo | [preencher]     |
| Data               | [preencher]     |
| Assinatura         | [preencher]     |

### 15.2 Representante da TechCorp

| Campo              | Preenchimento   |
|--------------------|-----------------|
| Nome completo      | [preencher]     |
| Cargo              | [preencher]     |
| E-mail corporativo | [preencher]     |
| Data               | [preencher]     |
| Assinatura         | [preencher]     |

### 15.3 Testemunha (opcional)

| Campo              | Preenchimento   |
|--------------------|-----------------|
| Nome completo      | [preencher]     |
| Cargo              | [preencher]     |
| Data               | [preencher]     |
| Assinatura         | [preencher]     |

---

## 16. Uso Interno – Registro TechCorp

> Esta seção é de uso exclusivo da TechCorp e não compõe a parte entregue ao cliente
> para assinatura. Deve ser preenchida após coleta das assinaturas.

| Campo                              | Preenchimento   |
|------------------------------------|-----------------|
| Número do Chamado no ITSM          | [preencher]     |
| Data de Registro no Sistema        | [preencher]     |
| Analista Responsável pelo Registro | [preencher]     |
| Localização do Arquivo Digital     | [preencher]     |
| Próximo Lembrete de Revisão        | [preencher]     |
| Observações Internas               | [preencher]     |

---

## Anexo A – Tabela de Classificação de Risco

| Probabilidade / Impacto | Insignificante | Baixo  | Moderado | Alto    | Crítico |
|-------------------------|---------------|--------|----------|---------|---------|
| Quase certa             | Médio         | Alto   | Alto     | Crítico | Crítico |
| Provável                | Médio         | Médio  | Alto     | Alto    | Crítico |
| Possível                | Baixo         | Médio  | Médio    | Alto    | Alto    |
| Improvável              | Baixo         | Baixo  | Médio    | Médio   | Alto    |
| Rara                    | Baixo         | Baixo  | Baixo    | Médio   | Médio   |

**Referência de Decisão:**

| Nível   | Ação Recomendada                                                   |
|---------|--------------------------------------------------------------------|
| Crítico | Tratamento imediato obrigatório. Aceite somente em caráter excepcional e temporário, com aprovação executiva. |
| Alto    | Tratamento prioritário. Aceite possível com prazo definido e controles compensatórios. |
| Médio   | Tratamento planejado. Aceite possível com monitoramento reforçado. |
| Baixo   | Aceite permitido sob monitoramento padrão.                         |

---

## Anexo B – Tabela de Priorização por CVSS

| Faixa CVSS | Severidade | Prazo Recomendado de Tratamento        |
|------------|------------|----------------------------------------|
| 9.0 – 10.0 | Crítica    | Imediato                               |
| 7.0 – 8.9  | Alta       | Até 7 dias                             |
| 4.0 – 6.9  | Média      | Até 30 dias                            |
| 0.1 – 3.9  | Baixa      | Até 90 dias ou aceite justificado      |

---

## Anexo C – Exemplos de Situações que Requerem Aceite Formal

| Situação                                          | Categoria                  | Risco Típico |
|---------------------------------------------------|----------------------------|--------------|
| Desativação ou não instalação da Solução EDR      | Segurança / Endpoint       | Alto         |
| Manutenção de conta de administrador local paralelo | Shadow IT / Governança   | Alto         |
| Recusa de implementação de MFA                    | Identidade e Acesso        | Alto         |
| Vulnerabilidade crítica sem correção no prazo     | Vulnerabilidades           | Crítico      |
| Uso contínuo de computadores compartilhados       | Fator Humano               | Médio / Alto |
| Armazenamento de senhas em navegadores            | Fator Humano               | Médio        |
| Recusa de revisão de acessos privilegiados        | Identidade e Acesso        | Alto         |
| Ferramenta remota não homologada em uso           | Shadow IT / Terceiros      | Alto         |
| Recusa do cliente em corrigir falha de baseline   | Governança                 | Alto         |
| Solicitação de exceção ao processo formal de aprovação | Processo / Governança | Médio / Alto |
