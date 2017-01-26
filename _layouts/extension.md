<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>{{ page.title }}</title>

    <!-- BEGIN CSS -->
    {% include style_default.md %}
    <link rel="stylesheet" href="/lib/lightgallery/css/lightgallery.min.css" />
    {% include style_custom.md %}
    <!-- END CSS -->
</head>
<body>

    {% include header.md %}

    <div class="container">

    <ol class="breadcrumb">
        <li><a href="/">Home</a></li>
        <li><a href="/extensions">Extensions</a></li>
        <li class="active">{{ page.breadcrumb }}</li>
    </ol>

    {{ content }}
    </div>

    <!-- BEGIN SCRIPT -->
    {% include script_default.md %}
    <script src="/lib/lightgallery/js/lightgallery.min.js"></script>
    <script src="/js/extension.js"></script>
    {% include script_custom.md %}
    <!-- END SCRIPT-->
</body>
</html>
