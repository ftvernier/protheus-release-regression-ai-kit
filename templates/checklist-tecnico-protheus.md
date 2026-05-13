# Checklist Técnico Protheus - Migração de Release

## Ambiente

| Campo | Informação |
|------|------------|
| Ambiente | |
| Release atual | |
| Release destino | |
| Sistema operacional | |
| Banco de dados | |
| AppServers envolvidos | |
| DBAccess | |
| TSS | |
| License Server | |

## Validações técnicas

| Item | Componente | Validação | Evidência esperada | Criticidade | Status | Observações |
|------|------------|-----------|--------------------|-------------|--------|-------------|
| 1 | AppServer | Validar subida dos serviços | Serviços online e logs sem erro crítico | Alta | Pendente | |
| 2 | DBAccess | Validar conexão com banco | Conexão estabelecida sem erro | Alta | Pendente | |
| 3 | License Server | Validar consumo de licenças | Licenças disponíveis e sem erro fatal | Alta | Pendente | |
| 4 | TSS | Validar comunicação fiscal | TSS respondendo e transmitindo NF-e | Alta | Pendente | |
| 5 | REST | Validar endpoints críticos | HTTP 200/201 ou retorno esperado | Alta | Pendente | |
| 6 | Jobs | Validar execução de rotinas automáticas | Jobs executados sem erro | Alta | Pendente | |
| 7 | RPO/APO | Validar apontamento correto | appserver.ini apontando para diretórios esperados | Alta | Pendente | |
| 8 | Logs | Monitorar erros críticos | Ausência de erros bloqueantes | Alta | Pendente | |
| 9 | Banco | Validar acesso e performance inicial | Consultas críticas respondendo normalmente | Alta | Pendente | |
| 10 | Usuários | Validar login e permissões | Usuários-chave acessando corretamente | Média | Pendente | |
