{% if page.tags %}
    <div class=tags>
        <ul>
            {% for tag in page.tags %}
            <li>{{ tag }}</li>
            {% endfor %}
        </ul>
    </div>
{% endif %}