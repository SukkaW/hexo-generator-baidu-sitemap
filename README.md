# Sitemap generator

---

`fork`自[coneycode/hexo-generator-baidu-sitemap](https://github.com/coneycode/hexo-generator-baidu-sitemap)，由于原作者不在更新，自己在使用中又碰到了问题，所以自己维护这个副本

---

Generate sitemap.

**使用站图的初衷是[为自己的博客添加站内搜索](http://gengbiao.me/2014/10/22/hexo%E6%B7%BB%E5%8A%A0%E7%99%BE%E5%BA%A6%E7%AB%99%E5%86%85%E6%90%9C%E7%B4%A2/),如果想更好的发挥站图的作用，建议手动提交baidusitemap给百度.**

## Install

if your hexo version is 2.x.x, you should install as follow:

``` bash
$ npm install hexo-generator-baidu-sitemap@0.0.8 --save
install process ...
```

if version is 3.x.x, you should install as follow:

``` bash
$ npm install hexo-generator-baidu-sitemap@0.1.4 --save
install process ...
```

## Update

``` bash
$ npm remove hexo-generator-baidu-sitemap
install process ...
$ npm install hexo-generator-baidu-sitemap --save
```

## Options

if your hexo version is 2.x.x, you can configure this plugin in `_config.yml`.

``` yaml
baidusitemap:
    path: baidusitemap.xml
```

if version is 3.x.x, you should configure this plugin in `_config.yml`.

``` yaml
baidusitemap:
path: baidusitemap.xml

```

- **path** - Sitemap path. (Default: baidusitemap.xml)

## Errors

Maybe response is "hexo is not definded",then you should:

``` bash
$ cd node_modules/hexo-generator-baidu-sitemap/
node_modules/hexo-generator-baidu-sitemap/
$ npm install
```
