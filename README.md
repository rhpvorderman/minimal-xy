MinimalNoXtras Pelican Theme
=======================

MinimalNoXtras [Pelican](https://getpelican.com/) is a no-frills fork from 
the excellent [MinimalXY](https://github.com/petrnohejl/minimal-xy) theme which 
was in turn extended from [minimalX](https://github.com/art1fa/minimalX) 
by [art1fa](https://github.com/art1fa).

Petr Nohejl did an excellent job into modifying the MinimalX theme into the 
MinimalXY theme that is visually pleasing yet minimalistic. The theme is also 
very easy to navigate. 




Design focus
------------

- Minimal flat design
- Good usability, simple & intuitive navigation
- Focus on what's really important &ndash; your articles
- Presented in a clean and straightforward way
- Very lightweight:
  - no custom fonts, 
  - no javascript
  - no trackers 
  - no social media buttons, disqus integration or other integrations.
  - no dependencies. In order to view the site, no javascript or css will be 
    downloaded from external sources.


Features
--------

- Fully responsive and mobile-first
- W3.CSS CSS framework & HTML5 semantics


Screenshots
-----------

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
