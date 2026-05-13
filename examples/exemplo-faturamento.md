# Exemplo - Faturamento

## Contexto

Validação regressiva do fluxo de faturamento após migração de release do ERP Protheus.

## Cenários sugeridos

| Cenário | Objetivo | Resultado esperado | Criticidade | Evidência |
|--------|----------|--------------------|-------------|-----------|
| Criar pedido de venda | Validar inclusão de pedido | Pedido gravado corretamente | Alta | Print do pedido |
| Liberar crédito e estoque | Validar liberação do pedido | Pedido liberado para faturamento | Alta | Print da liberação |
| Gerar nota fiscal | Validar emissão de NF | NF gerada e autorizada | Alta | DANFE/XML/status TSS |
| Cancelar nota fiscal | Validar cancelamento | NF cancelada corretamente | Alta | Protocolo de cancelamento |
| Gerar contas a receber | Validar integração financeira | Título gerado corretamente | Alta | Print do título |

## Prompt complementar

Gere cenários adicionais para testar faturamento no Protheus após migração de release, considerando pedido de venda, liberação, emissão de NF-e, cancelamento, devolução, geração financeira e integração com TSS.
