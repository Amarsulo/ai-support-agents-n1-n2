# Funcionalidade: Atendimento de Suporte N1/N2

## Cenário: Identificação de problema SQL

Dado que recebo um chamado com erro de query SQL
Quando analiso o chamado
Então devo classificar como SQL
E acionar o SQL Agent

---

## Cenário: Identificação de problema de código

Dado que recebo um erro em sistema .NET
Quando analiso o chamado
Então devo classificar como DEV
E acionar o Dev Agent

---

## Cenário: Geração de documentação

Dado que um problema foi resolvido
Quando finalizo a análise
Então devo gerar:
- KB
- GMUD
