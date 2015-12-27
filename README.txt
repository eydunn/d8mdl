DESCRIPTION
-----------

A Google Material Design theme
https://www.google.com/design/spec/material-design
This theme is not for front-end beginners.
Targeting extreme performance in modern browsers and new web technologies and
low-powered devices, this theme is for lightweight sites.
Use it when you are ready to move away from jQuery.
http://andreapaiola.name/2015-07-materialize-css-vs-material-design-lite/



LAYOUT STRUCTURE: Standard Drupal 8 Regions and MDL Layout components
---------------------------------------------------------------------

https://api.drupal.org/api/drupal/core%21modules%21system%21templates%21page.html.twig/8
https://www.google.com/design/spec/layout/structure.html
http://www.getmdl.io/components/index.html#layout-section

page.header (Header)
Standard place for Site branding with logo, site name and site slogan.
In Material Design becomes the App bar / primary toolbar.

page.primary_menu (Primary menu)
Standard place for site Main navigation block, in Material Design becomes a navigation block in the header.

page.secondary_menu (Secondary menu)
Tipically the place for User account menu and users tasks, it becomes a layout block of menu type,
a hamburger menu in the header.
https://www.google.com/design/spec/components/menus.html
http://www.getmdl.io/components/index.html#menus-section

page.breadcrumb (Breadcrumb)
Breadcrumb navigation

page.highlighted (Highlighted)
Status messages: alerts and errors messages

page.help (Help)
Help messages

page.content (Content)
Main page contents: contains entities fields output and main user interactions/contents

page.sidebar_first (Left sidebar) and page.sidebar_second (Right sidebar)
You can use for faceted navigations, become MDL navigation drawers.
https://www.google.com/design/spec/patterns/navigation-drawer.html
http://www.getmdl.io/components/index.html#menus-section

page.footer (Footer)
Copyright and Term of service area. Easy.


INSTALLATION
------------

Standard theme installation: copy the unzipped dir into "themes" directory.
MDL's CSS and JS are in Google CDN, but you can load from local theme subdirectory mdl/, look at the theme configuration.
Download from http://www.getmdl.io/started/index.html#download
Current MDL version: 1.0.6, but if you want you can update MDL version in theme configuration.
Default colors are indigo-pink, but MDL colors is customizable here http://www.getmdl.io/customize/index.html
and you can set in theme configuration.