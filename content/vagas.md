---
title: Vagas de Emprego
description: |
  Espaço para a divulgação de vagas para desenvolvedores na região do Vale do Paraíba.
layout: :theme/page
---

# Vagas de Emprego no Vale

Espaço para a divulgação de vagas para desenvolvedores na região do Vale do Paraíba. Para adicionar uma vaga, abra uma [issue](https://github.com/Jug-Vale/Jug-Vale.github.io/issues) criando um arquivo no diretório `content/positions/` no seguinte [modelo](/positions/2024-12-29-modelo). Após o merge, a vaga será listada abaixo:

# Vagas Abertas
---

{#for page in site.pages}
{#if page.data.layout == "positions"}
- [{page.data.title} - {page.data.company}]({page.url})
{/if}
{/for}