<nav class="navbar navbar-default navbar-fixed-top">
    <div class="container">
        <div class="navbar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
            <a class="navbar-brand" href="/"><img title="MageKey GitHub" src="/img/logo.svg" /><span>MageKey</span> <span class="github">GitHub</span></a>
        </div>
        <div id="navbar" class="navbar-collapse collapse">
            <ul class="nav navbar-nav">
                {% for item in site.data.menu %}
                <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                {% endfor %}
            </ul>
            <ul class="nav navbar-nav navbar-right">
                <li><a href="mailto:support@magekey.com">support@magekey.com</a></li>
            </ul>
        </div>
    </div>
</nav>
