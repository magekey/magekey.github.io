---
layout: component
title: Customer Sidebar / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.customer_sidebar %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Customer Sidebar</li>
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
            Customer Sidebar is an extension intended for shop owners that will help you improve customer  navigation menu.
            The extension replaces a standard customer navigation menu with a new improved Customer Sidebar.
            Customer Sidebar it’s a left sidebar that contains the logo block on the top, main menu block implemented with icons and submenu block. 
            Customer Sidebar extension allows administrator to manage links and icons. You can simple add new custom link or default magento link.
            </p>

            <p>
            With the Customer Sidebar extension, an administrator can customize your customer navigation menu design.
            For this purpose, a convenient design tool is implemented, which allows detailed customization of your navigation styles.
            Using this tool, you can change the background for main menu and sub menu, add offsets and border.
            You can customize font and size of the menu links, using both your browser standard fonts, and Google fonts, and to make different settings for hover links and active links states.
            You can also customize sidebar logo block, choose new logo and specify the background.
            </p>

            <p>
            The Customer Sidebar extension is fully responsive.
            </p>

            <h2>Features:</h2>

            <ul>
                <li>replaces a standard customer navigation menu with a new improved Customer Sidebar.</li>
                <li>manage your links in Magento backend.</li>
                <li>consists of the logo, main menu and submenu blocks.</li>
                <li>with design tool an administrator can customize your menu design.</li>
                <li>fully responsive.</li>
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
                    <li><a href="#navigation" class="toc-left">Navigation</a><a href="#navigation" class="toc-right">4</a></li>
                    <li><a href="#configuration" class="toc-left">Configuration</a><a href="#configuration" class="toc-right">6</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p style="margin-bottom: 5px;">
            Customer Sidebar is an extension intended for shop owners that will help you improve customer  navigation menu.
            The extension replaces a standard customer navigation menu with a new improved Customer Sidebar.
            Customer Sidebar it’s a left sidebar that contains the logo block on the top, main menu block implemented with icons and submenu block. 
            Customer Sidebar extension allows administrator to manage links and icons. You can simple add new custom link or default magento link.
            </p>

            <br/>
            
            <p>Customer Sidebar introduces its sections under <strong>Content > Customer Sidebar</strong> menu. The extension comes with 2 sections:</p>
            <ul>
                <li><strong>Navigation</strong> - allows administrator to manage navigation links</li>
                <li><strong>Configuration</strong> - allows administrator to customize Customer Sidebar</li>
            </ul>
            
            <br/>
            
            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide1.png" />
            </p>
            
            <div class="pagebreak"></div>
            
            <a name="navigation"></a>
            <h2>Navigation</h2>
            
            <br/>
            
            <p>To manage Customer Sidebar links navigate to <strong>Content > Customer Sidebar > Navigation</strong> section.</p>

            <br/>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide9.png" />
            </p>
            
            <p>To create a Link click <strong>Add Item</strong> button.</p>

            <p>The New Item screen is represented with two settings blocks: Item Details and Icon.</p>
            
            <h3><i>Item Details</i></h3>
            
            <br/>
            
            <p>This screen allows to store general sidebar item details. The following settings are available:</p>
            
            <ul>
                <li><strong>Title</strong> - defines the name of the sidebar item.</li>
                <li><strong>Parent Item</strong> - defines the parent item of the sidebar item.</li>
                <li><strong>Link</strong> - defines the sidebar item url.</li>
                <li><strong>Sort Order</strong> - defines the sidebar item order.</li>
                <li><strong>Visible</strong> - enable/disable sidebar item.</li>
            </ul>
            
            <br>
            
            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide10.png" />
            </p>
            
            <div class="pagebreak"></div>
            
            <h3><i>Icon</i></h3>
            
            <br/>
            
            <p>This screen allows to setup sidebar icon. This setting available only for main items without "parents".</p>
            <p>The following settings are available:</p>
            
            <ul>
                <li><strong>Font-Awesome Icon</strong> - defines the sidebar icon.</li>
            </ul>
            
            <br/>
            
            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide11.png" />
            </p>
            
            <div class="pagebreak"></div>
            
            <a name="navigation"></a>
            <h2>Configuration</h2>
            
            <br/>
            
            <p>To set up the Customer Sidebar extension navigate to <strong>Content > Customer Sidebar > Configuration</strong> section.</p>
            
            <p>The Configuration screen is represented with four settings blocks: Sidebar Navigation, Logo Block, Sub Menu and Links.</p>
            
            <br/>
            
            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide2.png" />
            </p>
            
            <h3><i>Sidebar Navigation</i></h3>
            
            <ul>
                <li><strong>Enable Customer Sidebar</strong> - enable/disable Customer Sidebar extension.</li>
                <li><strong>Design</strong> - allows to customize main sidebar container.</li>
            </ul>
            
            <p class="text-center">
                <img style="width:800px" src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide3.png" />
            </p>
            
            <h3><i>Logo Block</i></h3>

            <ul>
                <li><strong>Display Sidebar Logo</strong> - enable/disable Customer Sidebar logo block.</li>
                <li><strong>Use Custom Logo</strong> - allows to use custom image for logo block.</li>
                <li><strong>Custom Logo Image</strong> - allows to upload custom image for logo block.</li>
                <li><strong>Design</strong> - allows to customize logo block.</li>
            </ul>
            
            <p class="text-center">
                <img style="width:900px" src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide4.png" />
            </p>
            
            <div class="pagebreak"></div>
            
            <h3><i>Sub Menu</i></h3>

            <ul>
                <li><strong>Sub Menu Container</strong> - allows to customize sidebar sub menu container.</li>
                <li><strong>Title</strong> - allows to customize sidebar title.</li>
            </ul>
            
            <p class="text-center">
                <img style="width:900px" src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide5.png" />
            </p>
            
            <h3><i>Links</i></h3>

            <ul>
                <li><strong>Navigation Links</strong> - allows to customize main navigation links.
                    <ul>
                        <li><strong><i>Default State</i></strong> - allows to customize links for default state.</li>
                        <li><strong><i>Hover State</i></strong> - allows to customize links for hover state.</li>
                        <li><strong><i>Active State</i></strong> - allows to customize links for active state.</li>
                    </ul>
                </li>
                <li><strong>Sub Links (Level 1)</strong> - allows to customize sidebar links (Level 1).
                    <ul>
                        <li><strong><i>Default State</i></strong> - allows to customize links for default state.</li>
                        <li><strong><i>Hover State</i></strong> - allows to customize links for hover state.</li>
                        <li><strong><i>Active State</i></strong> - allows to customize links for active state.</li>
                    </ul>
                </li>
                <li><strong>Sub Links (Level 2)</strong> - allows to customize sidebar links (Level 2).
                    <ul>
                        <li><strong><i>Default State</i></strong> - allows to customize links for default state.</li>
                        <li><strong><i>Hover State</i></strong> - allows to customize links for hover state.</li>
                        <li><strong><i>Active State</i></strong> - allows to customize links for active state.</li>
                    </ul>
                </li>
            </ul>
            
            <p class="text-center">
                <img style="width:900px" src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide6.png" />
            </p>
            
            <p class="text-center">
                <img style="width:900px" src="http://cdn.magekey.com/marketplace/extensions/m2/customer-sidebar/slide7.png" />
            </p>
        </div>
    </div>

</div>
