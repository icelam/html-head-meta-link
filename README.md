# Link and Meta Tags Collections #

> A collection of `<link>` and `<meta>` tags in HTML `<head>` section

### Meta Tags ###

```html
<!-- Recommend minimum -->
<meta charset="utf-8" />
<meta name="viewport" content="minimum-scale=1, initial-scale=1, width=device-width, shrink-to-fit=no" />

<!-- Content type -->
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

<!-- Site / Page language -->
<meta name="language" content="English" />

<!-- Tell IE and Chrome to use the latest engine -->
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"/>

<!-- Security Policy -->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">

<!-- Turn off auto Format detetction -->
<meta name="format-detection" content="telephone=no">
<meta name="format-detection" content="date=no">
<meta name="format-detection" content="address=no">
<meta name="format-detection" content="email=no">
<!-- Disable detection and formatting for skype toolbar plugin -->
<meta name="skype_toolbar" content="skype_toolbar_parser_compatible">

<!-- SEO -->
<meta name="description" content="" />
<meta name="keywords" content="" />
<meta name="title" content="" />

<!-- Indexing rules for all search engines -->
<meta name="robots" content="index,follow">
<!-- Indexing rules for Google -->
<meta name="googlebot" content="index,follow">

<!-- Disable sitelinks search box on Google Search result-->
<meta name="google" content="nositelinkssearchbox">

<!-- Open Graph (Facebook) -->
<meta property="fb:app_id" content="123456789">
<meta property="og:url" content="https://example.com/page.html">
<meta property="og:type" content="website">
<meta property="og:title" content="Content Title">
<meta property="og:image" content="https://example.com/image.jpg">
<meta property="og:image:secure_url" content="https://example.com/image.jpg" />
<meta property="og:image:type" content="image/jpg" />
<meta property="og:image:width" content="1280" />
<meta property="og:image:height" content="630" />
<meta property="og:image:alt" content="A description of what is in the image (not a caption)">
<meta property="og:description" content="Description Here">
<meta property="og:site_name" content="Site Name">
<meta property="og:locale" content="en_US">
<meta property="article:author" content="">

<!-- Twitter -->
<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@site_account">
<meta name="twitter:creator" content="@individual_account">
<meta name="twitter:url" content="https://example.com/page.html">
<meta name="twitter:title" content="Content Title">
<meta name="twitter:description" content="Content description less than 200 characters">
<meta name="twitter:image" content="https://example.com/image.jpg">
<meta name="twitter:image:alt" content="A text description of the image conveying the essential nature of an image to users who are visually impaired. Maximum 420 characters.">

<!-- PWA -->
<link rel="manifest" href="/manifest.json" />

<!-- Android -->
<meta name="mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#000000">

<!-- iOS  -->
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-title" content="Application Title">
<meta name="apple-mobile-web-app-status-bar-style" content="black" />
<meta name="apple-touch-fullscreen" content="yes">

<link rel="apple-touch-icon" sizes="180x180" href="images/apple-touch-icon-180x180.png" />
<link rel="apple-touch-icon" sizes="152x152" href="images/apple-touch-icon-152x152.png" />
<link rel="apple-touch-icon" sizes="144x144" href="images/apple-touch-icon-144x144.png" />
<link rel="apple-touch-icon" sizes="120x120" href="images/apple-touch-icon-120x120.png" />
<link rel="apple-touch-icon" sizes="114x114" href="images/apple-touch-icon-114x114.png" />
<link rel="apple-touch-icon" sizes="76x76" href="images/apple-touch-icon-76x76.png" />
<link rel="apple-touch-icon" sizes="72x72" href="images/apple-touch-icon-72x72.png" />
<link rel="apple-touch-icon" sizes="57x57" href="images/apple-touch-icon-57x57.png" />
<link rel="apple-touch-icon" href="images/apple-touch-icon-57x57.png" />

<link rel="apple-touch-startup-image" sizes="768x1004" href="images/apple-splash-screen-768x1004-iPad.png"/>
<link rel="apple-touch-startup-image" sizes="1536x2008" href="images/apple-splash-screen-1536x2008-iPad.png"/>
<link rel="apple-touch-startup-image" sizes="1024x748" href="images/apple-splash-screen-1024x748-iPad.png"/>
<link rel="apple-touch-startup-image" sizes="2048x1496" href="images/apple-splash-screen-2048x1496-iPad.png"/>
<link rel="apple-touch-startup-image" href="images/apple-splash-screen-320x480.png"/>
<link rel="apple-touch-startup-image" sizes="640x960" href="images/apple-splash-screen-640x960.png"/>
<link rel="apple-touch-startup-image" sizes="640x1136" href="images/apple-splash-screen-640x1136.png"/>

<!-- Smart App Banner -->
<meta name="apple-itunes-app" content="app-id=APP_ID,affiliate-data=AFFILIATE_ID,app-argument=SOME_TEXT">

<!-- Android app deep linking -->
<meta name="google-play-app" content="app-id=package-name">
<link rel="alternate" href="android-app://package-name/http/url-sample.com">
<link rel="chrome-webstore-item" href="https://chrome.google.com/webstore/detail/APP_ID">

<!-- iOS app link -->
<meta property="al:ios:url" content="applinks://docs">
<meta property="al:ios:app_store_id" content="12345">
<meta property="al:ios:app_name" content="App Links">

<!-- Android app link -->
<meta property="al:android:url" content="applinks://docs">
<meta property="al:android:app_name" content="App Links">
<meta property="al:android:package" content="org.applinks">

<!-- Web fall back -->
<meta property="al:web:url" content="https://applinks.org/documentation">

<!-- Windows  -->
<meta name="msapplication-navbutton-color" content="#000000">
<meta name="msapplication-TileColor" content="#000000">
<meta name="msapplication-TileImage" content="ms-icon-144x144.png">
<meta name="msapplication-config" content="browserconfig.xml">
<meta name="msapplication-tap-highlight" content="no">

<!-- Pinned Sites  -->
<meta name="application-name" content="Application Name">
<meta name="msapplication-tooltip" content="Tooltip Text">
<meta name="msapplication-starturl" content="/">

<!-- Pinned Tab  -->
<link href="path/to/icon.svg" rel="mask-icon" size="any" color="#000000">

<!--Favicons-->
<link rel="shortcut icon" href="/favicon.ico" />

<!-- AMP link -->
<link rel="amphtml" href="https://example.com/path/to/amp-version.html">

<!-- Links with same or similar contents -->
<link rel="canonical" href="https://example.com/" />

<!-- Alternative links in other langiages -->
<link rel="alternate" href="https://es.example.com/" hreflang="es">

<!-- RSS / Atom -->
<link rel="alternate" href="https://feeds.feedburner.com/example" type="application/rss+xml" title="RSS">
<link rel="alternate" href="https://example.com/feed.atom" type="application/atom+xml" title="Atom 0.3">

<!-- Disable translation in Google Chrome -->
<meta name="google" content="notranslate">

<!-- Set the base URL for all relative URLs within the document -->
<base href="https://example.com/page.html">
```

### manifest.json ###
```json
{
  "name": "app name",
  "short_name": "short name",
  "icons": [{
    "src": "images/icons/icon-48x48.png",
    "sizes": "48x48",
    "type": "image/png"
  },
  {
    "src": "images/icons/icon-72x72.png",
    "sizes": "72x72",
    "type": "image/png"
  },
  {
    "src": "images/icons/icon-96x96.png",
    "sizes": "96x96",
    "type": "image/png"
  },
  {
    "src": "images/icons/icon-144x144.png",
    "sizes": "144x144",
    "type": "image/png"
  },
  {
    "src": "images/icons/icon-168x168.png",
    "sizes": "168x168",
    "type": "image/png"
  },
  {
    "src": "images/icons/icon-192x192.png",
    "sizes": "192x192",
    "type": "image/png"
  },
  {
    "src": "images/icons/icon-256x256.png",
    "sizes": "256x256",
    "type": "image/png"
  },
  {
    "src": "images/icons/icon-512x512.png",
    "sizes": "512x512",
    "type": "image/png"
  }],
  "orientation": "portrait",
  "display": "standalone",
  "theme_color": "#000000",
  "background_color": "#ffffff"
}
```

### browserconfig.xml ###
```
<?xml version="1.0" encoding="utf-8"?>
<browserconfig>
   <msapplication>
     <tile>
        <square70x70logo src="small.png"/>
        <square150x150logo src="medium.png"/>
        <wide310x150logo src="wide.png"/>
        <square310x310logo src="large.png"/>
     </tile>
   </msapplication>
</browserconfig>
```
