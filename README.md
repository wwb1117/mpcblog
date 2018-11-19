# mpcblog
基于 Node.js 的开源博客系统，采用响应式布局，支持手机访问，功能全面，美观大方。  
## 功能模块
* 文章列表
  * 支持搜索
  * 创新的竖向分页
* 文章详情
  * 自动生成目录
  * 支持评论 (基于[畅言](http://changyan.kuaizhan.com/))
* 留言
* 关于
* 后台管理
  * 网站统计  
  * 博客管理 - 新的文章 (支持 UEditor 和 Markdown 编辑器)  
  * 博客管理 - 分类管理  
  * 博客管理 - 文章管理  
  * 评论管理  
  * 留言管理  
  * 关于管理  
  * 缓存管理  
  * 异常管理  
  * 系统设置  

## 技术构成
* 服务端 [Node.js](https://nodejs.org/)
* web框架 [Express 4](http://expressjs.com/)
* 模板引擎 [Pug](https://pugjs.org/)
* JS库 [jQuery](http://jquery.com/)
* UI库 [Bootstrap 3](http://getbootstrap.com/)
* Web字体 [Font Awesome](https://fontawesome.com/)
* 持久化 [MongoDB](https://www.mongodb.org/)
* 缓存(可选) [Redis](http://redis.io/)
* 日志 [winston](https://github.com/winstonjs/winston/)
* 多语言 [i18n](https://github.com/mashpie/i18n-node)
* 身份验证 [Passport](http://www.passportjs.org/)

## 快速开始
#### 准备条件
安装 [Node.js](https://nodejs.org/en/download/) (v6 以上版本)、[MongoDB](https://www.mongodb.org/downloads/)、[Redis](http://redis.io/download/)（可选）。  
#### 安装依赖
```Shell
$ npm install
```

#### 启动站点  

```Shell
$ node bin/www 
```

打开浏览器，访问 [http://localhost:3000/](http://localhost:3000)
#### Enjoy it! :smile:


##### 启动
```Shell
$ NODE_ENV=production pm2 start bin/www -i 0
```

## 贡献者们
感谢给 iBlog2 项目贡献代码的朋友，感谢他们的支持，详情 [点击这里](https://github.com/eshengsky/iBlog2/graphs/contributors)。

