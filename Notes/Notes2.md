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

*<!-- Favicon Links -->
<!-- <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png"> -->
<!-- <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png"> -->
<!-- <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png"> -->

<!-- Canonical URL -->
<!-- <link rel="canonical" href="https://yourwebsite.com/current-page"> -->*
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
    
    /* BASE MEDIA QUERY - Mobile First Approach */
    /* This is the most common and recommended pattern for responsive design */
    /* Start with styles for mobile devices, then use min-width to add styles for larger screens */
    @media (min-width: 768px) {
        /* Styles for tablets and larger devices */
        body { font-size: 16px; }
    }

    /* RESPONSIVE BREAKPOINTS */
    /* Extra small devices (phones) */
    @media (max-width: 480px) {
        body { font-size: 14px; }
        .container { padding: 10px; }
    }

    /* Small devices (landscape phones, tablets) */
    @media (min-width: 481px) and (max-width: 768px) {
        body { font-size: 15px; }
        .container { padding: 15px; }
    }

    /* Medium devices (tablets, small desktops) */
    @media (min-width: 769px) and (max-width: 1024px) {
        body { font-size: 16px; }
        .container { max-width: 750px; }
    }

    /* Large devices (desktops) */
    @media (min-width: 1025px) {
        body { font-size: 18px; }
        .container { max-width: 1200px; }
    }

    /* ORIENTATION-BASED MEDIA QUERIES */
    /* Portrait orientation (taller than wide) */
    @media (orientation: portrait) {
        .sidebar { width: 100%; }
    }

    /* Landscape orientation (wider than tall) */
    @media (orientation: landscape) {
        .sidebar { width: 30%; float: left; }
    }

    /* ACCESSIBILITY MEDIA QUERIES */
    /* Prefers reduced motion - for users with vestibular disorders or motion sensitivity */
    @media (prefers-reduced-motion: reduce) {
        * { animation-duration: 0.01ms !important; animation-iteration-count: 1 !important; transition-duration: 0.01ms !important; }
    }

    /* Prefers color scheme - respects user's light/dark mode preference */
    @media (prefers-color-scheme: dark) {
        body { background-color: #1a1a1a; color: #ffffff; }
    }

    @media (prefers-color-scheme: light) {
        body { background-color: #ffffff; color: #000000; }
    }

    /* High contrast mode - for users who need better contrast */
    @media (prefers-contrast: more) {
        body { border: 2px solid #000; }
        a { text-decoration: underline; }
    }

    /* Reduced transparency - for users sensitive to transparency effects */
    @media (prefers-reduced-transparency: reduce) {
        .modal { opacity: 1 !important; background: solid colors only; }
    }

    /* DEVICE-SPECIFIC MEDIA QUERIES */
    /* High DPI screens (Retina displays) */
    @media (min-resolution: 192dpi) {
        img { image-rendering: crisp-edges; }
    }

    /* Touch-capable devices */
    @media (hover: none) and (pointer: coarse) {
        button { padding: 15px; } /* Make buttons larger for touch */
        a { padding: 10px; } /* Add padding around clickable elements */
    }

    /* Hover-capable devices (mouse/trackpad) */
    @media (hover: hover) and (pointer: fine) {
        button:hover { background-color: #0056b3; }
    }

-->
```
