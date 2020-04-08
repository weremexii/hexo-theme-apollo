![hexo-theme-apollo](https://pic.rmb.bdstatic.com/af5790651695edd53f917eb9c3b7708f.png)

本项目基于apollo主题修改, 新增支持`tag`显示, `category`页面  

## 文档

- [中文文档](https://github.com/achjqz/hexo-theme-apollo/blob/master/docs/doc-zh.md)
- [Document](https://github.com/achjqz/hexo-theme-apollo/blob/master/docs/doc-en.md)


## 安装

``` bash
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/achjqz/hexo-theme-apollo.git themes/apollo
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `apollo`:

```yaml
theme: apollo

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## 更新

``` bash
cd themes/apollo 
git pull
```

## 开发

``` bash
git clone https://github.com/achjqz/hexo-theme-apollo.git apollo
cd apollo
npm install
npm install --global gulp-cli
# 构建css
gulp
```

## License

MIT
