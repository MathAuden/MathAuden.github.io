---
title: home
section: home
lang: pt

layout: home
---
{%- assign lang = page.lang | default: site.lang | default: 'en' -%}

<h1>
  Olá,<br>
  aqui é o Matheus!<br>
</h1>
<h1>
  <a class="gsm-link" href="{{ site.menu[lang].portfolio.link | prepend: site.url }}/development">Estudante de Engenharia de Software</a>
 <span class="gsm-home__and"><!--&&--></span>
  <a class="gsm-link" href="{{ site.menu[lang].portfolio.link | prepend: site.url }}/design"><!--Desenvolvedor Junior--></a>
  <span class="gsm-home__and"><!--&&--></span>
  <a class="gsm-link" href="{{ site.menu[lang].portfolio.link | prepend: site.url }}/illustration"><!--Assistente de Business Intelligence--></a>
</h1>