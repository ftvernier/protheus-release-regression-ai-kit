# Exemplo - Financeiro

## Contexto

Validação regressiva dos processos financeiros após migração de release do ERP Protheus.

## Cenários sugeridos

| Cenário | Objetivo | Resultado esperado | Criticidade | Evidência |
|--------|----------|--------------------|-------------|-----------|
| Gerar título a receber | Validar integração com faturamento | Título criado corretamente | Alta | Print do título |
| Gerar título a pagar | Validar integração com compras | Título criado corretamente | Alta | Print do título |
| Baixar título | Validar baixa financeira | Baixa realizada sem inconsistência | Alta | Print da baixa |
| Gerar borderô | Validar processo de pagamento/recebimento | Borderô criado corretamente | Média | Print do borderô |
| Validar vencimentos | Conferir cálculo de datas | Vencimentos corretos | Alta | Consulta do título |

## Prompt complementar

Gere cenários adicionais para testar o módulo financeiro do Protheus após migração de release, considerando contas a pagar, contas a receber, baixas, conciliação, integração bancária e contabilização.
