<div class="card">
    <div class="gallery col-md-8">
        <div class="wrapper row">
            <div class="preview">
                <div class="preview-pic tab-content">
                    {% for slide in item.slides %}
                    <div class="tab-pane{% if forloop.index == 1 %} active{% endif %}" id="pic-{{ forloop.index }}">
                        <img src="{{ slide.url }}" alt="{{ item.title }}" />
                    </div>
                    {% endfor %}
                </div>
                <ul class="preview-thumbnail nav nav-tabs">
                    {% for slide in item.slides %}
                    <li class="{% if forloop.index == 1 %}active{% endif %}">
                        <a data-target="#pic-{{ forloop.index }}" data-toggle="tab">
                            <img src="{{ slide.url }}" alt="{{ item.title }}" />
                        </a>
                    </li>
                    {% endfor %}
                </ul>
            </div>
        </div>
    </div>
    <div class="details col-md-4">
        <h1>{{ item.title }}</h1>
        <p>{{ item.short_desc }}</p>
    </div>
</div>
