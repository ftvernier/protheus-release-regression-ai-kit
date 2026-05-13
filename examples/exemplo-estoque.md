# Exemplo - Estoque

## Contexto

Validação regressiva de processos de estoque após migração de release do ERP Protheus.

## Cenários sugeridos

| Cenário | Objetivo | Resultado esperado | Criticidade | Evidência |
|--------|----------|--------------------|-------------|-----------|
| Consultar saldo de produto | Validar saldo antes da movimentação | Saldo exibido corretamente | Alta | Print da consulta |
| Movimentar entrada | Validar entrada manual ou por compra | Saldo atualizado | Alta | Documento de entrada |
| Movimentar saída | Validar saída manual ou por venda | Saldo reduzido corretamente | Alta | Documento de saída |
| Validar custo | Garantir cálculo correto de custo | Custo atualizado conforme regra | Média | Consulta de custo |
| Validar reserva de estoque | Garantir reserva por pedido | Reserva criada corretamente | Alta | Print da reserva |

## Prompt complementar

Gere cenários adicionais de testes regressivos para o módulo de estoque do Protheus, considerando saldo, movimentação, reserva, custo, inventário e integração com faturamento e compras.
