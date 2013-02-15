pelican-variant-note
====================

This is a monospaced typography theme for pelican. It is based on the CSS template [variant-note](http://andreasviklund.com/files/demo/variant-note/) by [Andreas Viklund](http://andreasviklund.com/). You can visit [this article](http://andreasviklund.com/learn/customizing-the-images-in-the-variant-note-template/) to know about tweaking the template.

Its main tips:

* Tiny, clear, and simple. It loads quickly.
* Monospace font as main one
* It uses a small subset of [Awesome Fonts](http://fortawesome.github.com/Font-Awesome/) to render social and other icons
* Social sharing integration (up to now: [twitter](http://twitter.com), [G+](https://plus.google.com/) and [Facebook](http://facebook.com)
* Includes [pygments](http://pygments.org/) for syntax highlighting

Actually it is used on my blog [Bitakoro](http://bitakoro.tk/)

![](https://raw.github.com/mpancorbo/pelican-variant-note/master/preview.png)

Variables
---------

Some new optional variables can be added to `pelicanconf.py`

* `MENU_TEXT`, text for menu header
* `LINKS_TEXT`, text for blogroll header
* `CATEGORIES_TEXT`, text for category list header
* `SOCIAL_TEXT`, text for social links header
* `FOOTER_TEXT`, text for footer
* `GOOGLE_PLUS_SHARE`, `True` for adding an icon to share the article on G+
* `FACEBOOK_SHARE`, `True` for adding an icon to share the article on Facebook
* `TWITTER_USERNAME`, if set, an icon is added to share the article on Twitter
* `SITEURLABS`, it's mandatory if you want any social sharing to work properly. It shoud have the same value as `SITEURL` and it's used on the query strings. This setting avoids jamming the use of relative paths in your blog.
* `CATEGORY_ICONS`, set of duplas with category name and its correspondig name in the [Awesome Ffonts](http://fortawesome.github.com/Font-Awesome/)


Tipography
----------

This theme is one of the most awesome I've seen with monospaced fonts. The CSS template originally comes with the font `Sax Mono`, of [Font Squirrel](http://www.fontsquirrel.com/fontface) to render the main text, but it lacks the special characters of language Esperanto, on which I write the blog. Nevertheless I kept it and used it as the base font for [pygments](http://pygments.org/).

The theme uses `PT Mono`, from Google Webfonts.

License
-------

The theme is given back to public domain, with the limits eventually imposed by the licenses of its contributors: [Andreas Viklund](http://andreasviklund.com/about/copyright/), [Awesome Fonts](http://fortawesome.github.com/Font-Awesome/#license), [pygments](http://pygments.org/.)
