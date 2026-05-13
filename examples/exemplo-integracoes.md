# Exemplo - Integrações

## Contexto

Validação regressiva de integrações críticas após migração de release do ERP Protheus.

## Cenários sugeridos

| Cenário | Objetivo | Resultado esperado | Criticidade | Evidência |
|--------|----------|--------------------|-------------|-----------|
| Validar API de pedido | Garantir recebimento de pedidos externos | Pedido integrado corretamente | Alta | Payload/log/status |
| Validar API de estoque | Garantir consulta ou atualização de estoque | Retorno correto | Alta | Log/API response |
| Validar integração fiscal | Garantir comunicação com sistemas fiscais | Comunicação sem erro | Alta | Log/status |
| Validar jobs automáticos | Garantir execução de rotinas agendadas | Job executado com sucesso | Alta | Log da rotina |
| Validar fila/mensageria | Garantir processamento de eventos | Eventos processados corretamente | Alta | Log/fila vazia |

## Prompt complementar

Gere cenários adicionais para testar integrações do Protheus após migração de release, considerando APIs REST, jobs, filas, integrações fiscais, integrações financeiras e sistemas satélites.
