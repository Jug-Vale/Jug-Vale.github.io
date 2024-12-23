---
title: Sobre
description: |
  Notícias, anúncios, resumo dos encontros e outras coisas relacionadas ao JUG Vale;
layout: :theme/page
---

# Sobre JUG Vale

Fortalecer o TI na nossa região é de extrema importância, pois possibilita a geração de mais inovação, negócios e mão de obra qualificada. Favorecendo principalmente as empresas deste ramo aqui na região, pois profissionais e empreendedores não precisam se deslocar para outras cidades.

A ideia do nosso grupo é colocar junto profissionais, estudantes e empresas da área e difundir o conhecimento desse vasto e dinâmico mundo que é o de TI. Além disto, temos o profundo objetivo de senso social, não cobramos nada dos participantes, e sempre pedimos 1kg de alimento em favor de alguma entidade beneficente em nossos encontros

Queremos organizar os nossos eventos e grupo de forma que todos participem, sem pagar diretamente nenhum centavo. Para isso, precisamos da ajuda de todos, seja nos ajudando em nossos códigos no [github](https://github.com/Jug-Vale), temos diversos projetos em nosso github e você pode nos enviar [pull request (#PR)](https://help.github.com/articles/using-pull-requests), participando das discussões no [grupo do WhatsApp](https://chat.whatsapp.com/1wMGdAitGeeD6eQlEnnzLN) e até palestrando em dias de evento e os divulgando em suas redes sociais.

Qualquer dúvida ou sugestão, nos envie um e-mail: jugvale@gmail.com.

Veja todas nossas redes em [linktr.ee/jugvale](https://linktr.ee/jugvale)

## Authors

<div class="authors">
  <!-- authors.yml is in the data/ -->
  {#for id in cdi:authors.fields}
    {#let author=cdi:authors.get(id)}
    <!-- the author-card tag is defined in the default Roq theme -->
    {#author-card name=author.name avatar=author.avatar nickname=author.nickname profile=author.profile /}
  {/for}
</div>

