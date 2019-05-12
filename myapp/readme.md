## 基于express搭建node后台框架

> 安装node环境

> 安装express
`````
npm -g install express
`````
> 安装express-generator
```
npm install express-generator -g
```
> 新建项目
```
express -e myapp // 创建基于ejs模板引擎输出html项目
```
> 项目结构
+ bin 是项目启动文件 配置以什么方式启动项目，默认npm start
+ public 是项目的静态文件 放置js css img等文件
+ routes 是项目的路由配置信息
+ view 是视图文件 放置模板文件ejs(相当于html)
+ www 配置项目启动
+ app.js 整个项目的入口文件，加载主要依赖包，配置中间件，加载路由等。
+ 


> 中间件
+ 安装session
```
npm install express-session
```
+ 安装cookie
```
npm install cookie-parser   --save
```



