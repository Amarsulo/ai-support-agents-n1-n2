# AI Support Agents – N1/N2

##  Descrição

Este projeto implementa uma equipe de agentes de Inteligência Artificial para suporte técnico N1 e N2 em ambientes corporativos.

A solução é baseada em:

- BMAD (Business, Models, Agents, Data)
- OpenSpec
- Agentes declarativos em Markdown (.md)

---

##  Objetivo

Automatizar o processo de atendimento de chamados, incluindo:

- Classificação do problema
- Análise técnica (SQL Server e .NET)
- Geração de documentação (KB)
- Criação de GMUD (mudanças controladas)

---

## Arquitetura BMAD

Este projeto segue o modelo BMAD:

- **Business** → Suporte N1/N2 corporativo  
- **Models** → Modelos de linguagem aplicados aos agentes  
- **Agents** → Agentes declarativos (.md)  
- **Data** → Chamados, erros, queries e código  

Essa estrutura permite organizar a solução de forma escalável e orientada a processos de negócio.

---

## Equipe de Agentes

### 01 - Orquestrador  
Responsável por coordenar todo o fluxo de atendimento.

### 02 - Classificador  
Identifica o tipo do problema:
- SQL
- DEV
- USER

### 03 - SQL Agent  
Especialista em banco de dados:
- Analisa queries  
- Detecta problemas de performance  

### 04 - Dev Agent  
Especialista em desenvolvimento:
- C#  
- ASP.NET  
- VB6  

### 05 - KB Agent  
Gera documentação técnica para base de conhecimento.

### 06 - GMUD Agent  
Gera automaticamente documentos de mudança (GMUD).

---

## Colaboração entre os Agentes

Os agentes trabalham de forma colaborativa:

- O Orquestrador coordena o fluxo  
- O Classificador identifica o tipo do problema  
- O agente especialista realiza a análise técnica  
- O KB Agent documenta o conhecimento gerado  
- O GMUD Agent cria a mudança necessária  

Essa abordagem simula uma equipe real de sustentação trabalhando de forma integrada.

---

## Fluxo de Execução

1. Chamado é recebido  
2. Classificador identifica o tipo  
3. Agente especialista analisa:
   - SQL → SQL Agent  
   - Desenvolvimento → Dev Agent  
4. KB Agent gera documentação  
5. GMUD Agent cria solicitação de mudança  

---

## Exemplo de Uso

### Entrada:
Erro ao executar SELECT * FROM pedidos, sistema lento

### Resultado esperado:

- Classificação: SQL  
- Análise do problema (query ineficiente)  
- Sugestão de melhoria (índice / ajuste de query)  
- Geração de KB  
- Geração de GMUD  

---

## Simulação de Execução

### Entrada (Chamado)
Erro ao executar SELECT * FROM pedidos

### Resultado

- Classificado como SQL  
- Identificado uso inadequado de SELECT *  
- Sugestão de otimização  
- KB criada automaticamente  
- GMUD gerada  

---

## Tecnologias e Conceitos

- Agentes de IA declarativos (.md)  
- Cursor IDE / Copilot  
- Prompt Engineering  
- OpenSpec  
- BMAD  

---

## Diferencial

Este projeto simula um ambiente real de sustentação N1/N2, incluindo processos utilizados em empresas como:

- Análise de incidentes  
- Documentação técnica  
- Controle de mudanças (GMUD)  

---

## Conclusão

A utilização de agentes de IA pode reduzir o tempo de atendimento, padronizar processos e melhorar a qualidade da documentação em ambientes corporativos.

---

##  Observação
Este projeto foi desenvolvido utilizando o Cursor IDE para definição de agentes declarativos (.md), conforme apresentado no treinamento.

Este projeto foi desenvolvido utilizando o Cursor IDE para definição de agentes declarativos (.md), conforme apresentado no treinamento.
