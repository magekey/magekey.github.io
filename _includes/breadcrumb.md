<ol class="breadcrumb">
{% for bread in breadcrumb %}
    <li><a href="{{ bread.url }}">{{ bread.title }}</a></li>
{% endfor %}
</ol>
