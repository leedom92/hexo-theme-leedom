# hexo-theme-leedom

简体中文 | [English](./README.md)

## 简介

一个仿照尤雨溪博客的简洁的Hexo主题。该主题参考了[Hexo-Theme-Oranges](https://github.com/zchengsite/hexo-theme-oranges)，样式则是基于[尤雨溪的博客](https://blog.evanyou.me)。
 
> 我的博客
> 
>[传送门](https://blog.leedom.me/)

## 安装
`hexo-site` 是你的 hexo 项目的根目录

克隆整个存储库：
```sh
cd hexo-site
git clone https://github.com/leedom92/hexo-theme-leedom.git themes/leedom
```

或者通过npm安装：
```sh
cd hexo-site
npm i hexo-theme-leedom
```

## 用法

在项目根目录下的`_config.yml`文件中，编辑`theme`为`leedom`：

```yml
theme: leedom
```

## 配置
如果您在搜索时出现以下错误:
```html
The search.xml file was not found, please refer to：configuration
```

>请安装 [hexo-generator-search](https://github.com/wzpan/hexo-generator-search) 插件

```sh
npm install hexo-generator-search -S
```
在根目录下的 `_config.yml` 添加或编辑以下配置:
```yml
search:
  path: search.xml
  field: post
  content: true
```

在 `themes/leedom/_config.yml` 编辑配置:
```yml
search:
  enable: true
  placeholder: 搜索
```

## License

[MIT](https://github.com/leedom92/hexo-theme-leedom/blob/master/LICENSE)
