---
layout: component
title: Checkout Additional Services / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.extra_services %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Checkout Additional Services</li>
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
            The Checkout Additional Services extension adds additional services step to checkout.
            With the extension, an administrator can manage additional services and configuration.
            </p>

            <p>
            Every additional service consist of title, description, price and editable feature.
            You can setup service price depends of your needs. It could be a fixed cost or percent amount of customer shopping cart.
            Editable feature allows extend your service with input field. You can choose what it will be: text field, textarea or dropdown.
            </p>

        </div>

        <!-- Installation Guide -->

        <div role="tabpanel" class="tab-pane" id="install_guide">

            <div class="pagebreak"></div>

            {% include install_guide_cli.md %}

        </div>

        <!-- User Guide -->
        <div role="tabpanel" class="tab-pane" id="user_guide">

            <div class="pagebreak"></div>

            <div class="toc-block">
                <h3>Table of contents:</h3>
                <ul class="toc">
                    <li><a href="#toc-overview" class="toc-left">Overview</a><a href="#toc-overview" class="toc-right">3</a></li>
                    <li><a href="#manage-services" class="toc-left">Manage Services</a><a href="#manage-services" class="toc-right">4</a></li>
                    <li><a href="#configuration" class="toc-left">Configuration</a><a href="#configuration" class="toc-right">7</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p>
            The Checkout Additional Services extension adds additional services step to checkout.
            With the extension, an administrator can manage additional services and configuration.
            Every additional service consist of title, description, price and editable feature.
            </p>

            <p>The Checkout Additional Services introduces its sections under <strong>Stores > Additional Services</strong> menu. The extension comes with 2 sections:</p>
            <ul>
                <li><strong>Manage Services</strong> - allows administrator to manage services</li>
                <li><strong>Configuration</strong> - allows administrator to setup the extension</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/extraservices/slide10.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="manage-services"></a>
            <h2>Manage Services</h2>

            <p>To create a new service navigate to <strong>Stores > Additional Services > Manage Services</strong> section.</p>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/extraservices/slide12.png" />
            </p>

            <p>To create a new service click <strong>Add Service</strong> button.</p>

            <p>The New Service screen is represented with four settings blocks: Service Details, Conditions, Actions and Editable.</p>

            <h3><i>Service Details</i></h3>

            <ul>
                <li><strong>Service Label</strong> - defines the label of the service.</li>
                <li><strong>Description</strong> - defines the description of the group.</li>
                <li><strong>Sort Order</strong> - defines the sort order of the service.</li>
                <li><strong>Status</strong> - allows to enabled/disabled the service.</li>
            </ul>

            <br/>
            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/extraservices/slide13.png" />
            </p>

            <div class="pagebreak"></div>

            <h3><i>Conditions</i></h3>

            <ul>
                <li><strong>Stores</strong> - allows to assign stores to service item.</li>
                <li><strong>Customer Groups</strong> - allows to assign customer groups to service item.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/extraservices/slide14.png" />
            </p>

            <br/>
            <br/>

            <h3><i>Actions</i></h3>

            <ul>
                <li><strong>Apply Action</strong> - defines the action for service amount.</li>
                <li><strong>Amount</strong> - defines the service amount.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/extraservices/slide15.png" />
            </p>

            <div class="pagebreak"></div>

            <h3><i>Editable</i></h3>

            <ul>
                <li><strong>Editable Enabled</strong> - allows to enabled/disabled the additional input for the service.</li>
                <li><strong>Field Type</strong> - defines field type for additional input of the service.</li>
                <li><strong>Field Placeholder</strong> - defines field placeholder for additional input of the service.</li>
                <li><strong>Drop Down Options</strong> - defines options for Drop Down field type only.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/extraservices/slide16.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <p>The Configuration screen is represented with three setting blocks: General, Checkout Section and Totals.</p>

            <h3><i>General</i></h3>

            <ul>
                <li><strong>Enabled Additional Services</strong> - allows enabled/disabled Checkout Additional Services extension.</li>
            </ul>

            <h3><i>Checkout Section</i></h3>

            <ul>
                <li><strong>Checkout Section Label</strong> - allows to update services checkout step title.</li>
                <li><strong>Display with Virtual products</strong> - allows to use services step in checkout for virtual products.</li>
                <li><strong>Price Format</strong> - allows to change price format for services items in checkout step.</li>
                <li><strong>No Price Format</strong> - allows to update label for free services items.</li>
            </ul>

            <h3><i>Totals</i></h3>

            <ul>
                <li><strong>Total Label</strong> - allows to update services total label.</li>
                <li><strong>Display subtotal</strong> - allows to enabled/disabled subtotal items for services total.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px; max-height: 600px" src="http://cdn.magekey.com/marketplace/extensions/m2/extraservices/slide11.png" />
            </p>
            
        </div>
    </div>

</div>
