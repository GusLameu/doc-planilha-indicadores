# Documentação da Planilha de Suporte e Indicadores

Este repositório contém a documentação funcional da planilha de suporte e indicadores, utilizada para registrar, acompanhar e consolidar demandas de suporte técnico, manutenção, instalação, telemetria e medição.

A documentação serve como referência para o desenvolvimento de um aplicativo que integrará a plataforma de chamados online com o sistema de indicadores, automatizando o preenchimento da planilha e o cálculo dos indicadores mensais.

## Arquivos

- **index.html** — Documento completo em HTML com:
  - Estrutura e campos da planilha
  - Regras de status e classificação das demandas
  - Fluxo de integração esperado
  - Cálculo dos indicadores
  - Separação entre DIOPE, unidades vinculadas e gerências regionais
  - Modelo de dados recomendado
  - Lista de regras a validar
  - Requisitos de automação

## Como visualizar a documentação

A documentação está publicada como uma página web acessível em:
**https://GusLameu.github.io/documentacao-planilha-suporte/**

## Para quem é este documento

- Desenvolvedores responsáveis por criar o aplicativo de integração.
- Analistas e gestores que precisam entender o funcionamento da planilha e dos indicadores.
- Qualquer pessoa que precise compreender o fluxo de demandas e o modelo de dados.

## Conteúdo principal

O documento HTML aborda:

1. **Objetivo** — Finalidade da planilha e da automação.
2. **Estrutura geral** — Abas e áreas funcionais.
3. **Cadastro principal** — Campos, descrições e regras de preenchimento.
4. **Status** — ANDAMENTO, PENDENTE, PARALISADA, CONCLUÍDO, CANCELADO.
5. **Fluxo de integração** — Como a plataforma de chamados deve alimentar o sistema.
6. **Indicadores** — Fórmulas de demandas recebidas, concluídas, percentuais e metas.
7. **DIOPE e regionais** — Separação dos grupos de acompanhamento.
8. **Modelo de dados** — Entidades sugeridas (Chamado, Item do chamado, Equipamento, cadastros auxiliares).
9. **Validações necessárias** — Perguntas que devem ser respondidas antes da implementação.
10. **Requisitos de automação** — Funcionalidades essenciais do sistema.

## Dúvidas

Em caso de dúvidas sobre o conteúdo da documentação, entre em contato pelo WhatsApp:

- **Link direto:** https://wa.me/5585981998007  
- **Número:** +55 85 98199-8007

## Atualizações

Para atualizar a documentação:

1. Gere uma nova versão do arquivo HTML.
2. Substitua o arquivo `index.html` neste repositório.
3. Faça um novo commit.
4. O GitHub Pages atualizará automaticamente a página em alguns minutos.

---

**Autor:** Gustavo L. Lameu  
**Contexto:** Integração entre plataforma de chamados e sistema de indicadores de suporte técnico.