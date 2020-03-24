### 李嘉豪

- 在线简历地址： [https://github.com/EPSON-LEE/myResume](https://github.com/EPSON-LEE/myResume)
- Email: 491071291@qq.com
- 手机: 18695726397
- Github: [Epson-Lee](https://github.com/EPSON-LEE)
- stack overflow: [superyipr](https://stackoverflow.com/users/12251494/superyipr)

### 教育背景

- 2013-9~2017-6：西安邮电大学 集成电路设计与集成系统

### Blog

- [博客 https://epson-lee.github.io/o/](https://epson-lee.github.io/o/)
### 技术能力

- 熟练掌握 HTML5、CSS3、JavaScript
- 了解 CI/CD 开发思想,运用在自己的博客上
- 熟悉 Webpack、Roll up打包工具、具有前后端分离开发的经验
- 熟练掌握 git pull rebase flow 和 git pull merge flow
- 熟练掌握 Gerrit、 Phabricator arcanist 进行 codeReview
- 具有良好的调试能力、了解基本 linux 命令能使用 mac 独立开发、具备科学上网的能力
- 熟练使用 React、Vue 技术栈、ES6 进行开发、熟悉 antd-design、element-ui、iview、vant-ui
- 从做表单的场景扩展到了 FRP 的数据流开发，正在摸索如何将 rxjs 正在探索如何应用到业务中

### 工作经验
- 2018.07 — 今：**Keep EE  Group| 前端开发**

  - Keep 工程效率组，指导新人开发。 负责团队code review、任务拆分、模块拆分。
  - 负责 Keep 信息化办公平台的开发
  - 负责 Keep 运维平台开发
  - 负责 Keep 测试平台开发（全链路压测平台和业务线前后端代码质量报表）
  - 指导新人进行业务开发、知识分享
  - 调研前端工程化

- 2017.06 — 2018.07：**福建网龙计算机网络信息技术有限公司 | 前端开发**

  - 独立开发：工程院信息化交付管理平台
  - 模块负责：教育部-陕西省教育厅学校管理平台
  - 参与开发：福建省教育信息统一化平台学情分析模块的开发

### 主要项目经验

> Keep 智能信息化办公平台 (2018.07 - 今)

- 项目：
  - 线上项目：参与 Keep 2017 用户年度报告 H5 页面的开发。
  - 行政支持：Keep SSO、Keep 权限、Keep 流程引擎、Keep 流程引擎、Keep CRM、 Keep OA-SOP、Keep。
  - 人事管理：Keep 人力管理平台、 Keep 员工入职一体化方案。

- 技术栈：
  - vue + vuex + iview + Echarts

- 项目难点：
  - 负责平台下所有系统的开发、部署、上线、codeReview。
  - 来到 Keep 负责的第一个项目，面对新组人员不稳定、PM经验不足、需求不稳定的情况下保持了良好的适应能力。
  - 流程引擎：参与流程引擎的技术选型，基于 bpmn-js 进行定制化开发。可视化进行审批线的搭建，包含（审批、通过、拒绝、加签、转签、会签）六种操作模式。
  - 从零开始开发人力、财务、行政、业务方向攻击三十多套表单、其中每个表单都包括保存草稿、变更、审批、详情、打印、导入、导出、权限管理八个功能点。在面对长流程、大量的表单联动场景和需求快速变更情况下保证了代码的模块化和较高的可维护性。

- 沉淀和收获：
 - 沉淀出 [iview-json-schema-form](https://github.com/EPSON-LEE/vue-iview-form) 针对扁平没有数据交互的表单可以通过简单的 json 配置快速生成表单。
 - 跟踪业界先进的表单处理方案[formily](), 接触到了 FRP 的编程思想。

> 协助 Keep 架构组

- 项目介绍:

  - 负责协助架构组进行前端工程化建设，参与基于 iview-admin 的 web 脚手架的维护和开发。

- 沉淀和收获
  - 了解内部体系化建设的基础设施：SSO、cmsProxy、auth-jwt

> Keep 运维信息化闭环平台

- 项目介绍:
  - 以服务为出发点，来操作包括监控读写，报警添加，资源管理，流程处理，权限管理、费用计算等功能的 Paas 平台。
  
- 技术栈：
  - vue + vuex + iview + Echarts

- 项目难点：

  - 监控页面不属于传统的表单页面，包含了非常个性化的联动关系、交互逻辑复杂，接口不健全。接触到了 vuex-orm 处理复杂的数据关系。 输出到博客 [前端项目中使用 vuex orm](https://epson-lee.github.io/o/2019/11/19/vuex-orm/)
  - 由于设计问题，监控监控页面常常需要前端对一个 7m json 进行解析渲染出图。使用了 web worker 技术进行处理，从之前的页面卡死提升到不到 1s 出图。

- 沉淀和收获
  - 信息化平台从最初的一人发展到三人开发、不同模块其实可以拆出单独的应用, 基于 single-spa 搭建了一个微服务的项目，拆解出 base 应用 + 独立 app 的一个脚手架(包含样式隔离、开发时父子应用的开发模式)。github:[micro-fronted-single-spa-demo](https://github.com/EPSON-LEE/single-spa-demo)


> 福建省教育信息统一化平台

- 项目地址：http://fj.101.com/wjt/fj/index
- 项目介绍:
  - 该项目开发时间长、技术栈广而杂（从 angular1.x ~ react 0.14 主要负责其中学情分析模块七个页面
- 技术栈：
  - 项目开发人员
  - react 技术栈 、HighCharts
  - jsonServer 进行前后端分离

> 教育部-陕西省教育厅学校管理平台

- 项目地址：测试中
- 项目介绍:
  - 项目主要开发
  - 项目涉及四十二个页面，每个页面都有几十个字段的表单
  - 主要负责公共组件的抽取和相关页面开发
- 技术栈：
  - react 技术栈 、antd-design

> 工程院信息化交付管理系统

- 项目地址：http://rms-new.sdp.101.com/#/login
- 项目介绍:
  - 作为项目开发负责人，该项目目前为止开发了四个模块（开发计划、版本计划、资源池、绩效模块报表）共十六个页面，设计了该页面的权限系统并进行技术选型、 公共模块抽离、第三方库的封装
- 主要技术栈：
  - react 技术栈 、antd-design 组件、FrapeGantt 甘特图组件、rc-animate 动画组件
  - jsonServer 进行前后端分离


> 个人项目：General-lib（pending）

- Github 地址：https://github.com/EPSON-LEE/General-Lib
- 项目介绍:
  - 提升下自己手写 js 的能力
  - 模拟 js 中一些原生方法,eg:call、apply
  - 模仿 jQuery 中的一些方法
  - 模仿 underSource、lodash 中的一些方法

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

- 在两份工作中都遇到了大量的表单联动场景、目前在调研根据json-schema处理表单需求的业务场景，近期一直在调研[uform](https://github.com/alibaba/uform)

- 在前端工程化方面，根据[蚂蚁金服的前端框架和工程化实践](https://github.com/sorrycc/blog/issues/85?from=timeline&isappinstalled=0)思考，自己作为一个业务开发如何结合 electron + node 降低开发人员开发成本提升开发体验。

- 作为内部项目来讲、无论是用户量还是性能、稳定性要求都不是是很高、所以希望参与开发一个对外的项目中去，并且在保证业务稳定的同时能使用到更加先进的技术和工具。

> 未来的工作

- 能够接触到不限于 Web 端的丰富的前端开发形态，小程序、Hybrid App、Node，通过业务来驱动技术成长。
- 能跟踪业界的一些最新的思想，比如继 sass pass 后的 fass 开发方式、wasm。

> 自己业余的规划

- 研发体系的建设包括 git、ci/cd、类似 phabricator、trallo 项目管理的私有化等研发体系的基础搭建。
