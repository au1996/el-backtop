# el-backtop

一个基于 vue2.x 版本的回到顶部组件，API 跟 element-ui 保持一致。

## 引入 el-backtop

在 main.js 中写入以下内容：

```js
import Vue from "vue";
import ElBacktop from "el-backtop";

Vue.use(ElBacktop);
```

在 vue 文件中使用：

```html
<template>
  <div>
    <el-backtop></el-backtop>
  </div>
</template>
```

| 参数              | 说明                             | 类型   | 默认值                   |
| :---------------- | :------------------------------- | :----- | :----------------------- |
| target            | 触发滚动的对象                   | string | document.documentElement |
| visibility-height | 滚动高度达到此参数值才出现       | number | 200                      |
| right             | 控制其显示位置, 距离页面右边距   | number | 40                       |
| bottom            | 控制其显示位置, 距离页面底部距离 | number | 40                       |

[API 文档](https://element.eleme.cn/2.15/#/zh-CN/component/backtop)
