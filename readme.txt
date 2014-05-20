
---
Symbolset
www.symbolset.com
Copyright © 2014 Oak Studios LLC
SS Emoji is a trademark of Oak Studios LLC in the United States and/or other countries.
---


SS Emoji Beta v0.001


--------------------
Desktop
--------------------

Your download contains the set you purchased as OTF, TTF, EOT, WOFF, and SVG font files. OTF, or OpenType Format, is a cross-platform font file for use on the desktop. Don't be misled by the name, each of these file types contain OpenType features. The remaining four files are formatted for web browsers.

Install the OTF font and use it in any desktop application that supports OpenType features.

Your symbol set contains both symbols and alphabetic characters. Begin by typing a keyword from the documentation. Once the keyword is completed, and the font recognizes the keyword, the correlating symbol will be displayed in place of the letters.


--------------------
Web
--------------------

Start by first uploading the "webfonts" folder to your webserver. Then place this link tag within the <head> tags of your HTML:

    <link href="webfonts/ss-emoji.css" rel="stylesheet" />

There are two common methods to use and reference symbols.

The first is use a symbol alongside a complementary word. Using class names, with CSS :before pseudo elements and Unicode code points, we can append symbols to words. In this example we're adding a poo symbol to a dislike button:

    <button class="ss-poo”>Dislike</button>

The second way is to use a symbol in place of a word. This method triggers symbols with semantic keywords. When using this method on the web apply the generic "ss-icon" class to the element wrapping the keyword.

For example, when showing that your current mood is rage:

    Current mood: <i class="ss-icon">rage</i>

A cog symbol will be displayed alongside the text "Settings".

When using the replacement technique, sighted users will see symbols and search engines and screen readers will see the semantic keyword.

You can also use symbols with their direct Unicode value. See documentation.html for a full list of supported icons. This example will show a smiling emoji icon:

    <i class="ss-icon">&#x1F601;</i> Happy


--------------------
Use with other sets
--------------------

If using in conjunction with another Symbolset (ie. Standard), include a reference to both CSS files (default set should be last) and add the secondary font's CSS class (ie. ".ss-standard") where desired.

    <link href="webfonts/ss-standard.css" rel="stylesheet" />
    <link href="webfonts/ss-emoji.css" rel="stylesheet" />
    ...
    <i class="ss-icon">Poo</i>
    <i class="ss-icon ss-standard">Grid</i>

For more see: http://blog.symbolset.com/using-multiple-sets/


--------------------
Support
--------------------

Support for multicolor fonts varies by approach. For info on each, see: http://blog.symbolset.com/multicolor-fonts/

For info on browser support for our standard sets, see: http://blog.symbolset.com/browser-support/


--------------------
Versions
--------------------

Periodically Symbolset will push updates to sets. We'll add keywords, build out symbols, and squash bugs. Be sure to check your account (http://symbolset.com/account) for updates.

