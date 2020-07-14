### 李嘉豪

- Github: [Epson-Lee](https://github.com/EPSON-LEE)
- 手机： 13082529394
- 微信： 18829292287
- stack overflow: [superyipr](https://stackoverflow.com/users/12251494/superyipr)
- Email: leejiahao199506@gmail.com

### 教育背景

- 2013-9~2017-6：西安邮电大学 集成电路设计与集成系统

### Blog

- [博客 https://epson-lee.github.io/o/](https://epson-lee.github.io/o/)

### 技术能力

- 熟悉 JavaScript、HTML、CSS。
- 熟悉 float、 flex、 grid 等主流布局方案。
- 熟悉 Webpack、Roll up 打包工具的基本配置和 babel 编译工具。
- 熟悉常见的开源图表工具 Echarts、Highcharts。
- 熟练掌握 git pull rebase、git pull merge 协同开发模型。
- 掌握前端 （动静分离、静态预渲染、动态服务渲染）等主要架构实践，并有实践经验。
- 熟练使用 Koa 进行开发，熟悉前后端交互协议 HTTP、了解 RPC, 具有运维经验。
- 熟练使用 React、Vue 主流开发框架以及周边生态(Redux、Vuex、Mobx)、熟练使用 antd-design、element-ui、iview、vant-ui 等相关 UI 开发框架。

### 工作经验

- 2020.05 — 2020.06：**顺丰同城 供应链业务组 | 前端开发**

  > 负责 OMS 系统 2.0 的开发

- 2018.07 — 2020.05：**Keep 工程效率组 | 工程效率组前端业务负责人**

  > Keep 智能信息化办公平台

    - 主要职责：

      1. 包括 OA、OA 移动端、CRM、OMS、HRM、EAM、内测平台、门禁、基于 bpmn-js 的可视化流程引擎、会议室预定等内部系统的开发。

      2. 指导新人进行业务开发和知识分享，负责团队内部 code review、任务拆分、模块拆分、组件开发。

    - 项目关键点：

      1. 从零开始开发人力、财务、行政、业务方向合计三十多套表单、其中每个表单都包括保存草稿、变更、审批、详情、打印、导入、导出、权限管理八个功能点。在面对长流程、大量的表单联动场景和需求快速变更情况下保证了代码的模块化和较高的可维护性。

      2. 针对 HRM、EAM 做了微服务化集成。 Github:[micro-fronted-single-spa](https://github.com/EPSON-LEE/single-spa-demo)

      3. 项目中出复杂的表单交互较多，针对简单单层的表单服务沉淀出 [iview-json-schema-form](https://github.com/EPSON-LEE/vue-iview-form) 表单生成器。

      4. 沉淀出一些特定的复杂业务组件模块 （可编辑表格模块、固定列表筛选模块、递增嵌套表单模块等）
  
  > Keep 全链路运维平台开发

    - 项目背景：
      
      为了提升公司业务开发人员工作效率，整合公司使用的不同云厂商，以服务资源为纬度、基于公司组织架构进行个性化定制的全链路管理平台。

    - 主要职责：

      1. 各种服务资源的申请、审批、释放、扩容等操作界面的开发。

      2. 机器、集群、服务性能使用率的可视化报表的开发。

    - 项目关键点：

      平台设计思想基于百度 nuoya 运维平台，服务节点和机器、服务、集群以及相关指标需要进行笛卡尔积计算同时展现报表。在用户操作时很容易请求出几 M 的 json 数据，出现用户体验差、前端需要处理过于冗杂数据的情况，针对以上几点做了以下优化：

      1、BFF 层搭建，在服务层进行数据处理进行数据格式化，使用 vue-orm 进行全局状态的管理。

      2、针对几 M 的 json 数据理使用 web worker 进行处理，缩短页面卡顿时间。

      [博客：在前端项目中使用 vuex orm](https://epson-lee.github.io/o/2019/11/19/vuex-orm/)

  > Keep 前端基础架构建设

    1、配合架构组进行公司中台进行动静分离改造

    2、基于 iview-admin 的公司 PC 端脚手架的开发和维护提供给业务中台使用。设计 axios 封装、iview 集成。针对一定数据量下 Tree、Tab 组件中的卡顿进行了优化。

    3、开发 npm 包，统一化管理接口地址提升开发效率。

    4、配合架构组使用 Lerna 进行公司前端项目的插件化改造。

- 2017.06 — 2018.07：**福建网龙计算机网络信息技术有限公司 | 前端开发**

  - 独立开发：工程院信息化交付管理平台
  - 模块负责：教育部-陕西省教育厅学校管理平台
  - 参与开发：福建省教育信息统一化平台学情分析模块的开发

### 主要项目经验

> 福建省教育信息统一化平台

- 项目地址：http://fj.101.com/wjt/fj/index

- 项目介绍：该项目开发时间长、技术栈广而杂（从 angular1.x ~ react 0.14 主要负责其中学情分析模块

> 教育部-陕西省教育厅学校管理平台

- 项目介绍：项目涉及四十二个页面，每个页面都有几十个字段的表单

- 项目关键点：表单公共模块的抽象，系统表单复杂数据流管的管理。对表单组件进行二次开发，模块复用性提升开发效率。

> 工程院信息化交付管理系统

- 项目地址：http://rms-new.sdp.101.com/#/login

- 项目介绍：从无到有搭建公司工程院项管软件（包含任务看板、多层数据报表、绩效查看、业务进度可视化），设计了该页面的权限系统并进行技术选型、进行公共模块抽离、开发第三方组件。

- 项目关键点： 整个系统数据关联度大业务耦合严重，优化数据流结构针对不同模块数据流进行拆分，抽象出 （甘特图、富文本编辑器模块）
  - react 技术栈 、antd-design 组件、FrapeGantt 甘特图组件、rc-animate 动画组件
  - jsonServer 进行前后端分离


> 个人项目：一个尝鲜的管理系统（2018-03）

- Github 地址：https://github.com/EPSON-LEE/web-manage-system
- 项目介绍:
  - 使用最新版本、主要进行测试尝鲜
- 主要技术栈：
  - 使用 CSSS3 Grid 布局
  - webpack 4.1.0
  - 测试 React 模块中的各种模式并应用在项目中、eg: Hight-order Component
  - ReactV16 中的新特性、context、componengDidCatch、fiber
  - 一些有意思的 lib eg: Dan Abramov 的 React-dnd

> 个人项目：react-like（2019-05）

- Github 地址：https://github.com/EPSON-LEE/react-like
- 项目介绍:

  - 一个十分简易版的react 使用roll up打包

> 个人项目：从loader到代码分析vue（进行中）

- Github 地址：https://github.com/EPSON-LEE/practise

### 未来计划

> Web 方向：

- 在两份工作中都遇到了大量的表单联动场景、目前在调研根据json-schema处理表单需求的业务场景，近期一直在调研 [uform](https://github.com/alibaba/uform)

> 业余的规划

- 研发体系的建设包括 git、ci/cd、类似 phabricator、trallo 项目管理的私有化等研发体系的基础搭建。
