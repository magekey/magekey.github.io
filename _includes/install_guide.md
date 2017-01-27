<div class="description">
    <strong>To install the extension follow the instructions below:</strong>
    <ol>
        <li>Backup your web directory and store database.</li>
        <li>Download {{ item.title }} installation package.</li>
        <li>Upload contents of the {{ item.title }} installation package to your store root directory.</li>
        <li>
            <p>In SSH console of your server navigate to your store root folder:</p>
            <code>cd /path/to/store/root/folder</code>
        </li>
        <li>
            <p>Enable {{ item.title }} extension:</p>
            <code>php -f bin/magento module:enable {{ item.code }}</code>
        </li>
        <li>
            <p>Upgrade magento system to apply {{ item.title }} extension:</p>
            <code>php -f bin/magento setup:upgrade</code>
        </li>
        <li>
            <p>Deploy static view files:</p>
            <code>php -f bin/magento setup:static-content:deploy</code>
        </li>
        <li>
            Flush store cache. Log out from the backend and log in again.
        </li>
    </ol>

    <div>{{ item.title }} extension is now installed and ready for work.</div>
</div>
