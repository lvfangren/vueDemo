# WYSIWYG

基于webpack5 + vue2X + ts的项目模版

解决项目配置问题，相对于vite或者其它一些脚手架工具，这解决了生产环境配置，跨域接口请求，CI/CD配置等问题（当然，前提是你的项目需要像我一样[配置生产环境](#关于生产环境配置)相关），这让你可以更加集中精力的完成项目的页面开发，当完成开发后可以很快的部署，让所有人看到成果，而不是只能运行在你的本地服务下。

有些时候会对一些集成度高的工具产生些排斥，有些时候它反会让人觉得难以下手。

## 使用
当这个项目模版clone下来后

* npm install

* npm run dev

它运行了一个基本的例子，但是不像vue-cli等工具，这没有组织你项目的目录结构，例如：你可以把你的图片文件夹命名成AAA都是可以的，但是注意不要修改已经指定的文件目录，这个很重要！


## 关于生产环境配置

阿里云服务器准备


## 案例支持

* [XXX](baidu.com)

如果您的项目使用了这个项目模版完成，可以在issue或者pr提出，希望得到您的支持！

## 其它

考虑到灵活度我没有配套安装vue-router等相关全家桶，我认为那是和你开发的项目需求有关，属于业务层面的需要，所以你可以自行配套安装使用。

关于vue3版本的需求，建议clone这个项目模版后可以使用[@vue/compat](https://v3.vuejs.org/guide/migration/migration-build.html#overview)完成项目vue3的支持

本意是希望所见即所得

## 参考

[webpack文档](https://www.webpackjs.com/guides/)

[vue-loader文档](https://vue-loader.vuejs.org/)

[eslint文档](https://eslint.org/docs/user-guide/configuring/configuration-files#extending-configuration-files)

[API接口](https://www.v2ex.com/p/7v9TEc53)

### License

MIT