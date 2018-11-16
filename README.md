# Vue相关-
不一定对，只是个人学习一点理解一点的记录，建议别看


----------------------------------------------------------------------------------------
  1.class 内部用空格隔开代表一次性应用多个不同的css样式
  2.<router-link to="../a">等于 <a href="../a"></a>
  3.$router.push({path:'../a'}) 等同于 <router-link to="../a">
  4.$router.replace({path:'../a'}) 和$router.push({path:'../a'}) 区别和Android的fragment里的replace和add差不多，一个是覆盖，一个是添加
  5.$router.push({path:'../a'})里可以加入replace:true 的属性，效果和直接用$router.replace({path:'../a'})一样
  6.export default{} 效果等同 new Vue({})，但是一般全局初始化Vue的时候才new Vue({})
  7.引入第三方的组件可以采用 import{组件名} form '来源名',单一可以不用{}
  8.引入时使用驼峰命名法，AoB 等同于 ao-b ，使用的时候统一 <ao-b>，不可用<AoB> 
  9.v-for 等同于java的foreach(itemType item: items),形式为v-for(item in items),使用后效果为自动遍历并产生复数个自身所写在的位置的控件
  10.export default{name:..} name 在这里作用和new Vue({ el:..})的el完全不一样
  11.加载js文件和其他文件都可以用require(),一般情况下和直接用url一样
  12.mounted相当于activity里的 onCreate，生命周期里就一次，可以理解为界面刚刚出来的时候，和onCreate差不多，可以做数据初始化和网络请求这块了
  13.components 就是模板，可以自定义，也可以放入第三方提供的组件
  14.pull-to api参考 https://github.com/stackjie/vue-pull-to/blob/master/README.zh-CN.md
  
