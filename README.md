# SS Emoji Beta


### Use on the web


Start by first uploading the `webfonts` folder to your webserver. Then place this link tag within the `<head>` tags of your HTML:

```html
<link href="webfonts/ss-emoji.css" rel="stylesheet" />
```

To use an icon wrap the word in an `ss-icon` class. For example, when showing that your current mood is rage:

    Current mood: <i class="ss-icon">rage</i>

When using the replacement technique, sighted users will see symbols and search engines and screen readers will see the semantic keyword.

You can also use symbols with their direct Unicode value. See `documentation.html` for a full list of supported icons. This example will show a smiling emoji icon:

```html
<i class="ss-icon">&#x1F601;</i> Happy
```

### Use with other sets

If using in conjunction with another Symbolset (ie. Standard), include a reference to both CSS files (default set should be last) and add the secondary font's CSS class (ie. `ss-standard`) where desired.

```html
<link href="webfonts/ss-standard.css" rel="stylesheet" />
<link href="webfonts/ss-emoji.css" rel="stylesheet" />
...
<i class="ss-icon">Poo</i>
<i class="ss-icon ss-standard">Grid</i>
```

For more see: http://blog.symbolset.com/using-multiple-sets/


### Support

Support for multicolor fonts varies by approach. For info on each, see: http://blog.symbolset.com/multicolor-fonts/

For info on browser support for our standard sets, see: http://blog.symbolset.com/browser-support/

### License
[SIL Open Font License, Version 1.1](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web)
See the LICENSE file for more info.

