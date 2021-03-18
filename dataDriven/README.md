# 1.vue初始化时做了什么
  1.1. initMixin：初始化_init方法
  1.2. stateMixin：定义$data与$props属性，定义$set,$delete,$watch方法
  1.3. eventsMixin:定义$on，$once，$off，$emit方法
  1.4. lifecycleMixin：定义_update，$forceUpdate，$destroy方法
  1.5. renderMixin：定义$nextTick，_render方法，在vue.prototype上添加一些方法
  1.6. new Vue发生了什么
    合并options
    初始化生命周期 initLifecycle
# 2.数据是怎样渲染到页面的
# 3.数据的变化是怎样实时更新到页面的