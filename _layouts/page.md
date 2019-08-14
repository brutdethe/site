---
layout: default
---
{% if page.name == 'README.md' %}
    {%- include summary.html -%}
{% else %}
    {%- include content.html -%}
{% endif %}
