# Exemplo - Fiscal

## Contexto

Validação regressiva dos processos fiscais após migração de release do ERP Protheus.

## Cenários sugeridos

| Cenário | Objetivo | Resultado esperado | Criticidade | Evidência |
|--------|----------|--------------------|-------------|-----------|
| Emitir NF-e | Validar autorização fiscal | NF-e autorizada | Alta | DANFE/XML/protocolo |
| Cancelar NF-e | Validar cancelamento fiscal | NF-e cancelada na SEFAZ | Alta | Protocolo de cancelamento |
| Validar comunicação com TSS | Garantir comunicação fiscal | TSS respondendo corretamente | Alta | Log/status |
| Gerar livros fiscais | Validar apuração/obrigações | Relatórios gerados corretamente | Alta | Relatório fiscal |
| Validar impostos | Conferir cálculo tributário | Impostos calculados corretamente | Alta | Print da nota/impostos |

## Prompt complementar

Gere cenários adicionais para testar processos fiscais no Protheus após migração de release, considerando emissão de NF-e, cancelamento, inutilização, TSS, impostos, livros fiscais e obrigações acessórias.
