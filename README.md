# hexo-theme-leedom

English | [简体中文](./README.zh-CN.md)

## Introduction

A pure theme of Hexo like Evan You's blog. The theme is derived from [Hexo-Theme-Oranges](https://github.com/zchengsite/hexo-theme-oranges), and the style is based on [Evan You's blog](https://blog.evanyou.me).
 
> MY BLOG
> 
>[THE PORTAL](https://blog.leedom.me/)

## Installation
`hexo-site` is the root directory of your hexo project

clone the entire repository:
```sh
cd hexo-site
git clone https://github.com/leedom92/hexo-theme-leedom.git themes/leedom
```

Or you can Install through npm:
```sh
cd hexo-site
npm i hexo-theme-leedom
```

## Usage

Edit the `theme` field in the `_config.yml` file under the project root:

```yml
theme: leedom
```

## Configuration
if there's an error when you are searching:
```html
The search.xml file was not found, please refer to：configuration
```

>please install [hexo-generator-search](https://github.com/wzpan/hexo-generator-search) plugin

```sh
npm install hexo-generator-search -S
```

add or edit configuration in your root `_config.yml`:
```yml
search:
  path: search.xml
  field: post
  content: true
```

edit configuration in the `themes/leedom/_config.yml`:
```yml
search:
  enable: true
  placeholder: 搜索
```

## License

[MIT](https://github.com/leedom92/hexo-theme-leedom/blob/master/LICENSE)
