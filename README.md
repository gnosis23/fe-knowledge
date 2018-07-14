# fe-knowledge
写这个文档的目的就是整理一些现代前端工程需要掌握的知识点。

## 1. Javascript 基础
ES6 现在也是标配了吧，下文就不明确指出是否是 ES6 特性了。

### Spread Operator
[Spread operator 基本用法](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

实现原理？

### Annotation
比如 dva.js 里面的 `@connect`

### Babel
还有相关插件

## 2. React.js
[官网](https://reactjs.org/docs/getting-started.html)是很好的学习资料

### JSX

### props

### 高阶组件

## 3. Redux
### 3.1 Redux 是什么？
[Redux](https://redux.js.org/introduction) 是一种状态管理方案的实现；相较于 Flux ，Redux 增加了一些限制：
- Single source of truth: The state of your whole application is stored in an object tree within a single store.
- State is read-only: The only way to change the state is to emit an action, an object describing what happened.
- Changes are made with pure functions

### 3.2 Core API
store: dispatch, subscribe, reducer

### 3.3 实现原理
- [middleware](https://redux.js.org/advanced/middleware)
- [从零开始实现一个简单的redux](https://juejin.im/post/5a1ebe3b51882575d42f2629)


## 4. Webpack
### 主要插件介绍
- 图片插件
- 热模块替换

## 5. Create-react-app
学些 react-dev-utils 源代码
- 怎么打开浏览器
- 怎么自动下载依赖
- 怎么创建模板等等
