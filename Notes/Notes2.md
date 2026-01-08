# Common HTML Meta Elements Reference

## Essential Meta Elements

```html
<!-- Basic Meta Elements (Required) -->

<!-- Character Encoding (Required) -->
<!-- <meta charset="UTF-8"> -->

<!-- Viewport for Responsive Design (Required for mobile-friendly sites) -->
<!-- <meta name="viewport" content="width=device-width, initial-scale=1.0"> -->

<!-- SEO Meta Elements -->
<!-- <meta name="description" content="Brief description of your website (155-160 characters)"> -->
<!-- <meta name="keywords" content="keyword1, keyword2, keyword3"> -->
<!-- <meta name="author" content="Your Name"> -->

<!-- Cache Control -->
<!-- <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate"> -->
<!-- <meta http-equiv="Pragma" content="no-cache"> -->
<!-- <meta http-equiv="Expires" content="0"> -->

<!-- Search Engine Crawling -->
<!-- <meta name="robots" content="index, follow"> -->

<!-- Mobile Theme Color -->
<!-- <meta name="theme-color" content="#your-color-code"> -->

<!-- Open Graph Meta Tags (for social media sharing) -->
<!-- <meta property="og:title" content="Your Page Title"> -->
<!-- <meta property="og:type" content="website"> -->
<!-- <meta property="og:url" content="https://yourwebsite.com"> -->
<!-- <meta property="og:image" content="https://yourwebsite.com/image.jpg"> -->
<!-- <meta property="og:description" content="Your page description"> -->
<!-- <meta property="og:site_name" content="Your Site Name"> -->
<!-- <meta property="og:locale" content="en_US"> -->

<!-- Twitter Card Meta Tags -->
<!-- <meta name="twitter:card" content="summary_large_image"> -->
<!-- <meta name="twitter:site" content="@yourtwitterhandle"> -->
<!-- <meta name="twitter:title" content="Your Page Title"> -->
<!-- <meta name="twitter:description" content="Your page description"> -->
<!-- <meta name="twitter:image" content="https://yourwebsite.com/image.jpg"> -->

<!-- Apple Mobile Web App Meta Tags -->
<!-- <meta name="apple-mobile-web-app-capable" content="yes"> -->
<!-- <meta name="apple-mobile-web-app-status-bar-style" content="black"> -->
<!-- <meta name="apple-mobile-web-app-title" content="App Name"> -->

<!-- Microsoft Tile -->
<!-- <meta name="msapplication-TileColor" content="#your-color-code"> -->
<!-- <meta name="msapplication-TileImage" content="/ms-icon-144x144.png"> -->

<!-- Favicon Links -->
<!-- <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png"> -->
<!-- <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png"> -->
<!-- <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png"> -->

<!-- Canonical URL -->
<!-- <link rel="canonical" href="https://yourwebsite.com/current-page"> -->
```

## Example Implementation

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Copy and paste relevant meta tags from above -->
    <title>Your Page Title</title>
  </head>
  <body>
    Your content here
  </body>
</html>
```

### CSS Reference Notes

``` CSS
<!-- CSS NOTES -->
<!-- When using CSS you can do a few things.
    You can select specific elements by using their tag name or you can select their parent and or children and siblings.
    Like so:
    div {} (This selects all div elements)
    div p {} (This selects all p elements that are children of div elements)
    div > p {} (This selects all p elements that are direct children of div elements)
    div + p {} (This selects all p elements that are immediate siblings of div elements)
    div ~ p {} (This selects all p elements that are siblings of div elements)
    div.classname {} (This selects all div elements with the class name of classname)
    #idname {} (This selects the element with the id of idname)
    .classname {} (This selects all elements with the class name of classname)
    You can also group elements together like so:
    div, p, section {}
    You can also use pseudo selectors like so:
    a:hover {}
    a:active {}
    a:visited {}
    a:focus {}
    You can also use attribute selectors like so:
    input[type="text"] {}
    input[type="password"] {}
    input[disabled] {}
    input[placeholder="Enter your name"] {}
    You can also use nth-child selectors like so:
    li:nth-child(odd) {}
    li:nth-child(even) {}
    li:nth-child(3) {}
    You can also use media queries like so:
    @media (max-width: 600px) {
        body { background-color: lightblue; }command:github.copilot.toggleStatusMenu
    }

-->
```
