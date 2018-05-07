# Paradox

A simple theme for [Hexo].

## Installation

### Install

``` bash
$ git clone https://github.com/affogatoproject/paradox
```

### Enable

Modify `theme` setting in `_config.yml` to `paradox`.

### Update

``` bash
cd themes/paradox
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml


# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **menu** - Navigation menu
- **rss** - RSS link
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path

[Hexo]: https://hexo.io/
[hexo-generate-feed]: https://github.com/hexojs/hexo-generator-feed
