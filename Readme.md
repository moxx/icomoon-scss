# icomoon-scss
 Scss version of Icomoon Free Font Icons, ready to drop right into your Scss projects
 
Use in sass/scss

```sass
@import 'path/to/my/components/icomoon-scss/src/scss/icomoon'

```

Use as css (located in dist/css)
```html
<link href="/path/to/my/css/icomoon.min.css" rel="stylesheet">
```

Example Html
```html
<h1><i class="imo imo-home"></i> Home</h1>
```

find a full preview of all available icons on https://icomoon.io/preview-free.html


# Contribute
Easy to upgrade to a new version of iconmoon free set
```bash
npm install
bower install
gulp 
```
this will simple get the newest version from ``git://github.com/Keyamoon/IcoMoon-Free#master`` , out of the branch it will generate ttf,eot,woff,woff2 and grep all icon-codes from demo.css  and transform it to ``src/scss/_icons.scss``
