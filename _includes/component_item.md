<div class="col-sm-6 col-md-4 list-item">
    <div class="thumbnail">
        <img src="{{ item.thumbnail }}" alt="{{ item.title }}">
        <div class="caption">
            <h3 class="title">{{ item.title }}</h3>
            <p class="short-desc">{{ item.short_desc }}</p>
            <p class="text-center marketing">
                <a href="{{ item.url }}" class="btn btn-primary marketing-url" role="button">{{ item.title }}</a>
            </p>
        </div>
    </div>
</div>
