---
title: Template Instructions
layout: default
menu: 2
menutitle: Instructions
---
# SESYNC Site Template

This jekyll template supports the following features:

* single top menu
* Sidebar navigation
* customizable copyright

# Style Examples

# H1 Header

## H2 Header

### H3 Header

*Bold*

This is some raw text

## Adding items to the top menu

Any page that has 'menu' listed in the header will be included in the top menu. Optionally, items may also have a 'menutitle' attribute to use a different name for the menu link. In the case of this page, we want it to show up as Home rather than the default Sample Page title. You can take a look at page1.md and notice it only has the 'menu' option specifying its the first one.

Please note, the actual files for menus can be named anything.

## Editing the sidebar

Edit the markdown file located at _includes/sidebar.md. Below is what that file looks like. You can use the following items in a sidebar

* '#' h1 header
* '##' h2 header
* '*' list item
* links

<pre>

{% include sidebar.md %}

</pre>

# Customizing the Copyright

Open up _config.yml and edit the copyright section.

# Customizing css

edit the css/custom.css file
