# lookthings.admin

> 本项目是使用 Element UI ，通过 vue-cli 构建

## 环境

![npm](https://img.shields.io/npm/v/npm.svg)
`npm >=6`

![node](https://img.shields.io/badge/node-%3E%3D6-brightgreen.svg)

`node >=6`

## 结构说明

```
├── .idea
├── src
|    ├── app                  主要代码文件
|    |     ├── components     组件模块
|    |     ├── config         项目文件
|    |     ├── lib            第三方模块
|    |     ├── services       服务模块，处理公共方法和后端接口交互
|    |     ├── app.router.js  路由模块
|    |     └── views          页面视图模块，用于构建几个模块的是视图
|    ├── assets               项目资源文件
|    ├── app.vue              基本组件
|    ├── main.js              vue 启动文件
|    ├── vendor.js            第三方文件
|    └── index.html           基本模板
├── CODE_OF_CONDUCT.md        代码行为
├── CONTRIBUTING.md           贡献者规范
├── webpack.config.js         webpack 配置文件
├── LICENSE                   开源声明
├── package.json              npm 初始文件
└── README.md                 说明文件
```

## 开始

 - 克隆和下载此仓库
 - 进入该文件下，安装依赖
 - cnpm 安装方式[淘宝镜像](https://npm.taobao.org/)

``` bash
npm install

# 如果安装较慢，或者中途过程出错，可以采用cnpm方式
# 先安装
npm install -g cnpm --registry=https://registry.npm.taobao.org
# 再通过
cnpm install
```



## 开发环境

``` bash
# serve with hot reload at localhost:8010
npm run dev
```

然后在浏览器中输入 localhost:8010，进行访问

## 构建

``` bash
# build for production with minification
npm run build
```

## 贡献者规范
[git提交归档和git分支规范](./CONTRIBUTING.md)

## 行为准则

[行为准则](./CODE_OF_CONDUCT.md)

## 开源声明

[MIT](./LICENSE)