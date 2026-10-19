---
title: Matheus
section: home
lang: en

layout: home
---
{%- assign lang = page.lang | default: site.lang | default: 'en' -%}

<h1>
  Hi,<br>
  I'm Matheus!<br>
</h1>
<h1>
  <a class="gsm-link" href="{{ site.menu[lang].portfolio.link | prepend: site.url }}/development">Software Engineering Student</a>
  <span class="gsm-home__and"><!--&&--></span>
  <a class="gsm-link" href="{{ site.menu[lang].portfolio.link | prepend: site.url }}/design"><!--designer--></a>
  <span class="gsm-home__and"><!--&&--></span>
  <a class="gsm-link" href="{{ site.menu[lang].portfolio.link | prepend: site.url }}/illustration"><!--illustrator--></a>
</h1>
