# prettify_demo

* 问题：用google-code-prettify高亮博客的代码，但是行号怎么也无法显示？  
解决：加入如下样式代码：
```
li.L0, li.L1, li.L2, li.L3, li.L5, li.L6, li.L7, li.L8, li.L9 {
   list-style-type: decimal !important
  }
```

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
