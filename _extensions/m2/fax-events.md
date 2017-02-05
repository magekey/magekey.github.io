---
layout: component
title: Fax Events / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.fax_events %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Fax Events</li>
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
            Fax Events is an extension for faxing messages. It uses Interfax services provider to create text documents and transmit them to your fax machine.
            To send a fax message to a given fax number, the extension uses standard Magento email templates.
            The text of your fax document will be identical to your email template text.
            </p>

            <p>
            Fax Events extension has got 3 trigger events for sending a fax message:
            </p>

            <ul>
                <li>faxing a message when a standard Magento Contact form is completed</li>
                <li>faxing a message when a new customer is registered in your shop</li>
                <li>faxing a message when a new order is created.</li>
            </ul>

            <p>
            The first step in using Fax Events is setting up an Interfax service provider by registering at <a href="http://www.interfax.net" target="_blank">www.interfax.net</a>.
            The email and password obtained during registration will be used for authorization at the service provider website when sending a fax message.
            An administrator will enter your email and password into the extension settings in the backend panel of your website.
            You will also need to specify the fax number all the messages shall be sent to.
            </p>

            <p>
            The administrator may enable or disable sending faxes in response to certain events.
            For example, you may opt to use the extension to get fax messages only when new orders are created in your shop.
            </p>

            <h2>Feature highlights</h2>

            <ul>
                <li>using Interfax service provider for sending fax messages</li>
                <li>using standard email templates to create a fax document</li>
                <li>faxing a message when a standard Contact form is completed</li>
                <li>faxing a message when a new customer is registered</li>
                <li>faxing a message when a new order is created.</li>
            </ul>

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
                    <li><a href="#configuration" class="toc-left">Configuration</a><a href="#configuration" class="toc-right">4</a></li>
                    <li><a href="#how-to-use" class="toc-left">How to use Events</a><a href="#how-to-use" class="toc-right">7</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p style="margin-bottom: 5px;">
            Fax Events is an extension for faxing messages. It uses Interfax services provider to create text documents and transmit them to your fax machine.
            To send a fax message to a given fax number, the extension uses standard Magento email templates.
            The text of your fax document will be identical to your email template text.
            </p>

            <p style="margin-bottom: 5px;">Fax Events extension has got 3 trigger events for sending a fax message:</p>

            <ul>
                <li>faxing a message when a standard Magento Contact form is completed</li>
                <li>faxing a message when a new customer is registered in your shop</li>
                <li>faxing a message when a new order is created.</li>
            </ul>


            <p style="margin-top: 10px;">Fax Events introduces a configuration section under <strong>Marketing > Fax Events</strong> menu. The extension comes with 1 section: <b>Configuration</b></p>

            <p class="text-center">
                <img style="width: 400px" src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/slide1.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <br/>
            <p>To set up the Fax Events extension navigate to <strong>Marketing > Fax Events > Configuration</strong> section.</p>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/slide2.png" />
            </p>

            <p>The Configuration screen is represented with four settings blocks: General Settings, Provider, Events, Logging.</p>

            <h3><i>General Settings</i></h3>

            <ul>
                <li><strong>Enable Module</strong> - allows enabling/disabling Fax Events extension.</li>
            </ul>

            <br/>
            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/us-config-general.png" />
            </p>

            <div class="pagebreak"></div>

            <h3><i>Provider</i></h3>

            <p>Fax Events uses Interfax services provider to create text documents and transmit them to your fax machine.</p>

            <ul>
                <li><strong>Provider</strong> - allows to choose fax provider. Available only Interfax option.</li>
                <li><strong>Interfax Endpoint</strong> - defines Interfax endpoint service url.</li>
                <li><strong>Interfax Username</strong> - defines Interfax username.</li>
                <li><strong>Interfax Password</strong> - defines Interfax password.</li>
                <li><strong>Fax Number</strong> - defines fax number.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/slide3.png" />
            </p>

            <div class="pagebreak"></div>
            <h3><i>Events</i></h3>

            <p>
            Fax Events extension has got 3 trigger events for sending a fax message:
            </p>

            <ul>
                <li><b>Contact > Contact Form</b> - faxing a message when a standard Magento Contact form is completed</li>
                <li><b>Customer > New Account</b> - faxing a message when a new customer is registered in your shop</li>
                <li><b>Sales > New Order</b> - faxing a message when a new order is created.</li>
            </ul>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/slide4.png" />
            </p>

            <h3><i>Logging</i></h3>

            <ul>
                <li><strong>Enable</strong> - allows enabling/disabling fax logging.</li>
            </ul>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/slide5.png" />
            </p>

            <div class="pagebreak"></div>
            <a name="how-to-use"></a>
            <h2>How to use Events</h2>

            <p>This section describe how to faxing your messages to your fax machine.</p>

            <h3><b><i>Contact</i></b> > <b><i>Contact Form</i></b></h3>

            <p>Navigate to Magento contact form. By default Magento contact form located under <i>www.yoursite.url/contact</i></p>

            <p>Fill the form and click <b>Submit</b> button</p>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/ug-contact-form.png" />
            </p>

            <div class="pagebreak"></div>

            <h3><b><i>Customer</i></b> > <b><i>New Account</i></b></h3>

            <p>Navigate to Create Account section. By default this page located under <i>www.yoursite.url/customer/account/create</i></p>

            <p>Fill the form and click <b>Create an Account</b> button</p>

            <p class="text-center">
                <img style="width: 450px;" src="http://cdn.magekey.com/marketplace/extensions/m2/fax-events/ug-customer-new-account.png" />
            </p>

            <p>&nbsp;</p>

            <h3><b><i>Sales</i></b> > <b><i>New Order</i></b></h3>

            <p>This event triggered when your customer place new order in your store.</p>

        </div>
    </div>

</div>
