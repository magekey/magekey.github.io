---
layout: component
title: Promotion Banner / Magento 2 / Extensions / MageKey GitHub
breadcrumb: Promotion Banner
---
{% assign item = site.data.extensions.m2.promotion_banner %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">{{ page.breadcrumb }}</li>
</ol>

{% include card.md %}

<div class="details">

    <ul class="nav nav-tabs" role="tablist">
        <li role="presentation" class="active"><a href="#overview" aria-controls="overview" role="tab" data-toggle="tab">Overview</a></li>
        <li role="presentation"><a href="#install_guide" aria-controls="install_guide" role="tab" data-toggle="tab">Installation Guide</a></li>
        <li role="presentation"><a href="#user_guide" aria-controls="user_guide" role="tab" data-toggle="tab">User Guide</a></li>
    </ul>

    <div class="tab-content">

        <!-- Overview -->
        <div role="tabpanel" class="tab-pane active" id="overview" aria-expanded="true">
            <div class="pagebreak"></div>

            <p>
            The extension creates banner groups and allows you to place it on any page using Magento widgets.
            Each group can contain several banners.
            The Banner settings allow show up banner at any date or time.
            Promotion Banner Slider extension provides Promotion block settings; it allow to place your notes over banner.
            </p>

            <p>
            When using Promotion Banner, the first step is to create a banner groups. This group will be used to place bundle of your banners on page.
            The next step is to create your banners by selecting group, date and time, by adding image, and by updating promotion block banner settings.
            Once banners are created place your banner groups on any page through the Magento widgets.
            </p>

            <h2>Feature highlights</h2>

            <h3>Manage Groups</h3>

            <p>The extension allows to create banner groups and place this group on any page using Magento widgets.</p>

            <h3>Create a banner</h3>

            <p>The extension allows to create multiple banners and assign them to group.</p>

            <h3>Banner date and time</h3>

            <p>Administrator has control over when each banner is displayed and choose date and time.</p>

            <h3>Banner promotion block</h3>

            <p>Administrator may setup promotion block over banner.</p>

        </div>

        <!-- Installation Guide -->
        <div role="tabpanel" class="tab-pane" id="install_guide">

            <div class="pagebreak"></div>

            {% include install_guide.md %}

        </div>

        <!-- User Guide -->
        <div role="tabpanel" class="tab-pane" id="user_guide">

            <div class="pagebreak"></div>

            <div class="toc-block">
                <h3>Table of contents:</h3>
                <ul class="toc">
                    <li><a href="#getting-around" class="toc-left">Getting Around</a><a href="#getting-around" class="toc-right">3</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="getting-around"></a>
            <p>
            The extension creates banner groups and allows you to place it on any page using Magento widgets.
            Each group can contain several banners.
            The Banner settings allow show up banner at any date or time.
            Promotion Banner Slider extension provides Promotion block settings; it allow to place your notes over banner.
            </p>

            <h2>Getting Around</h2>

            <p>Promotion Banner introduces its sections under <strong>Content > Promotion Banner</strong> menu. The extension comes with 2 sections:</p>
            <ul>
                <li><strong>Manage Groups</strong> - allows administrator to create banner groups</li>
                <li><strong>Manage Banners</strong> - allows administrator to create banners</li>
            </ul>

        </div>
    </div>

</div>
