<div class=metas>
    <ul>
        {% if  page.type %}
            <li>Type : {{ page.type }}</li>
        {% endif %}
        {% if  page.par %}
            <li>Par : <a href="https://github.com/{{ page.par }}">{{ page.par }}</a></li> 
        {% endif %}
        {% if page.adresse %}
            <li>Adresse : 
            {% if page.osm %}
                <a href="https://www.openstreetmap.org/node/{{ page.osm }}">
            {% else %}
                <a href="https://www.openstreetmap.org/search?query={{ page.adresse }}, Montréal">
            {% endif %}
                {{ page.adresse }}</a>
                </li>
        {% endif %}
        {% if  page.metro %}
            <li>Métro : {{ page.metro }}</li> 
        {% endif %}
        {% if  page.site %}
            <li>Site : <a href="{{ page.site }}">{{ page.site }}</a></li> 
        {% endif %}
    </ul>
</div>