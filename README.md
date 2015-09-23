# hexo-theme-biture

A single column, widget-less minimalist theme for [Hexo], based on [Pure] css framework, forked from https://github.com/kywk/hexo-theme-biture

Preview: http://wzktravel.github.io/


## Installation

### Install

``` bash
$ git clone https://github.com/wzktravel/hexo-theme-biture.git themes/biture
```

### Enable

Modify `theme` setting in `_config.yml` to `biture`.

### Update

``` bash
cd themes/biture
git pull
```


## Configuration

``` yml
# Header
menu:
  home: /
  archive: /archive
  submenu:
    google: //google.com/
    yahoo:  //yahoo.com/

extmenu:
  github: //github.com/
  hexo: //hexo.io/zh-cn/
  theme:
    Pithiness:  //github.com/okoala/hexo-theme-pithiness 

rss:

# Content
excerpt_link: Read More

fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```
- **menu** - Main navigation menu, dropdown menu supported.
- **extment** - Extend menu at the right hand side, dropdown menu supported too.
- **rss** - RSS subscription link (change if using Feedburner)
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - KEEP IT 'true'
- **google_analytics** - Google Analytics ID

## toc
在文章页面增加toc(table of contents)
使用方法：
1. 在`_config.yml`中添加`toc: true`
1. 每个页面中可以手动关闭, `toc: off`
``` yml
title: 日志追查总结
date: 2015-09-10 20:03:00
tags: [shell, log, hive, sql]
toc: off
```

[Hexo]: https://hexo.io/
[Pure]: http://purecss.io/
