# hexo-theme-Caerus

A simple and beautiful theme for [Hexo].

[![](/img/caerus.png)](http://txliang.com/)

## Installation
You can clone or download the zip if you like it,and then put it to your themes folder,change the `_config.yml` configuration file's option: `theme: Caerus`.And you can adjust it to comply with your needs.

## attention
1. A defect is the stylesheet, Caerus's stylesheet use SCSS, but it need you using gem compile `style.scss` to `style.css` by your hands.
2. Caerus is not good to configurable.
2. Caerus is not perfect, it's very simple.

### Fancybox
Caerus uses [Fancybox] to showcase your photos. You can use Markdown syntax or fancybox tag plugin to add your photos.

```
![img caption](img url)

{% fancybox img_url [img_thumbnail] [img_caption] %}
```

### Sidebar
Caerus provides 5 built-in widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

All of them are enabled by default. You can edit them in `widget` setting.

## Development

[Hexo]: http://zespia.tw/hexo/
[Fancybox]: http://fancyapps.com/fancybox/
[Font Awesome]: http://fontawesome.io/
