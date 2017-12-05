# prettify_demo

* 问题：用google-code-prettify高亮博客的代码，行号怎么全部显示？  
解决：Prettify 默认的是每5行显示一个行号。  
想让行号全部显示，加入如下样式代码：
```
li.L0, li.L1, li.L2, li.L3, li.L5, li.L6, li.L7, li.L8, li.L9 {
   list-style-type: decimal !important
  }
```

* 
```
不管是使用SyntaxHighlighter，还是使用Google-Code-Prettify，源代码中的"<"和">"都应该替换成&lt;和&gt;，否则可能无法正确进行语法高亮修饰。
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
