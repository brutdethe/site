---
layout: default
---
{%- include aside.md -%}
<article class=blobContent data-title=content>
    <h1>{{ page.nom }}</h1>
    {%- include location-metas.md -%}
    {{ content }}
    {%- include location-tags.md -%}
</article>
