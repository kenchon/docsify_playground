# Headline

> An awesome project.

- [Release Note](/release-note/about-this-project)


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document Site</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="description" content="Description">
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <link rel="stylesheet" href="//unpkg.com/docsify/lib/themes/vue.css">
</head>
<body style="margin-top: 0;">
  <header style="background-color: brown;height: 5em;position: fixed;top: -0.5em;margin-top: 0;">
  </header>
  <div id="app"></div>
  <script>
    window.$docsify = {
      repo: '',
      topMargin: 30, 
      loadNavbar: true,
      autoHeader: true,
      // complete configuration parameters
      search: {
        maxAge: 86400000, // Expiration time, the default one day
        paths: [], // or 'auto'
        placeholder: 'Type to search',

        // Localization
        placeholder: {
          '/': 'Type to search'
        },

        noData: 'No Results!',

        // Headline depth, 1 - 6
        depth: 2,

        hideOtherSidebarContent: false, // whether or not to hide other sidebar content

        // To avoid search index collision
        // between multiple websites under the same domain
        namespace: 'website-1',
      }
    }
  </script>
  <script src="//unpkg.com/docsify/lib/docsify.min.js"></script>
</body>
</html>
```