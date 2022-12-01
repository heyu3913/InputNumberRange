# input-number-range


#### tips：更多定制化需求请联系: 1310217042@qq.com / vx:iverson96i


## 背景：

在开发时遇到一个数字区间输入框的需求，项目使用的是vue，组件库用的是element UI，但是element UI并没有提供数字区间组件，只提供了InputNumber 计数器输入框，如果用两个计数器输入框进行拼接也能满足需求，但是样式调试起来太过于复杂且不够灵活，不能令人满意，并且该数字区间输入框在其它界面也有这种需求，于是就在element input输入框的基础上自行封装了一个数字区间组件使用。

## Demo地址：
https://heyu3913.github.io/InputNumberRange/dist/index


## 使用方式：

```javascript
npm下载：
  npm i input-number-range -S
项目中引用：
  import InputNumberRange from 'InputNumberRange'
组件中使用(记得注册)
<InputNumberRange ></InputNumberRange> (具体可看项目中App.vue)
``` 

## 参数说明：

| 参数    | 说明 | 类型 | 可选值 |  默认值 | 是否必选
| ------ | ------ | ------ |  ------ |  ------ |------ |
| v-model | 选中项绑定值     | array | - | - |是
| disabled | 是否禁用 | boolean | - | false |否
| precision | 属性控制精度 | number | - | 0 |


## 事件说明：

| 事件名称    | 说明 | 回调参数 | 
| ------ | ------ | ------ | 
| blurfrom    | fromInput框失焦    | event| 
| focusfrom    | fromInput聚焦    | event| 
| blurto    | toInput框失焦    | event| 
| focusto    | toInput框聚焦    | event| 
| inputfrom    | fromInput框输入    | 输入的值| 
| inputto    | toInput框输入    | 输入的值| 
