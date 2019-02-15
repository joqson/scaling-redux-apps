
### [读 React 16.x 源码](./docs/stories/react/README.md)

### 深入实践 [Redux Dynamic Modules](https://github.com/Microsoft/redux-dynamic-modules), 构建大型可伸缩的 React + Redux App
* 油管上视频：[Redux Dynamic Modules - Navneet Gupta & Alex B](https://www.youtube.com/watch?v=SktRbSZ-4Tk)
* 文字脱敏[Scaling Redux Apps](./docs/stories/scaling-redux-app.md)

### React-Admin 相关
* [官方文档](https://marmelab.com/react-admin/) | [中文文档](https://react-admin.com) | [Demo](https://o-o.ren/scaling-redux-apps/demo/#/customers)
* [简介](https://react-admin.com/docs/zh-CN/intro.html)
* [十分钟教程](https://react-admin.com/docs/zh-CN/tutorial.html)
* [数据提供程序](https://react-admin.com/docs/zh-CN/data-providers.html)
* [Admin 组件](https://react-admin.com/docs/zh-CN/admin-component.html)
* [Resource 组件](https://react-admin.com/docs/zh-CN/resource-component.html)
* [List 视图组件](https://react-admin.com/docs/zh-CN/list-view-component.html)
* [Show 视图组件](https://react-admin.com/docs/zh-CN/show-view-component.html)
* [Field 组件](https://react-admin.com/docs/zh-CN/field-components.html)
* [Create 和 Edit 视图组件](https://react-admin.com/docs/zh-CN/creat-edit-view-components.html)
* [Input 组件](https://react-admin.com/docs/zh-CN/input-components.html)
* [身份验证](https://react-admin.com/docs/zh-CN/authentication.html)
* [授权](https://react-admin.com/docs/zh-CN/authorization.html)
* [主题](https://react-admin.com/docs/zh-CN/theming.html)
* [编写 Action](https://react-admin.com/docs/zh-CN/actions.html)
* [i18n](https://react-admin.com/docs/zh-CN/translation.html)
* [在其它 App 中包含 Admin](https://react-admin.com/docs/zh-CN/custom-app.html)
* [引用](https://react-admin.com/docs/zh-CN/reference.html)
* [常见问题](https://react-admin.com/docs/zh-CN/faq.html)
* [生态](https://react-admin.com/docs/zh-CN/ecosystem.html)

### 核心组件及源码分析

扩展安装：[Redux DevTools Extension](https://github.com/zalmoxisus/redux-devtools-extension)

1. [调试 React-Admin 源码，看清框架的本质](./docs/stories/debug-react-admin.md)
2. [`localhost:8080` 背后的动作](./docs/stories/redux-devtools/npm-start.md)
3. [`localhost:8080/#/login` 背后的动作](./docs/stories/redux-devtools/route-login.md)
4. [React-Admin 架构分析：`Admin` 组件源码解析之 `dataProvider` 属性](./docs/stories/core-admin-data-provider.md)
5. [React-Admin 架构分析：Material-UI 定制](./docs/stories/material-ui-customization.md)
    * [React-Admin 架构分析：Material-UI 定制之 `Themes` 文档](./docs/stories/material-ui-customization-themes.md)
    * [React-Admin 架构分析：Material-UI 定制之 `Overrides` 文档](./docs/stories/material-ui-customization-overrides.md)
    * [React-Admin 架构分析：Material-UI 定制之 `CSS in JS` 文档](./docs/stories/material-ui-customization-css-in-js.md)
    * [React-Admin 架构分析：Material-UI 定制之 `Default Theme` 文档](./docs/stories/material-ui-customization-default-theme.md)
6. [React-Admin 架构分析：`Admin` 组件源码解析之 `theme` 属性](./docs/stories/core-admin-app-theme.md)
7. [React-Admin 架构分析：`Admin` 组件源码解析之 `appLayout` 属性](./docs/stories/core-admin-app-layout.md)
8. [react-admin 包分析](./docs/stories/react-admin-package.md)
9. [ra-core 包分析](./docs/stories/ra-core-package.md)
10. [Admin 组件源码解析](./docs/stories/Admin.md)（有干货但有些凌乱，留作纪念）
11. [CoreAdminRouter 组件源码分析](./docs/stories/CoreAdminRouter.md)（有干货但有些凌乱，留作纪念）
12. [最早的想法（留作纪念）](./docs/stories/old-readme.md)
13. [ImageInput 相关问题](https://github.com/Kirk-Wang/react-admin-app/issues/1)
14. [AOP & middleware(1秒懂^_^)](./docs/stories/aop-middleware.md)

脑图备份：
* [React源码大纲](./docs/images/react/react-1.png)
* [浅聊 Virtual DOM](./docs/images/react/virtual_dom.png)
* [ES相关基础](./docs/images/jsms/ES_basic.png)
* [JS-WEB-API](./docs/images/jsms/JS-WEB-API.png)
* [CSS-HTML](./docs/images/jsms/CSS-HTML.png)
* [前端性能](./docs/images/perf/perf_img.png)
* [缓存](./docs/images/perf/perf_cache.png)
* [本地存储](./docs/images/perf/perf_storage.png)
* [CDN](./docs/images/perf/perf_cdn.png)
* [页面渲染](./docs/images/perf/perf_pagerender.png)
* [浏览器运行机制浅析](./docs/images/perf/perf_explorer.png)
* [浅析DOM优化原理](./docs/images/perf/perf_dom.png)
* [Event Loop 与异步更新策略](./docs/images/perf/perf_eventloop.png)
* [回流与重绘](./docs/images/perf/perf_reflow_repaint.png)
* [首屏](./docs/images/perf/perf_homepage.png)
* [防抖与节流](./docs/images/perf/perf_th.png)
* [性能监测](./docs/images/perf/perf.png)
* [react 性能分析](https://react.css88.com/blog/2018/09/10/introducing-the-react-profiler.html#profiling-an-application)
* [前端性能优化清单](https://juejin.im/post/5a966bd16fb9a0635172a50a)
* [creeperyang/blog](https://github.com/creeperyang/blog/issues)
* [把前端监控做到极致](https://juejin.im/post/5a52f138f265da3e5b32a41b)
* [js-leakage-patterns](https://github.com/zhansingsong/js-leakage-patterns)
* [CS-Interview-Knowledge-Map](https://github.com/InterviewMap/CS-Interview-Knowledge-Map)

---

### redux-saga

* [Redux-Sage 中文文档](https://redux-saga-in-chinese.js.org/)
* [Redux-Saga 仓库实例精解](./docs/stories/saga/examples-saga.md) (废弃，没价值，大家自行看源码🤣)
* [坦克大战复刻版](https://zhuanlan.zhihu.com/p/35551654) 
* [SVG 图像入门教程](http://www.ruanyifeng.com/blog/2018/08/svg.html)
* [走进SVG](https://www.imooc.com/learn/143)
* [svg基础知识点](./docs/images/.png)
* [immutable入坑指南](http://www.aliued.com/?p=4175)
* [首屏场景组件 GameTitleScene 的分析](./docs/stories/battle-city/game-title-scene.md)
* [关卡选择场景组件 ChooseStageScene 的分析](./docs/stories/battle-city/choose-stage-scene.md)
* [游戏场景组件 GameScene 的分析](./docs/stories/battle-city/game-scene.md)
* [Iterator 和 for...of 循环](http://es6.ruanyifeng.com/#docs/iterator)
* [深入浅出 ES6（二）：迭代器和 for-of 循环](http://www.infoq.com/cn/articles/es6-in-depth-iterators-and-the-for-of-loop)
* [深入浅出 ES6（三）：生成器 Generators](http://www.infoq.com/cn/articles/es6-in-depth-generators)
* [redux-saga 实践总结](https://zhuanlan.zhihu.com/p/23012870)
* [浅析redux-saga实现原理](https://zhuanlan.zhihu.com/p/30098155)
* [从 Pub/Sub 浅聊 reudx-saga](./docs/stories/saga/pub-sub-saga.md)
* [Redux-Saga 漫谈](https://www.yuque.com/lovesueee/blog/redux-saga)
* [little-saga](https://github.com/little-saga/little-saga)
* [构建你自己的 redux-saga](https://github.com/little-saga/little-saga/blob/master/docs/building-your-own-redux-saga.md)一文：
* [构建你自己的 redux-saga 总结](./docs/stories/saga/build-saga.md)
* [Git 配置](./docs/images/mac/git/gitconfig.png)
* [CSSINJS](http://cssinjs.org)
* [漫谈 CSS in JS](https://zhuanlan.zhihu.com/p/31622439)

---

### webpack(脑图)

* [webpack可以做什么](./docs/images/webpack/1.png)
* [webpack基础配置](./docs/images/webpack/2.png)
* [webpack打包文件分析](./docs/images/webpack/3.png)
* [webpack之转化ES高级语法](./docs/images/webpack/4.png)
* [webpack处理js语法及校验](./docs/images/webpack/5.png)
* [webpack暴露全局变量](./docs/images/webpack/6.png)
* [webpack之Html插件](./docs/images/webpack/7.png)
* [webpack之样式处理](./docs/images/webpack/8.png)
* [webpack详细配置](./docs/images/webpack/9.png)
* [webpack优化](./docs/images/webpack/10.png)
    * tree-shaking 
    * scope hosting
    * splitChunks
    * noParse
    * webpack.IgnorePlugin
    * 懒加载
    * dllPlugin
    * happypack
    * 热更新
    * ...
* [Tapable](./docs/images/webpack/11.png)
* [实现一个简易的webpack](./docs/images/webpack/12.png)
* [写一个loader](./docs/images/webpack/13.png)
* [写一个plugin](./docs/images/webpack/14.png)

---

### NodeJS

<details>
  <summary>
    <b>NodeJs 是什么？</b>
  </summary>
  <ul>
    <li>Node.js is a `JavaScript runtime` built on Chrome's V8</li>
    <li>Node.js uses an event-driven, `non-blocking I/O` model</li>
  </ul>
</details>

<details>
  <summary>
    <b>非阻塞I/O</b>
  </summary>
  <ul>
    <li>阻塞：I/O 时进程休眠等待 I/O 完成后进行下一步</li>
    <li>非阻塞：I/O 时函数立即返回，进程不等待 I/O 完成</li>
    <li>I/O 操作非常慢</li>
  </ul>
</details>

<details>
  <summary>
    <b>事件驱动</b>
  </summary>
  <ul>
    <li>I/O 等异步操作结束后的通知</li>
    <li>观察者模式</li>
  </ul>
</details>

<details>
  <summary>
    <b>为什么偏爱 NodeJS</b>
  </summary>
  <ul>
    <li>前端职责范围变大，统一开发体验</li>
    <li>在处理高并发，I/O密集场景性能优势明显</li>
  </ul>
</details>

<details>
  <summary>
    <b>CPU 密集 VS I/O 密集</b>
  </summary>
  <ul>
    <li>CPU 密集：压缩，解压，加密，解密</li>
    <li>I/O 密集：文件操作，网络操作，数据库</li>
  </ul>
</details>

<details>
  <summary>
    <b>web 常见场景</b>
  </summary>
  <ul>
    <li>静态资源的读取</li>
    <li>数据库操作</li>
    <li>渲染页面</li>
  </ul>
</details>

<details>
  <summary>
    <b>高并发应对之道</b>
  </summary>
  <ul>
    <li>增加机器数(堆机器并不合算)</li>
    <li>增加每台机器的 CPU 数----多核</li>
  </ul>
</details>

<details>
  <summary>
    <b>进程</b>
  </summary>
  <ul>
    <li>进程（执行中的程序）：是计算机中的程序关于某数据集合上的一次运行活动，是系统进行资源分配和调度的基本单位</li>
    <li>多进程：启动多个进程，多个进程可以一块执行多个任务(CPU 调度算法快速的切换)</li>
  </ul>
</details>

<details>
  <summary>
    <b>NodeJS 工作模型</b>
  </summary>
  <ul>
    <li>Client --> EventLoop(single thred) --> Non-blocking Worker(internal C++ threadpool)</li>
    <li>一个 NodeJS 进程只开一个线程</li>
  </ul>
</details>

<details>
  <summary>
    <b>线程</b>
  </summary>
  <ul>
    <li>线程：进程内一个相对独立的，可调度的执行单元，与同属于一个进程的线程共享进程的资源</li>
    <li>多线程：启动一个进程，在一个进程内启动多个线程，这样，多个线程也可以一块执行多个任务（靠调度算法来做）</li>
  </ul>
</details>

<details>
  <summary>
    <b>NodeJS 的单线程</b>
  </summary>
  <ul>
    <li>单线程只是针对主进程，与I/O 操作系统底层多线程调度没啥关系</li>
    <li>单线程并不是单进程（用 cluster 模块，CPU 有几个核儿，我们就启几个进程）</li>
  </ul>
</details>

<details>
  <summary>
    <b>常用场景</b>
  </summary>
  <ul>
    <li>Web Server</li>
    <li>本地代码构建(性能不是最好，但对前端友好)</li>
    <li>实用工具开发(性能不是最好，但对前端友好)</li>
  </ul>
</details>

<details>
  <summary>
    <b>快速 Demo 演示</b>
  </summary>
  <ul>
    <li>VSCode + Code Runner</li>
  </ul>
</details>

#### CommonJS

包裹函数，不用自己写，NodeJS 帮我们弄好了

```js
(function(exports, require, module, __filename, __dirname){
    console.log('test.');
});
```

<details>
  <summary>
    <b>CommonJS 特性</b>
  </summary>
  <ul>
    <li>每个文件是一个模块，有自己的作用域</li>
    <li>在模块内部 module 变量代表模块本身</li>
    <li>module.exports 属性代表模块对外接口</li>
  </ul>
</details>

<details>
  <summary>
    <b>require 规则</b>
  </summary>
  <ul>
    <li>`/` 表示绝对路径，`./` 表示相对于当前文件的</li>
    <li>支持 js、json、node 拓展名，不写依次尝试</li>
    <li>不写路径则认为是 build-in 模块或者各级 node_modules 内的第三方模块</li>
  </ul>
</details>

<details>
  <summary>
    <b>require 特性</b>
  </summary>
  <ul>
    <li>module 被加载的时候执行，加载后缓存</li>
    <li>一旦出现某个模块被循环加载，就只输出已经执行的部分，还未执行的部分不会输出</li>
  </ul>
</details>

<details>
  <summary>
    <b>npm 常用命令</b>
  </summary>
  <ul>
    <li>npm root -g</li>
  </ul>
</details>

<details>
  <summary>
    <b>module.exports 与 exports 的区别</b>
  </summary>
  <ul>
    <li>exports 是 module.exports 的快捷方式</li>
  </ul>
</details>

<details>
  <summary>
    <b>global</b>
  </summary>
  <ul>
    <li>CommonJS</li>
    <li>Buffer、process、console</li>
    <li>timer</li>
  </ul>
</details>

<details>
  <summary>
    <b>process 对象</b>
  </summary>
  <ul>
    <li><a href="https://nodejs.org/dist/latest-v10.x/docs/api/process.html" target="_blank">文档</a></li>
  </ul>
</details>

---
### 优秀的 blog
* [Jony的博客，记录学习工作的点点滴滴](https://github.com/forthealllight/blog)
* [冴羽的博客](https://github.com/mqyqingfeng/Blog)
* [node-interview](https://github.com/ElemeFE/node-interview/tree/master/sections/zh-cn)
* [大话WEB开发](https://github.com/SFLAQiu/web-develop)
* [梁少峰的个人博客](https://github.com/youngwind/blog)

### 杂项
* [解决chrome提示"您的连接不是私密连接"问题](https://github.com/mrdulin/blog/issues/32)
```sh
openssl req -newkey rsa:2048 -x509 -nodes -keyout server.pem -new -out server.crt -subj /CN=dev.xx.com -reqexts SAN -extensions SAN -config <(cat /System/Library/OpenSSL/openssl.cnf <(printf '[SAN]\nsubjectAltName=DNS:dev.xx.com')) -sha256 -days 3650
```
* [Docker--Error message 'sudo: unable to resolve host <USER>'](https://askubuntu.com/questions/59458/error-message-sudo-unable-to-resolve-host-user)
* [如何绕过chrome的弹窗拦截机制](https://my.oschina.net/jsan/blog/1545859)
* 80
```sh
sudo lsof -n -P | grep :80
```

