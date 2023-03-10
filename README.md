 Iot数据开放(小程序iframe h5移动端)
 =====
#### 项开发技术
 ```JS
  Vue.js全家桶+less+WeUi+postcss-px-to-viewport+better-scroll+lodash
Puppeteer+mock.js+whats-element+moment.js+echarts+jest+jscpd+fastclick
 ```
#### 项目介绍

 ` 数据开放面向商户对其大盘经营数据进行开放，为商户提供支付数据支持，帮助商户提升经营效率。为商户提供交易数据服务。包括每日的交易概览，如交易金额、笔数、顾客数的统计；新老顾客分布的用户构成情况；以及时段分布、笔单价区间分布等交易分布情况；也可按日、周、月查看多天的交易趋势；
主要模块有：交易分析日报、交易分析月报、活动分析、顾客分析、服务商日报、服务商月报。`

#### 项岗位职责
  - ##### 模块开发、维护:
    - 服务商月报（数据概览、趋势数据、交易详情、特约商户构成、特约商户地域构成)
    - 服务商日报（特约商户交易涨跌排行、特约商户交易趋势）
    - 无埋点监控接入，埋点上报
    
  - ##### 公共组件封装
    - 自定义日期选择器
    - 可视化容器、tabBar、
    - 列表懒加载容器
    - 自定义指令封装
  - ##### 封装SDK
    - 封装echart antv 
    - http、工具类、api、Mock服务搭建
  - ##### 测试
    - 编写测试用例、黑盒测试、编写单元测试、e2e测试 
  - ##### Git管理
    - CodeReview、分支管理、制定开源模式git规范
  
#### 项项目技术
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
#### 项目展示
![dataopen-1](https://user-images.githubusercontent.com/58834537/223069635-17f9ffbe-f5e3-4684-a66b-95ac1d3ec71b.png)
![dataopen6](https://user-images.githubusercontent.com/58834537/223072486-626eb823-48f2-44b7-af3b-f4cd34320ab3.png)
![dataopen4](https://user-images.githubusercontent.com/58834537/223070608-13098f4e-48fa-4dab-ae03-efa0751aff9a.png)
![dataopen8](https://user-images.githubusercontent.com/58834537/223072317-b2fd122a-3cd0-406e-bc92-8435504c3ac0.png)



