 Iot数据开放(h5移动端)
 =====
- 开发技术
 ```JS
  Vue.js全家桶+less+WeUi+postcss-px-to-viewport+better-scroll+lodash
Puppeteer+mock.js+whats-element+moment.js+echarts+jest+jscpd+fastclick
 ```
- 项目介绍

 > 数据开放面向商户对其大盘经营数据进行开放，为商户提供支付数据支持，帮助商户提升经营效率。为商户提供交易数据服务。包括每日的交易概览，如交易金额、笔数、顾客数的统计；新老顾客分布的用户构成情况；以及时段分布、笔单价区间分布等交易分布情况；也可按日、周、月查看多天的交易趋势；
主要模块有：交易分析日报、交易分析月报、活动分析、顾客分析、服务商日报、服务商月报。

- 岗位职责
  - 模块开发、维护:
  - 公共组件封装
  - 封装SDK
  - 测试
  - Git管理
  
- 项目技术
  - 使用 div+css+less+Weui编写静态页面,实现页面布局。
  - 使用 postcss-px-to-viewport适配各移动端适配。
  - 使用better-scroll做列表详情，以及多层嵌套滚动，解决移动端各种滚动场景。
  - 使用mock.js搭建本地Mock服务，对整个项目请求统一封装。
  - 使用WeUI+Weui.js将项目中公共功能、组件进行定制化开发。
  - 运用工厂模式设计思想使用TypeScript、echart、antv、webpack、less封装可视化SDK。
  - 使用jest编写单元测试，测试代码覆盖率。
  - 使用jest+puppeteer完成自动化测试。
  - 使用jscpd测试代码重复率，保证代码重复率。
  - 使用Vue-router+vuex实现动态路由权限分配。
  - 使用模块化、组件化、插件化思想对业务和工程进行分离，保证项目易维护、易迭代。
  - 使用keepAlive对个模块的分析板块进行动态缓存，http缓存，预加载，实现秒开提高用户体验。
