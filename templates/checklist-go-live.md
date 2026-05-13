[checklist-go-live.md](https://github.com/user-attachments/files/27715275/checklist-go-live.md)
# Checklist de Go-Live - Migração de Release Protheus

## Informações gerais

| Campo | Informação |
|------|------------|
| Empresa | |
| Ambiente | Produção |
| Release atual | |
| Release destino | |
| Data do go-live | |
| Horário de início | |
| Janela estimada | |
| Responsável técnico | |
| Responsável pela decisão de rollback | |
| Canal de comunicação | |

## Antes da migração

| Item | Atividade | Responsável | Criticidade | Evidência | Status | Observações |
|------|-----------|-------------|-------------|-----------|--------|-------------|
| 1 | Confirmar backup do banco de dados | DBA/Infra | Alta | Log ou print do backup | Pendente | |
| 2 | Confirmar backup de RPO/APO/bin/configurações | Técnico Protheus | Alta | Caminho do backup | Pendente | |
| 3 | Comunicar áreas envolvidas | Gestão/TI | Média | Mensagem enviada | Pendente | |
| 4 | Validar plano de rollback | TI/Negócio | Alta | Plano aprovado | Pendente | |
| 5 | Congelar novas alterações | TI | Alta | Confirmação do freeze | Pendente | |

## Durante a migração

| Item | Atividade | Responsável | Criticidade | Evidência | Status | Observações |
|------|-----------|-------------|-------------|-----------|--------|-------------|
| 1 | Parar serviços Protheus | Técnico Protheus | Alta | Status dos serviços | Pendente | |
| 2 | Aplicar atualização de release | Técnico Protheus | Alta | Log da atualização | Pendente | |
| 3 | Validar AppServer/DBAccess/TSS | Técnico Protheus | Alta | Logs sem erro crítico | Pendente | |
| 4 | Subir serviços principais | Técnico Protheus | Alta | Serviços online | Pendente | |

## Após a migração

| Item | Atividade | Responsável | Criticidade | Evidência | Status | Observações |
|------|-----------|-------------|-------------|-----------|--------|-------------|
| 1 | Validar login no Protheus | Usuário-chave/TI | Alta | Print do acesso | Pendente | |
| 2 | Validar emissão de nota fiscal | Fiscal/Faturamento | Alta | NF autorizada | Pendente | |
| 3 | Validar integrações críticas | Tecnologia/Integrações | Alta | Logs ou retorno das APIs | Pendente | |
| 4 | Validar rotinas automáticas | TI | Alta | Execução sem erro | Pendente | |
| 5 | Monitorar logs pós-go-live | TI | Alta | Logs acompanhados | Pendente | |

## Critérios para rollback

- Falha crítica em faturamento.
- Falha crítica em emissão fiscal.
- Indisponibilidade do ERP acima da janela prevista.
- Inconsistência grave em dados.
- Integrações críticas indisponíveis sem contorno.
- Risco operacional não aceito pelo negócio.
