---
title: First post
subtitle: With subtitle
date: 2021-07-05T15:37:55.483Z
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
## Enable the CMS integration

If you just created a new site with the Academic template, you can skip this step as the module is enabled by default.

For other templates or older sites, browse your GitHub project to check that the CMS module is added to your config/_default/config.yaml`:

### At the bottom of your `config.yaml` is a Module section:

```yaml
module:
  imports:
   # Add the Wowchemy CMS module below, if it has not already been added:
    - path: github.com/wowchemy/wowchemy-hugo-modules/wowchemy-cms
    - path: github.com/wowchemy/wowchemy-hugo-modules/wowchemy