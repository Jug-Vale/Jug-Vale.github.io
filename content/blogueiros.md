---
title: Blogueiros do JUG Vale
description: |
  Nessa página agregamos blogs dos “Javeiros” da nossa região.
layout: :theme/page
---

# Blogueiros JUG Vale

Nessa página agregamos blogs dos “Javeiros” da nossa região. Caso queria ver sua página/blog aqui, nos envie um Pull Request [abrindo uma Issue](https://github.com/Jug-Vale/Jug-Vale.github.io/issues) adicionando seu blog/site/vlog no arquivo `yml` em: `data/creators.yml`.

{#for creator in cdi:creators.creators}

### {creator.name}
---
__Blogs__

{#for blog in creator.blogs}
- [{blog.name}]({blog.url})
{/for}

__Youtube__

{#for yt in creator.youtube}
- [{yt.name}]({yt.url})
{/for}

__Facebook__

{#for fb in creator.facebook}
- [{fb.name}]({fb.url})
{/for}

__Instagram__

{#for insta in creator.instagram}
- [{insta.name}]({insta.url})
{/for}

{/for}