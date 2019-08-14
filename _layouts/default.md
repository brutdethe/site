<!doctype html>
<html lang="{{ page.lang | default: site.lang | default: "fr" }}">
    {%- include head.md -%}
    <body>
        {%- include header.md -%}
        <main class="container">
            {{ content }}
        </main>
    </body>
</html>
