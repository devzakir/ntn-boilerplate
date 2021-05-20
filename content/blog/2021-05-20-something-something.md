---
title: Something Something
description: "Hello, world. lorem ipsum dollar sit amet. Hello, world. lorem
  ipsum dollar sit amet. Hello, world. lorem ipsum dollar sit amet. Hello,
  world. lorem ipsum dollar sit amet. Hello, world. lorem ipsum dollar sit amet.
  Hello, world. lorem ipsum dollar sit amet. "
---
## Setting Up Netlify CMS

### [](https://www.netlifycms.org/docs/nuxt/#add-the-netlify-cms-files-to-nuxt)Add the Netlify CMS files to Nuxt

In the `static/` directory, create a new directory `admin/`. Inside that directory you'll create two files, your `index.html` and a `config.yml`. Per the [Netlify CMS documentation](https://www.netlifycms.org/docs/add-to-your-site/), we'll set the content of `static/admin/index.html` to the following:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Content Manager</title>
    <!-- Include the script that enables Netlify Identity on this page. -->
    <script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
  </head>
  <body>
    <!-- Include the script that builds the page and powers Netlify CMS -->
    <script src="https://unpkg.com/netlify-cms@^2.0.0/dist/netlify-cms.js"></script>
  </body>
</html>
```

For your `static/admin/config.yml` file, you can put in a basic starter config: