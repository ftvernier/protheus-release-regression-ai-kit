# Matriz de Riscos - Migração de Release Protheus

| ID | Tipo de risco | Descrição | Processo impactado | Probabilidade | Impacto | Criticidade | Ação preventiva | Contingência | Responsável | Status |
|----|---------------|-----------|--------------------|---------------|---------|-------------|-----------------|--------------|-------------|--------|
| R001 | Técnico | Falha ao subir AppServer após atualização | Acesso ao ERP | Média | Alto | Alta | Validar atualização em ambiente teste | Executar rollback | TI | Pendente |
| R002 | Fiscal | Falha na emissão de NF-e | Faturamento/Fiscal | Baixa | Alto | Alta | Testar emissão e comunicação com TSS | Acionar rollback ou contingência fiscal | Fiscal/TI | Pendente |
| R003 | Integração | API crítica retornando erro após migração | Integrações | Média | Alto | Alta | Validar endpoints críticos | Acionar time de integração | TI/Integrações | Pendente |
