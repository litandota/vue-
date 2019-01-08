# vue-notes
用vue-cli搭建的vue项目，使用的ele ui 。在这里做笔记。

export 语法 
https://www.cnblogs.com/diligenceday/p/5503777.html

vue 路由钩子

1.全局钩子函数    router.beforeEach   router.afterEach
2.路由钩子函数    beforeEnter  beforeLeave
3.组件路由钩子函数   beforeRouteEnter   beforeRouteLeave
https://www.cnblogs.com/heioray/p/7193841.html



v-if v-show 区别
都能控制标签隐藏显示。
v-if 删除增加dom   v-show 只是在对应标签上增加display-none  dom还在


18年面试题
https://www.cnblogs.com/sichaoyun/p/8406194.html


vuex 用法
https://vuex.vuejs.org/zh/

webpack入门
https://www.jianshu.com/p/42e11515c10f


vue keep-alive 缓存机制使用
https://segmentfault.com/a/1190000008123035



>  vueAdmin-template 学习笔记

项目地址  https://github.com/PanJiaChen/vueAdmin-template.git
权限相关文档 https://juejin.im/post/591aa14f570c35006961acac



> 最近工作中遇到并解决的问题

https://segmentfault.com/q/1010000015946274?_ea=4144018



>坑
判断一个对象的属性是否存在时，
如果此属性的类型不确定时，千万不要写成类似if(obj1.open)这个样式
因为所判断的属性有可能是一个数值型的类型，如果出现value是0的情况，那就入坑了
最后推荐使用lodash


|              | DCloud                                                       | APICloud                                                     |
| :----------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 官网地址     | <http://www.dcloud.io/>                                      | <https://www.apicloud.com/>                                  |
| 开源时间     | 2014                                                         | 2013                                                         |
| 开源框架     | Html5+MUI                                                    | html+js+css+aui                                              |
| 框架目标     | 重新定义移动端开发、提供云、端两种服务                       | 重新定义移动端开发、提供云、端两种服务                       |
| 开发IDE      | HBuilder                                                     | apiCloud/webstrom/sublime/Eclipse                            |
| 核心开发模式 | 使用标准的HTML、CSS、JS + HTML5 Plus扩展API                  | 使用标准的HTML、CSS、JS + APICloud扩展API                    |
| 文档         | 文档详细程度一般                                             | 文档相对详细： 1.新手开发指南 2.视频教程 3.demo源码下载      |
| 费用         | 3000元，100个问题，2次主动优化建议，三个月有效期             |                                                              |
| 成熟度       | 很成熟                                                       | 很成熟                                                       |
| 学习成本     | DCloud 定位为打造大型互联网移动应用。 故而学习较高   一般在三到四周 | APICloud  因有较为详细的文档，定位为中小型移动应用。 学习成本较低  一般在一到两周 |
| 案例         | UniApp视频教程、随州便民网、课呱呱、小猪省钱卷、品悦商购、小情绪、考拉省钱、逛大街、云省购、菲佣直聘、蚂蚁宝充电     更多案例：<https://uniapp.dcloud.io/case> | 慢慢买、澳仕玛、遇见农场主、31秒拼、孝颜商城、抓试网、霆优商城、吱到、惠小白、幸福10号、日日顺快线司机、中田健身、幸福家经纪人、拨浪鼓回收、律动斌、鳗鱼、车轮派、农略   更多案例：<https://www.apicloud.com/cases> |
| 核心功能     | 双端推送服务 热更新 强制更新 文件浏览 二维码 语音输入 摇一摇 摄像头 文件系统 定位服务 | 双端推送服务 热更新 强制更新 文件浏览 二维码 语音输入 摇一摇 摄像头 文件系统 定位服务 |
|              |                                                              |                                                              |
|              |                                                              |                                                              |
|              |                                                              |                                                              |
