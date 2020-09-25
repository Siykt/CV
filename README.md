# 个人简历

> 此为工作与项目经历汇总
>
> 工作经历使用时间正序记载, 项目汇总使用时间倒叙记载

## 项目汇总

### 微查宝 微信/百度/今日头条 小程序开发

所属公司: 杭州微查宝网络科技有限公司

项目角色: H5 主程

项目链接: <img src="https://img.weichabao.com/weapp/qrcode.jpeg" alt="二维码" style="width: 75px;" />

项目需求是将原网站功能迁移至小程序端, 但原网站使用技术较为古老, 所以业务逻辑部分基本还是重写

小程序这里由于需要完成多平台小程序的开发，选择使用框架而非原生, 其中我选择了 React 系的 Taro 框架

主要负责:

1. 完成页面开发, 完成业务需求

2. 编写交互式组件, 及其相关文档

3. 接入小程序中的微信支付, 百度与字节跳动端小程序中同时接入支付宝支付

4. 编写更新日志, 部署项目上线

5. 调整 iOS 平台差异

项目收获:

1. 熟悉 React 体系各项工具集合

2. 更加了解项目要求快速上线时, 对项目组件/业务逻辑开发的时长把控(敏捷式开发): 先易后难, 避免开发重复轮子, 时刻注意后端相关接口进度, 避免等待接口开发。

3. 了解到小程序开发与 Web 开发的不同之处

---

### 微查宝 Chrome 插件开发

所属公司: 杭州微查宝网络科技有限公司

项目角色: H5 主程

项目链接: <https://www.weichabao.com/download/ext>

项目需求是对于淘宝千牛后台数据的采集附带一些原网站查询功能, 其中采集功能由于 Chrome Extensions 权限限制问题, 采用的是 _循环查询 DOM_ 的采集模式。

此项目没有提供相关的数据样本, 导致项目前期核心功能搁置, 后采用对页面全面式抓取再进行相关的数据分析, 最后确定所需信息的定位元素完成核心功能的开发。

虽然支持 Chrome Extensions API 的浏览器大部分为现代浏览器, 无需处理低版本浏览器不兼容最新 API 的问题, 但在此环境中更易存在适配的盲点。

浏览器插件市场的要求也各不相同, 不能仅仅 build 一个 CRX 文件, 为适配各个市场的要求, 使用 Shell + node.js build 各个不同内容的市场包文件

主要负责:

1. 完成核心功能的开发

2. 完成动态插入广告功能

3. 适配浏览器插件市场完成多市场包 build 功能

4. 完成各类追加功能的开发

项目收获:

1. 熟悉 Chrome Extensions API

2. 熟悉 Webpack hooks API

3. 熟悉数据抓取需要考虑到的各类问题

---

### RICH PAPA 系统管理后台

所属公司: 杭州微查宝网络科技有限公司

项目角色: H5 主程

项目链接: <http://admin.richpapa88.com/rich-papa-admin-7553>

RICH PAPA 系统管理后台主要是对 APP 用户的审核、维护和管理。

由于人手不足(仅我一人), 周期吃紧, 选择使用由 Vue + Element-ui 技术栈开发的 Vue Element Admin 进行快速开发

权限系统将原本的 RBAC0 模式扩展为 RBAC3 模式

优化 Mobile 端展示效果

主要负责:

1. 完成功能模块的开发

2. 完成相关接口数据的设计

3. 完成权限系统的扩展

项目收获:

1. 了解后台 OS 开发的注意事项

2. 了解权限系统 RBAC 模式原理与实现

3. 了解 Vuex 与 ElementUI 组件

---

### RICH PAPA Web Socket 服务器

所属公司: 杭州微查宝网络科技有限公司

项目角色: Node.js 主程

项目链接: -

实现基础消息通讯功能的 Socket 服务器, 主要技术栈为 Node.js + Socket.io + Redis

主要负责:

1. 完成服务端的 Socket 消息通讯服务的开发

2. 设计合理的消息交互逻辑

项目收获:

1. 了解 Socket 从零开始的设计思路

2. 了解合理的消息交互逻辑的设计思路

---

### 魔镜直播官网开发

所属公司: 福州大航家文化传媒有限公司

项目角色: H5 主程

项目链接: <http://www.mj-liveapp.com/> - <http://m.mj-liveapp.com/>

完成网官网的双端开发, 非自适应模式

主要负责:

1. 负责 PC 端的开发, 需求适配至 IE9

2. 负责 Mobile 端开发, 需求适配各类主流手机

3. 接入支付宝/微信 js 支付

项目收获:

1. 了解 IE9 环境适配内容与适配方式

2. 了解主流移动端分辨率的适配

---

## 工作经历

### 福州大唐传易网络科技有限公司

> 梦开始的地方

工作时期: _2018-01_ 至 _2018-10_

部门职位: _web 前端_

做为 **搜索引擎排名优化(SEO)** 外包公司，一般也需要负责建站。

与通常的建站外包公司不同，我们更加在乎网⻚页面的布局与标签、类名语义化。一般业务逻辑不多，主要使用 **bootstrap** + **jQuery** 快速开发，要求效率、快速上线。

所以受开发周期的影响，我对于 **模块化开发**、**Sass mixin(css 预处理器)** 以及 模板重用等技术都有较为熟悉的经验。

其中主要使用的技术栈为:

1. SEO 语义化布局

2. 静态页面渲染

3. 应用 Sass/Scss 开发⻚页面样式

4. 熟悉 ES5 导出导入与 ES6 语法

相关技能标签:

[TwitterBootstrap](https://getbootstrap.com/) - [jQuery](http://jquery.com/) - [SEO](https://en.wikipedia.org/wiki/Search_engine_optimization) - [Sass/Scss](https://sass-lang.com/)

---

### 带你飞（福州）科技有限公司

工作时期: _2018-10_ 至 _2019-01_

部门职位: _web 前端_

主要负责移动端 App 的开发项目, 趋于多端打包平台的大热, 使用 H5 相关技术进行开发.

其前端首选框架为 **Cordova** 与 **AngularJs(Angular1)**, 后端使用的是 **ASP.net**, 也是我首次接触使用 **C#** 的后端工程师

其中主要使用的技术栈为:

1. 熟悉手机端适配，此次主要使用 rem 与 flex 布局方式。

2. 语音功能操作，利用 Cordova 框架封装的 API 调用原生的录音及播放功能实现语音的录制及播放。

3. 使用 jQuery.ajax 进行页面的异步操作。

4. 熟悉使用 AngularJS 的各类 API。

相关技能标签:

[AngularJs](https://angularjs.org/) - [Cordova](https://cordova.apache.org/)

---

### 福州大航家文化传媒有限公司

> 二次开发要求阅读文档、了解架构、API 接口熟悉、重构源码，以及与其他技术领域前端协助配合开发。

工作时期: _2019-01_ 至 _2019-10_

部门职位: _web 前端_

参与直播平台 App 二次开发项目，该项目是基于 ThinkPHP5.2 框架开发的**混合型 App 应用**。

同时负责其中 H5 的活动页面、小游戏、官网的开发, 协助完成高并发 I/O 处理。

维护由 **Node.js** + **Socket.io** 构建的消息服务器。

其中主要使用的技术栈为:

1. 基于 Socket.io 框架完成服务端的即时通讯功能，主要运用于直播间与游戏。

2. 基于 Vue.js 开发客户端活动页面。

3. 构建 Node.js 服务器协助完成高并发异步 I/O 处理。

4. 熟悉 Webpack 工具链以提升开发效率及其性能。

5. 熟悉 PHP 及 TP5.2 框架以协同后端完成部分功能的开发。

相关技能标签:

[Node.js](https://nodejs.org/) - [Socket.io](https://socket.io/) - [Vue](http://vuejs.org/) - [Webpack](https://www.webpackjs.com/) - [PHP/ThinkPHP](https://www.kancloud.cn/manual/thinkphp5)

---

### 杭州蜂华崛起网络科技有限公司

工作时期: _2019-10_ 至 _2020-02_

部门职位: _H5 开发工程师_

> 主要项目皆面向国外市场，需要做好 **i18N** 的相关适配

参与自研发聊天类 App 的后台开发, 与 Socket 服务器搭建。

聊天类软件要求保持长链接的稳定，**Socket.io** 库能满足第一版本需求。

项目周期较长，而后端开发人员较少，需要 Mock 服务器以便前端人员快速开发，所以也同时负责了搭建 Mock 服务器与接口文档的编写。

由于公司缘由，其中穿插境外电商与社交服务平台搭建，不过皆未完成。

其中主要使用的技术栈为:

1. 使用 Socket.io 搭建第一版的即时通讯服务器。

2. 使用 Node.js + Mock.js 开发 Mock 服务器

3. 使用 Vue.js + ElementUI + Vuex 完成管理后台 OS 的开发。

相关技能标签:

[Socket.io](https://socket.io/) - [Vue](http://vuejs.org/) - [ElementUI](https://element.eleme.io/) - [Vuex](https://vuex.vuejs.org/) - [Sass/Scss](https://sass-lang.com/)

---

### 杭州微查宝网络科技有限公司

工作时期: _2020-03_ 至今

部门职位: _H5 开发工程师_

> 目前在职的工作，学习机会较多

主要负责 微信/百度/今日头条 **小程序** 与 **Chrome 插件** 的自研发。

小程序这里由于需要完成多平台小程序的开发，选择使用框架而非原生。而虽然 Vue 使用较多，但还是选择了项目更易与维护的 **Typescript** + **React** 的相关小程序框架 **Tarojs** 。

Chrome 插件为第一次接触翻阅不少文档与资料，同时需要压缩插件包体积，选择使用 **Webpack** + **Typescript** 开发，自实现 DOM 模板引擎。(基于 **vnode** )。

其中穿插不少官网的更新，以及一些推广页面的开发。

其中主要使用的技术栈为:

1. 使用 Tarojs + Typescript + React + Redux + Stylus 完成小程序的开发

2. 使用 Webpack + Typescript 构建 Chrome Extensions 工程项目。

3. 熟悉 Chrome Extensions Api

4. 使用 Snabbdom vnode 实现 DOM 模板引擎。

相关技能标签:

[React](https://facebook.github.io/react/) - [Typescript](https://www.typescriptlang.org/) - [Redux](https://www.redux.org.cn/) - [Tarojs](https://taro-docs.jd.com/) - [Webpack](https://www.webpackjs.com/) - [ChromeExtensionsApi](https://developer.chrome.com/extensions/api_index) - [Snabbdom](https://github.com/snabbdom/) - [Stylus](https://www.stylus.com/)
