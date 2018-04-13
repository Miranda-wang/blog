工作环境:terminal,已经全局安装了vue(可使用npm install -g vue)

# 快速搭建大型单页面应用开发环境
 

```
># 全局安装vue-cli
npm install -g vue-cli
># 创建一个基于webpack模板的项目
npm init webpack my-demo
># 打开my-demo目录,安装开发依赖
cd my-demo
npm install
># 启动项目
npm run dev  如果出现DONE Compiled successfully in365s,Your application is running here :http://localhost:8080 说明已经安装成功,只是没有自动在浏览器打开,需要找到config/index.js文件,在文件module.exports配置中找到autoOpenBrowser,这时我们看设置的是false,将false改为true,使用ctrl+c关闭应用,再用npm run dev 重新启动即可

```
 
 
