#  Vue.js+LeanCloud单页面博客

## 简介
一个前后端完全分离的单页应用  [线上地址点此查看](http://jiangjiu.leanapp.cn)
采用了之前写的 vue.js+LeanCloud（node.js） 的开发样板 [github地址点此查看](https://github.com/jiangjiu/vue-leancloud-boilerplate)

## 技术栈
### 前端
- [Vue.js](https://github.com/vuejs/vue)
- [vuex 状态管理](https://github.com/vuejs/vuex)
- [vue-router 路由](https://github.com/vuejs/vue-router)
- [vue-resource xhr请求](https://github.com/vuejs/vue-resource)


### 后端
- [node.js 服务端](https://github.com/nodejs/node)
- [express 框架](https://github.com/expressjs/express)
- [LeanCloud 数据存储](http://www.leancloud.com)

## 开发

```bash
git clone git@github.com:jiangjiu/vue-leancloud-blog.git
$ cd vue-leancloud-blog
$ npm install

// 启动服务器端, 默认地址 http://localhost:3000
$ lean up

// 另开一个 terminal
$ cd FE
$ npm install
// 启动前端项目，默认地址 http://localhost:8080
$ npm run dev
```

## 构建部署

```bash
// 在FE目录下  构建前端文件至 /public 文件夹
$ npm run build

// 根目录下 leancloud命令行部署 / 通过 github 部署
$ lean deploy / lean deploy -g

```

具体部署可参考[LeanCloud云引擎 Node.js 部署](https://leancloud.cn/docs/leanengine_webhosting_guide-node.html#部署)

## License
MIT
