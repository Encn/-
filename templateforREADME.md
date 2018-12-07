
## miniProgram_tianjin

A mini program project for tianjin.

## 项目目录

    ├───images                    图片资源
    ├───pages                       页面
    │   ├───end
    │   ├───feedBack
    │   ├───home
    │   ├───login
    │   └───register
    └───utils                         工具箱
    
    ├───app.json                 全局页面配置，包括页面路由pages, 底部tabbar跳转等
    
    ├───project.config.json      项目配置文件 
    

## 使用说明

    使用原生小程序组件开发；
    首先注册小程序账号并下载开发者工具；其次域名信息需要合法的，配置到小程序账号后台。如果不合法，在上传体验版本时手机上无法访问；
    但在开发这工具上可以实现本地接口联调，需要找到“设置”-“项目设置”，然后选中该项：不校验合法域名、web-view（业务域名）、TLS 版本以及 HTTPS 证书即可。
    
    每个页面都由四部分组成：
    如：
    login: 
    login.js   js文件
    login.json 页面相关配置， 比如头部导航的背景色，字体颜色，窗口的背景色等
    login.wxml 页面结构， 小程序特有的标签，如view, block等，
    login.wxss 页面样式， 单位rpx, 设计图应是750的标准
    

## 表单验证插件

使用文档 

For a detailed explanation on how things work, check out the  docs for developing mini program.




