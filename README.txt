YourPocketApps homepage — Version 2.0.0.4

Unzip and use index.html as your homepage. All page styles, fonts and app
illustrations are bundled in the file.

At the very top of index.html, below the charset, edit the WEBSITE CONFIGURATION
block (window.POCKET_APPS_LINKS). You do not need to edit the large bundled code.

homepage: Enter your full homepage address, including https://.
apps.home: Controls the logo link, mobile menu Home link and footer home link.
           "#top" returns to the top of this page, without visiting the root.
           Set a path such as "/home-page/" or a full URL to open another page.
           This is independent of homepage (the base/metadata address above).
version: The release version displayed at the bottom of the homepage.
apps: The default /pocket-.../ paths automatically use your homepage domain.
      You can replace any one with a full https:// address to host it elsewhere.
socialImagePath: A path on your homepage domain or a full hosted image URL.
siteIconPath: "embedded" keeps the bundled icon and is independent of the domain.
              Enter a hosted icon path/full URL to update both the browser
              favicon and Apple bookmark/home-screen icon.

This configuration updates homepage/app links throughout the page, the footer
domain, canonical URL, Open Graph page/image URLs, Twitter image URL and
hosted icon URLs when the page loads in a browser. Relative hosted image/icon
paths resolve against your configured homepage, not the preview/download URL.
The social image must be available publicly at the configured address.

Important: this is a static HTML page using JavaScript to apply configuration.
Social-sharing crawlers that do not run JavaScript may not see those dynamic
metadata URLs. If hosted in Squarespace, its outer page metadata and icons must
also be set there; an embedded document's head cannot reliably override them.

Preserved amendments: responsive header, "Email" label, revised description
and copyright, visitor customisation and orange/gold app icon family.
The scrolling band has been removed, bringing the following content up.

This archive is the homepage only, not any of the five individual app ZIPs.
