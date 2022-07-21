MinimalBandwith Pelican Theme
=============================

A good-looking minimal [Pelican](https://getpelican.com/) theme that uses 
only 39kb of css (8kb gzipped). No Pelican plugins are required to use this
theme.

MinimalBandwith is a no-frills fork from the excellent 
[MinimalXY](https://github.com/petrnohejl/minimal-xy) theme which 
was in turn extended from [minimalX](https://github.com/art1fa/minimalX) 
by [art1fa](https://github.com/art1fa).

Petr Nohejl did an excellent job into modifying the MinimalX theme into the 
MinimalXY theme that is visually pleasing yet minimalistic. The theme is also 
very easy to navigate. 

MinimalBandwith removes all the features that makes the modern internet 
sluggish and bandwidth consuming. There are no custom fonts, there is no 
javascript and there are no links to third-parties that need to be accessed in 
order for the website to render.

If you like this theme please send your regards and stars to Petr Nohejl
at the [MinimalXY repository](https://github.com/petrnohejl/minimal-xy). My 
Only contribution has been pressing the delete button.

This effort was inspired by the [solar-powered version of Low-tech Magazine](
https://solar.lowtechmagazine.com/). Which is an extremely low-bandwith site.
You can read more about their efforts [here](
https://solar.lowtechmagazine.com/about.html). They also have a custom 
pelican theme named [solar](https://github.com/lowtechmag/solar).

Design focus
------------

- Very lightweight:
  - no custom fonts, 
  - no javascript
  - no trackers 
  - no social media buttons, disqus integration or other integrations.
  - no external dependencies. In order to view the site, no javascript or css 
    will be downloaded from external sources.

- Visual design from MinimalXY: It is already excellent so I
  will simply import any changes from the MinimalXY upstream.

Screenshots
-----------
From the original [MinimalXY theme](https://github.com/petrnohejl/minimal-xy). 
This theme looks the same.

- [Screenshot #1](screenshot1.png)
- [Screenshot #2](screenshot2.png)


How to use
----------

```python
# Theme
THEME = '/path/to/MinimalXY'

# Theme customizations
MINIMALXY_CUSTOM_CSS = 'static/custom.css'
MINIMALXY_FAVICON = 'favicon.ico'
MINIMALXY_START_YEAR = 2009
MINIMALXY_CURRENT_YEAR = date.today().year

# Author
AUTHOR_INTRO = u'Hello world! I’m John Doe.'
AUTHOR_DESCRIPTION = u'Hello world! I’m John Doe. I like coffee, birds and Python.'
AUTHOR_AVATAR = 'http://www.gravatar.com/avatar/abcdefghijkl?s=240'
AUTHOR_WEB = 'http://mypersonalsite.com'

# Services
GOOGLE_ANALYTICS = 'UA-12345678-9'
DISQUS_SITENAME = 'johndoe'

# Social
SOCIAL = (
    ('facebook', 'http://www.facebook.com/johndoe'),
    ('twitter', 'http://twitter.com/johndoe'),
    ('github', 'https://github.com/johndoe'),
    ('linkedin', 'http://www.linkedin.com/in/johndoe'),
)

# Menu
MENUITEMS = (
    ('Categories', '/' + CATEGORIES_SAVE_AS),
    ('Archive', '/' + ARCHIVES_SAVE_AS),
)
```

Follow the [Pelican documentation](https://docs.getpelican.com/en/stable/settings.html) for more info or check the [code](https://github.com/petrnohejl/Blog) of my personal blog.


License
-------

[MIT](LICENSE)
