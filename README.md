##  React 笔记整理

#### React 简介
     用于构建用户界面的JavaScript库
     由FaceBook开发且开源

+ **原生 JS 痛点**

    - 操作 <u style="color:#1661ab">DOM</u> 繁琐，效率低
    - 直接操作 <u style="color:#1661ab">DOM</u>，浏览器会进行大量的重排重绘
    - 没有 <u style="color:#1661ab">组件化</u> 的编码方案，代码复用率低

+ **React 特点**

    - 采用  <u style="color:#1661ab">组件化模式，声明式编码</u>，提高<u style="color:#1661ab">开发效率</u>和<u style="color:#1661ab">组件复用率</u>。
    - 在 React Native 中可以使用 React 进行移动端开发
    - 使用 **<u style="color:#de1c31">虚拟DOM</u>** 和优秀的 **<u style="color:#de1c31">diffing算法</u>**，尽量减少与真实DOM的交互<>

+ **虚拟 DOM**
    - 本质是对象
    - 相比真实DOM较轻
    - 最终会转化为真实DOM呈现在页面中

#### React 的基本使用

+ **相关 js 库**
    1) react.js ：React 核心库
    2) react-dom.js：提供操作 DOM 的 react 扩展库
    3) babel.min.js：解析 JSX 语法代码转为 JS 代码的库

注：[code => react-basic](/react-basic);