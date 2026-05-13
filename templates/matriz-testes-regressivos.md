# Matriz de Testes Regressivos - Migração de Release Protheus

## Informações gerais

| Campo | Informação |
|------|------------|
| Empresa | |
| Ambiente | |
| Release atual | |
| Release destino | |
| Banco de dados | |
| Sistema operacional | |
| Data prevista do go-live | |
| Janela de migração | |
| Responsável técnico | |
| Responsável funcional | |

## Matriz de testes

| Módulo | Processo | Cenário | Objetivo | Pré-condições | Passos | Resultado esperado | Evidência | Criticidade | Responsável | Status | Observações |
|--------|----------|---------|----------|---------------|--------|--------------------|-----------|-------------|-------------|--------|-------------|
| Faturamento | Pedido de venda | Gerar pedido e faturar NF | Validar fluxo completo de venda | Cliente, produto e condição de pagamento cadastrados | Criar pedido, liberar crédito/estoque, gerar NF | NF autorizada e pedido faturado corretamente | Print da NF, pedido e status no TSS | Alta | Área fiscal/CD | Pendente | |
| Estoque | Movimentação de estoque | Validar baixa de estoque no faturamento | Garantir atualização correta do saldo | Produto com saldo disponível | Faturar pedido e consultar saldo | Saldo atualizado corretamente | Print de consulta de saldo | Alta | Estoque | Pendente | |
| Financeiro | Título a receber | Validar geração do contas a receber | Garantir geração correta do título | Pedido faturado | Consultar contas a receber após emissão da NF | Título gerado com valor e vencimento corretos | Print do título | Alta | Financeiro | Pendente | |

## Status sugeridos

- Pendente
- Em execução
- Aprovado
- Aprovado com ressalva
- Reprovado
- Bloqueado

## Observações finais

Registre aqui os principais pontos de atenção, pendências e riscos encontrados durante a homologação.
