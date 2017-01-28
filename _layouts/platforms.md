<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>{{ page.title }}</title>

    <!-- BEGIN CSS -->
    {% include style_default.md %}
    {% include style_custom.md %}
    <!-- END CSS -->
</head>
<body>

    {% include header.md %}

    <div class="container">

    <ol class="breadcrumb">
        <li><a href="/">Home</a></li>
        <li class="active">{{ page.breadcrumb }}</li>
    </ol>

    <div class="row platforms">
        {% for platform in site.data.platforms %}
        {% assign code = platform[0] %}
        {% assign item = platform[1] %}

        <div class="col-sm-6 col-md-4 list-item">
            <a class="thumbnail" href="/{{ page.component }}/{{ code }}">
                <img src="{{ item.thumbnail }}" alt="{{ item.title }}">
                <div class="caption">
                    <h3 class="title text-center">{{ item.title }}</h3>
                </div>
            </a>
        </div>

        {% endfor %}
    </div>

    </div>

    <!-- BEGIN SCRIPT -->
    {% include script_default.md %}
    {% include script_custom.md %}
    <!-- END SCRIPT-->
</body>
</html>
