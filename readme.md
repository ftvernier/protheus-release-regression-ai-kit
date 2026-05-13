# Protheus Release Regression AI Kit

Kit open source para apoiar testes regressivos em migrações de release do ERP Protheus utilizando Inteligência Artificial.

## Objetivo

Migrações de release no ERP Protheus exigem cuidado técnico, funcional e operacional.

O objetivo deste projeto é ajudar analistas, desenvolvedores, tech leads, arquitetos e times de sustentação a estruturar melhor os testes regressivos, a homologação e a documentação de evidências durante uma migração de release.

A proposta não é substituir o conhecimento técnico ou funcional dos especialistas.

A proposta é usar IA como apoio para organizar cenários, riscos, checklists, evidências e decisões.

## Problema

Em muitos ambientes ERP, os testes regressivos ainda dependem de:

- planilhas soltas;
- conhecimento tribal;
- anotações manuais;
- baixa rastreabilidade;
- ausência de histórico reutilizável;
- pouca visibilidade executiva sobre riscos e pendências.

Em uma migração de release, isso pode gerar riscos para processos críticos como:

- faturamento;
- compras;
- estoque;
- financeiro;
- fiscal;
- contabilidade;
- integrações;
- customizações;
- rotinas automáticas;
- APIs;
- jobs;
- emissão de documentos fiscais;
- comunicação com TSS;
- execução de processos críticos do negócio.

## Como a IA pode ajudar

A IA pode apoiar em atividades como:

- geração de cenários de teste por módulo;
- classificação de criticidade;
- criação de checklist de homologação;
- identificação de riscos operacionais;
- organização de evidências;
- geração de resumo executivo;
- preparação de plano de rollback;
- documentação de validações funcionais e técnicas.

## Estrutura do projeto

```text
prompts/
  Prompts prontos para uso com ferramentas de IA.

templates/
  Modelos de documentos para homologação, testes e validação.

examples/
  Exemplos práticos aplicados a módulos do ERP Protheus.
```

## Como usar

1. Escolha um prompt na pasta `prompts`.
2. Copie o conteúdo.
3. Ajuste as informações conforme o seu ambiente.
4. Execute em uma ferramenta de IA como ChatGPT, Claude, Gemini ou outra IA.
5. Revise tecnicamente o resultado.
6. Use os templates para documentar a homologação.
7. Salve evidências, pendências e decisões tomadas durante o processo.

## Fluxo sugerido para uma migração de release

1. Levantar módulos, integrações, customizações e processos críticos.
2. Usar o prompt de matriz regressiva para gerar uma primeira versão dos cenários.
3. Revisar os cenários com especialistas técnicos e usuários-chave.
4. Classificar riscos por criticidade.
5. Executar homologação em ambiente de testes.
6. Registrar evidências.
7. Consolidar pendências e riscos residuais.
8. Preparar checklist de go-live.
9. Validar plano de rollback.
10. Gerar resumo executivo para liderança e áreas envolvidas.

## Importante

Este projeto não substitui testes reais, validação funcional, análise técnica ou homologação com usuários-chave.

A IA deve ser utilizada como apoio para organização, produtividade e redução de lacunas.

A responsabilidade final pela migração continua sendo do time técnico, funcional e de negócio.

## Casos de uso

- Migração de release Protheus.
- Atualização de ambiente.
- Homologação de customizações.
- Validação de integrações.
- Organização de plano de testes.
- Preparação de go-live.
- Documentação executiva para diretoria.
- Criação de histórico reutilizável para futuras migrações.

## Boas práticas

- Nunca utilize informações sensíveis da empresa em ferramentas públicas de IA.
- Anonimize nomes de clientes, fornecedores, usuários, valores e dados fiscais.
- Revise todos os resultados gerados pela IA.
- Priorize processos críticos antes de processos administrativos.
- Mantenha evidências organizadas.
- Envolva usuários-chave no processo de homologação.
- Não realize go-live sem plano de rollback validado.

## Contribuições

Contribuições são bem-vindas.

Você pode contribuir com:

- novos prompts;
- exemplos por módulo;
- templates de homologação;
- checklists técnicos;
- boas práticas de migração;
- casos reais anonimizados.

## Licença

Este projeto está disponível sob a licença MIT.
