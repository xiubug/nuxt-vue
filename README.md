# nuxt-vue

基于nuxt.js + vue 最佳实践

- 预览：http://nuxt.sosout.com/

## 特性

- :gem: **特性一**：基于 Vue.js
- :rocket: **特性二**：自动代码分层
- :1234: **特性三**：服务端渲染
- :gem: **特性四**：强大的路由功能，支持异步数据
- :rocket: **特性五**：静态文件服务
- :1234: **特性六**：ES6/ES7 语法支持
- :gem: **特性七**：打包和压缩 JS 和 CSS
- :rocket: **特性八**：HTML头部标签管理
- :1234: **特性九**：本地开发支持热加载
- :gem: **特性十**：集成ESLint
- :rocket: **特性十一**：支持各种样式预处理器： SASS、LESS、 Stylus等等

## 模板
- [ ] 项目搭建

## 使用

```bash
$ git clone https://github.com/sosout/nuxt-vue.git
$ cd nuxt-vue
$ npm install or yarn install
$ npm run dev         # 访问 http://localhost:8888
```

## 使用pm2守护进程

```bash
# for development
$ pm2 start npm --name "my-nuxt" -- run dev

# for production
$ pm2 start npm --name "my-nuxt" -- run build         
```
