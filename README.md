# AI Support Agents – N1/N2

##  Descrição

Este projeto implementa uma equipe de agentes de Inteligência Artificial para suporte técnico N1 e N2 em ambientes corporativos.

A solução é baseada em:
- BMAD (Business, Models, Agents, Data)
- OpenSpec
- Agentes declarativos em Markdown (.md)

---

## Objetivo

Automatizar o processo de atendimento de chamados, incluindo:

- Classificação do problema
- Análise técnica (SQL Server e .NET)
- Geração de documentação (KB)
- Criação de GMUD (mudanças controladas)

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

## Fluxo de Execução

1. Chamado é recebido
2. Classificador identifica o tipo
3. Agente especialista analisa:
   - SQL → SQL Agent
   - Desenvolvimento → Dev Agent
4. KB Agent gera documentação
5. GMUD Agent cria solicitação de mudança

---

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

## Tecnologias e Conceitos

- Agentes de IA declarativos (.md)
- Cursor IDE / Copilot
- Prompt Engineering
- OpenSpec
- BMAD

---

## Diferencial

Este projeto simula um ambiente real de sustentação N1/N2, incluindo processos utilizados em empresas como:

- análise de incidentes
- documentação técnica
- controle de mudanças (GMUD)

---

## Conclusão

A utilização de agentes de IA pode reduzir o tempo de atendimento, padronizar processos e melhorar a qualidade da documentação em ambientes corporativos.



### Entra
