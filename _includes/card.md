<div class="card">
    <div class="gallery col-md-6">
        <div class="thumbnails">
            {% for slide in item.slides %}
            <a href="{{ slide.url }}" class="thumbnail-item{% if forloop.index == 1 %} item{% endif %}">
                <img src="{{ slide.url }}" alt="" />
            </a>
            {% endfor %}
        </div>
    </div>
    <div class="details col-md-6">
        <h1>{{ item.title }}</h1>
        <p>{{ item.short_desc }}</p>
        <a href="{{ item.marketing_url }}" class="btn btn-primary" role="button">Go to Marketing</a>
    </div>
</div>
