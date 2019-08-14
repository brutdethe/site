---
layout: default
---
{% if page.name == 'README.md' %}
    {%- include summary.md -%}
{% else %}
    {%- include content.md -%}
{% endif %}
