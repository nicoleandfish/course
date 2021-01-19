微信小程序开发和传统网页开发的区别
运行环境|逻辑层|渲染层
---|---|---
iOS|JavaScriptCore|WKWebView
安卓|V8|chromium定制内核
小程序开发者工具|NWJS|Chrome WebView


申请小程序账号
https://mp.weixin.qq.com/wxopen/waregister?action=step1

下载开发者工具
https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html

小程序代码构成
.json-JSON配置文件
JSON是一种数据格式，在小程序中，JSON扮演的静态配置的角色。app.json是当前小程序的全局配置，包括了小程序的所有页面路径、界面表现、网络超时时间、底部tab等。
.wxml-WXML模版文件 ---HTML ----用于控制页面的结构

.wxss-WXSS样式文件 ---CSS  ----用于控制页面的样式

.js---JS脚本逻辑文件---JS   ----用于处理页面的交互
