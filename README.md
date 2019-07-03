## 变量和类型

1.question: JavaScript规定了几种语言类型
answer: 在es6之前，规定了六种语言类型，分别是undefined,null,Boolean,String,Number,Object。在es6的时候，新加了Symbol。
undefined类型只有一个值undefined，它是变量未赋值时候的值，在JavaScript中全局对象有一个undefined属性表示undefined，事实上undefined并非JavaScript的关键字，可以给全局的undefined属性赋值来改变它的值。

2.question: JavaScript对象的底层数据结构是什么

3.question: Symbol类型在实际开发中的应用、可手动实现一个简单的Symbol

4.question: JavaScript中的变量在内存中的具体存储形式

5.question: 基本类型对应的内置对象，以及他们之间的装箱拆箱操作

6.question: 理解值类型和引用类型

7.question: null和undefined的区别

8.question: 至少可以说出三种判断JavaScript数据类型的方式，以及他们的优缺点，如何准确的判断数组

> 类型

9.question: 可能发生隐式类型转换的场景以及转换原则，应如何避免或巧妙应用

10.question: 出现小数精度丢失的原因，JavaScript可以存储的最大数字、最大安全数字，JavaScript处理大数字的方法、避免精度丢失的方法


## 原型和原型链

1.question: 理解原型设计模式以及JavaScript中的原型规则

2.question: instanceof的底层实现原理，手动实现一个instanceof

4.question: 实现继承的几种方式以及他们的优缺点

5.question: 至少说出一种开源项目(如Node)中应用原型继承的案例

6.question: 可以描述new一个对象的详细过程，手动实现一个new操作符

7.question: 理解es6 class构造以及继承的底层实现原理


## 作用域和闭包

1.question: 理解词法作用域和动态作用域

2.question: 理解JavaScript的作用域和作用域链

3.question: 理解JavaScript的执行上下文栈，可以应用堆栈信息快速定位问题

4.question: this的原理以及几种不同使用场景的取值

5.question: 闭包的实现原理和作用，可以列举几个开发中闭包的实际应用

6.question: 理解堆栈溢出和内存泄漏的原理，如何防止

7.question: 如何处理循环的异步操作

8.question: 理解模块化解决的实际问题，可列举几个模块化方案并理解其中原理

## 执行机制

1.question: 为何try里面放return，finally还会执行，理解其内部机制

2.question: JavaScript如何实现异步编程，可以详细描述EventLoop机制

3.question: 宏任务和微任务分别有哪些

4.question: 可以快速分析一个复杂的异步嵌套逻辑，并掌握分析方法

5.question: 使用Promise实现串行

6.question: Node与浏览器EventLoop的差异

7.question: 如何在保证页面运行流畅的情况下处理海量数据

## 语法和API

1.question: 理解ECMAScript和JavaScript的关系

2.question: 熟练运用es5、es6提供的语法规范，

3.question: 熟练掌握JavaScript提供的全局对象（例如Date、Math）、全局函数（例如decodeURI、isNaN）、全局属性（例如Infinity、undefined）

4.question: 熟练应用map、reduce、filter 等高阶函数解决问题

5.question: setInterval需要注意的点，使用settimeout实现setInterval

6.question: JavaScript提供的正则表达式API、可以使用正则表达式（邮箱校验、URL解析、去重等）解决常见问题

7.question: JavaScript异常处理的方式，统一的异常处理方案


## HTML和CSS

> HTML

1.question: 从规范的角度理解HTML，从分类和语义的角度使用标签

2.question: 常用页面标签的默认样式、自带属性、不同浏览器的差异、处理浏览器兼容问题的方式

3.question: 元信息类标签(head、title、meta)的使用目的和配置方法

4.question: HTML5离线缓存原理

5.question: 可以使用Canvas API、SVG等绘制高性能的动画

> CSS

1.question: CSS盒模型，在不同浏览器的差异

2.question: CSS所有选择器及其优先级、使用场景，哪些可以继承，如何运用at规则

3.question: CSS伪类和伪元素有哪些，它们的区别和实际应用

4.question: HTML文档流的排版规则，CSS几种定位的规则、定位参照物、对文档流的影响，如何选择最好的定位方式，雪碧图实现原理

5.question: 水平垂直居中的方案、可以实现6种以上并对比它们的优缺点

6.question: BFC实现原理，可以解决的问题，如何创建BFC

7.question: 可使用CSS函数复用代码，实现特殊效果

8.question: PostCSS、Sass、Less的异同，以及使用配置，至少掌握一种

9.question: CSS模块化方案、如何配置按需加载、如何防止CSS阻塞渲染

10.question: 熟练使用CSS实现常见动画，如渐变、移动、旋转、缩放等等

11.question: CSS浏览器兼容性写法，了解不同API在不同浏览器下的兼容性情况

12.question: 掌握一套完整的响应式布局方案

> 手写

1.question: 手写图片瀑布流效果

2.question: 使用CSS绘制几何图形（圆形、三角形、扇形、菱形等）

3.question: 使用纯CSS实现曲线运动（贝塞尔曲线）

4.question: 实现常用布局（三栏、圣杯、双飞翼、吸顶），可是说出多种方式并理解其优缺点

## 计算机基础

关于编译原理，不需要理解非常深入，但是最基本的原理和概念一定要懂，这对于学习一门编程语言非常重要

> 编译原理

1.question: 理解代码到底是什么，计算机如何将代码转换为可以运行的目标程序

2.question: 正则表达式的匹配原理和性能优化

3.question: 如何将JavaScript代码解析成抽象语法树(AST)

4.question: base64的编码原理

5.question: 几种进制的相互转换计算方法，在JavaScript中如何表示和转换

> 网络协议

1.question: 理解什么是协议，了解TCP/IP网络协议族的构成，每层协议在应用程序中发挥的作用

2.question: 三次握手和四次挥手详细原理，为什么要使用这种机制

3.question: 有哪些协议是可靠，TCP有哪些手段保证可靠交付

4.question: DNS的作用、DNS解析的详细过程，DNS优化原理

5.question: CDN的作用和原理

6.question: HTTP请求报文和响应报文的具体组成，能理解常见请求头的含义，有几种请求方式，区别是什么

7.question: HTTP所有状态码的具体含义，看到异常状态码能快速定位问题

8.question: HTTP1.1、HTTP2.0带来的改变

9.question: HTTPS的加密原理，如何开启HTTPS，如何劫持HTTPS请求

10.question: 理解WebSocket协议的底层原理、与HTTP的区别

> 设计模式

1.question: 熟练使用前端常用的设计模式编写代码，如单例模式、装饰器模式、代理模式等

2.question: 发布订阅模式和观察者模式的异同以及实际应用

3.question: 可以说出几种设计模式在开发中的实际应用，理解框架源码中对设计模式的应用

## 数据结构和算法

据我了解的大部分前端对这部分知识有些欠缺，甚至抵触，但是，如果突破更高的天花板，这部分知识是必不可少的，而且我亲身经历——非常有用！

> JavaScript编码能力

1.question: 多种方式实现数组去重、扁平化、对比优缺点

2.question: 多种方式实现深拷贝、对比优缺点

3.question: 手写函数柯里化工具函数、并理解其应用场景和优势

4.question: 手写防抖和节流工具函数、并理解其内部原理和应用场景

5.question: 实现一个sleep函数

> 手动实现前端轮子

1.question: 手动实现call、apply、bind

2.question: 手动实现符合Promise/A+规范的Promise、手动实现async await

3.question: 手写一个EventEmitter实现事件发布、订阅

4.question: 可以说出两种实现双向绑定的方案、可以手动实现

5.question: 手写JSON.stringify、JSON.parse

6.question: 手写一个模版引擎，并能解释其中原理

7.question: 手写懒加载、下拉刷新、上拉加载、预加载等效果

> 数据结构

1.question: 理解常见数据结构的特点，以及他们在不同场景下使用的优缺点

2.question: 理解数组、字符串的存储原理，并熟练应用他们解决问题

3.question: 理解二叉树、栈、队列、哈希表的基本结构和特点，并可以应用它解决问题

4.question: 了解图、堆的基本结构和使用场景

> 算法
1.question: 可计算一个算法的时间复杂度和空间复杂度，可估计业务逻辑代码的耗时和内存消耗

2.question: 至少理解五种排序算法的实现原理、应用场景、优缺点，可快速说出时间、空间复杂度

3.question: 了解递归和循环的优缺点、应用场景、并可在开发中熟练应用

4.question: 可应用回溯算法、贪心算法、分治算法、动态规划等解决复杂问题

5.question: 前端处理海量数据的算法方案

## 运行环境

我们需要理清语言和环境的关系：

ECMAScript描述了JavaScript语言的语法和基本对象规范
浏览器作为JavaScript的一种运行环境，为它提供了：文档对象模型（DOM），描述处理网页内容的方法和接口、浏览器对象模型（BOM），描述与浏览器进行交互的方法和接口

Node也是JavaScript的一种运行环境，为它提供了操作I/O、网络等API

> 浏览器API

1.question: 浏览器提供的符合W3C标准的DOM操作API、浏览器差异、兼容性

2.question: 浏览器提供的浏览器对象模型 (BOM)提供的所有全局API、浏览器差异、兼容性

3.question: 大量DOM操作、海量数据的性能优化(合并操作、Diff、requestAnimationFrame等)

4.question: 浏览器海量数据存储、操作性能优化

5.question: DOM事件流的具体实现机制、不同浏览器的差异、事件代理

6.question: 前端发起网络请求的几种方式及其底层实现、可以手写原生ajax、fetch、可以熟练使用第三方库

7.question: 浏览器的同源策略，如何避免同源策略，几种方式的异同点以及如何选型

8.question: 浏览器提供的几种存储机制、优缺点、开发中正确的选择

9.question: 浏览器跨标签通信

> 浏览器原理

1.question: 各浏览器使用的JavaScript引擎以及它们的异同点、如何在代码中进行区分

2.question: 请求数据到请求结束与服务器进行了几次交互

3.question: 可详细描述浏览器从输入URL到页面展现的详细过程

4.question: 浏览器解析HTML代码的原理，以及构建DOM树的流程

5.question: 浏览器如何解析CSS规则，并将其应用到DOM树上

6.question: 浏览器如何将解析好的带有样式的DOM树进行绘制

7.question: 浏览器的运行机制，如何配置资源异步同步加载

8.question: 浏览器回流与重绘的底层原理，引发原因，如何有效避免

9.question: 浏览器的垃圾回收机制，如何避免内存泄漏

10.question: 浏览器采用的缓存方案，如何选择和控制合适的缓存方案

> Node

1.question: 理解Node在应用程序中的作用，可以使用Node搭建前端运行环境、使用Node操作文件、操作数据库等等

2.question: 掌握一种Node开发框架，如Express，Express和Koa的区别

3.question: 熟练使用Node提供的API如Path、Http、Child Process等并理解其实现原理

4.question: Node的底层运行原理、和浏览器的异同

5.question: Node事件驱动、非阻塞机制的实现原理

## 框架和类库

轮子层出不穷，从原理上理解才是正道

> TypeScript

1.question: 理解泛型、接口等面向对象的相关概念，TypeScript对面向对象理念的实现

2.question: 理解使用TypeScript的好处，掌握TypeScript基础语法

3.question: TypeScript的规则检测原理

4.question: 可以在React、Vue等框架中使用TypeScript进行开发

> React

1.question: React和vue 选型和优缺点、核心架构的区别

2.question: React中setState的执行机制，如何有效的管理状态

3.question: React的事件底层实现机制

4.question: React的虚拟DOM和Diff算法的内部实现

5.question: React的Fiber工作原理，解决了什么问题

6.question: React Router和Vue Router的底层实现原理、动态加载实现原理

7.question: 可熟练应用React API、生命周期等，可应用HOC、render props、Hooks等高阶用法解决问题

8.question: 基于React的特性和原理，可以手动实现一个简单的React

> Vue

1.question: 熟练使用Vue的API、生命周期、钩子函数

2.question: MVVM框架设计理念

3.question: Vue双向绑定实现原理、Diff算法的内部实现

4.question: Vue的事件机制

5.question: 从template转换成真实DOM的实现机制

> 多端开发

1.question: 单页面应用（SPA）的原理和优缺点，掌握一种快速开发SPA的方案

2.question: 理解Viewport、em、rem的原理和用法，分辨率、px、ppi、dpi、dp的区别和实际应用

3.question: 移动端页面适配解决方案、不同机型适配方案

4.question: 掌握一种JavaScript移动客户端开发技术，如React Native：可以搭建React Native开发环境，熟练进行开发，可理解React Native的运作原理，不同端适配

5.question: 掌握一种JavaScript PC客户端开发技术，如Electron：可搭建Electron开发环境，熟练进行开发，可理解Electron的运作原理

6.question: 掌握一种小程序开发框架或原生小程序开发

7.question: 理解多端框架的内部实现原理，至少了解一个多端框架的使用

> 数据流管理

1.question: 掌握React和Vue传统的跨组件通信方案，对比采用数据流管理框架的异同

2.question: 熟练使用Redux管理数据流，并理解其实现原理，中间件实现原理

3.question: 熟练使用Mobx管理数据流，并理解其实现原理，相比Redux有什么优势

4.question: 熟练使用Vuex管理数据流，并理解其实现原理

5.question: 以上数据流方案的异同和优缺点，不情况下的技术选型

> 实用库

1.question: 至少掌握一种UI组件框架，如antd design，理解其设计理念、底层实现

2.question: 掌握一种图表绘制框架，如Echart，理解其设计理念、底层实现，可以自己实现图表

3.question: 掌握一种GIS开发框架，如百度地图API

4.question: 掌握一种可视化开发框架，如Three.js、D3

5.question: 工具函数库，如lodash、underscore、moment等，理解使用的工具类或工具函数的具体实现原理

> 开发和调试

1.question: 熟练使用各浏览器提供的调试工具

2.question: 熟练使用一种代理工具实现请求代理、抓包，如charls

3.question: 可以使用Android、IOS模拟器进行调试，并掌握一种真机调试方案

4.question: 了解Vue、React等框架调试工具的使用

## 前端工程

前端工程化：以工程化方法和工具提高开发生产效率、降低维护难度

> 项目构建

1.question: 理解npm、yarn依赖包管理的原理，两者的区别

2.question: 可以使用npm运行自定义脚本

3.question: 理解Babel、ESLint、webpack等工具在项目中承担的作用

4.question: ESLint规则检测原理，常用的ESLint配置

5.question: Babel的核心原理，可以自己编写一个Babel插件

6.question: 可以配置一种前端代码兼容方案，如Polyfill

7.question: Webpack的编译原理、构建流程、热更新原理，chunk、bundle和module的区别和应用

8.question: 可熟练配置已有的loaders和plugins解决问题，可以自己编写loaders和plugins

> nginx

1.question: 正向代理与反向代理的特点和实例

2.question: 可手动搭建一个简单的nginx服务器、

3.question: 熟练应用常用的nginx内置变量，掌握常用的匹配规则写法

4.question: 可以用nginx实现请求过滤、配置gzip、负载均衡等，并能解释其内部原理

> 开发提速

1.question: 熟练掌握一种接口管理、接口mock工具的使用，如yapi

2.question: 掌握一种高效的日志埋点方案，可快速使用日志查询工具定位线上问题

3.question: 理解TDD与BDD模式，至少会使用一种前端单元测试框架

> 版本控制

1.question: 理解Git的核心原理、工作流程、和SVN的区别

2.question: 熟练使用常规的Git命令、git rebase、git stash等进阶命令

3.question: 可以快速解决线上分支回滚、线上分支错误合并等复杂问题

> 持续集成

1.question: 理解CI/CD技术的意义，至少熟练掌握一种CI/CD工具的使用，如Jenkins

2.question: 可以独自完成架构设计、技术选型、环境搭建、全流程开发、部署上线等一套完整的开发流程（包括Web应用、移动客户端应用、PC客户端应用、小程序、H5等等）

## 项目和业务

> 后端技能

1.question: 了解后端的开发方式，在应用程序中的作用，至少会使用一种后端语言

2.question: 掌握数据最终在数据库中是如何落地存储的，能看懂表结构设计、表之间的关联，至少会使用一种数据库

> 性能优化

1.question: 了解前端性能衡量指标、性能监控要点，掌握一种前端性能监控方案

2.question: 了解常见的Web、App性能优化方案

3.question: SEO排名规则、SEO优化方案、前后端分离的SEO

4.question: SSR实现方案、优缺点、及其性能优化

5.question: Webpack的性能优化方案

6.question: Canvas性能优化方案

7.question: React、Vue等框架使用性能优化方案

> 前端安全

1.question: XSS攻击的原理、分类、具体案例，前端如何防御

2.question: CSRF攻击的原理、具体案例，前端如何防御

3.question: HTTP劫持、页面劫持的原理、防御措施

> 业务相关

1.question: 能理解所开发项目的整体业务形态、业务目标、业务架构，可以快速定位线上业务问题

2.question: 能理解所开发项目整体的技术架构、能快读的根据新需求进行开发规划、能快速根据业务报警、线上日志等定位并解决线上技术问题

3.question: 可以将自己的想法或新技术在业务中落地实践，尽量在团队中拥有一定的不可替代性
