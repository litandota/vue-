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
