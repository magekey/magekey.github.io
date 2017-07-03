<div class="card row">
    <div class="gallery col-md-6">
        <div class="thumbnails">
            {% for slide in item.slides %}
            <a href="{{ slide.url }}" class="thumbnail-item hidden-sm{% if forloop.index == 1 %} first-item{% endif %}">
                <img src="{{ slide.url }}" alt="" />
            </a>
            {% endfor %}
        </div>
        <div class="print-thumbnail">
            <img src="{{ item.thumbnail }}" alt="" />
        </div>
    </div>
    <div class="info col-md-6">
        <h1 class="title">{{ item.title }}</h1>
        <h3 class="platform">for {{ site.data.platforms[item.platform].title }}</h3>
        <p class="short-desc">{{ item.short_desc }}</p>
        {% if item.marketing_url %}
        <a href="{{ item.marketing_url }}" class="marketing-url btn btn-primary" role="button" target="_blank">Go to Marketplace</a>
        {% else %}
        <a href="mailto:support@magekey.com" class="marketing-url btn btn-primary">Contact Developer</a>
        {% endif %}
    </div>
</div>
