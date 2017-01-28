<div class="card row">
    <div class="gallery col-md-6">
        <div class="thumbnails">
            {% for slide in item.slides %}
            <a href="{{ slide.url }}" class="thumbnail-item hidden-sm{% if forloop.index == 1 %} first-item{% endif %}">
                <img src="{{ slide.url }}" alt="" />
            </a>
            {% endfor %}
        </div>
    </div>
    <div class="info col-md-6">
        <h1 class="title">{{ item.title }}</h1>
        <h3 class="platform">for {{ site.data.platforms[item.platform].title }}</h3>
        <p class="short-desc">{{ item.short_desc }}</p>
        <a href="{{ item.marketing_url }}" class="marketing-url btn btn-primary" role="button">Go to Marketing</a>
    </div>
</div>
