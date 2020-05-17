---
title: 写一个npm插件
date: 2020-05-17 13:20:38
tags:
---
`vue`按需引入`toast`需要单独配置，`vue-cli2`和`vue-cli3`配置还不一样；
所以写个基于vue工程使用的`toast`插件，类似`mint-ui`的`Toast`
- 安装
```
npm install my-showtoast --save
```
- 引入
```
import showToast from 'my-showtoast';
Vue.use(showToast)
```
- 使用
```
this.$showToast.show('hello2020!')
this.$showToast.hide()
```

![my-showtoast.png](https://upload-images.jianshu.io/upload_images/13511312-3dda2ef6371a12f1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
