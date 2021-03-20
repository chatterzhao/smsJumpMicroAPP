# smsJumpToMicroAPP

#### 介绍
短信等非微信环境通过链接跳转微信小程序

#### 如何使用
- 登录自己的小程序后台：mp.weixin.qq.com，点击右上角的工具-生成 Url Schema，替换index.html页面中的 let schema = "替换为小程序管理平台生成的 Url Schema" 后面的值
- 将index.html部署到自己的网站服务器，然后把网址当短信发出即可
- 短信按字数收费，所以自己再想办法把网址短化一下，比如可以使用这个平台：https://4m.cn/

#### 项目使用
- clone 到本地
- 替换 Url Schema
- 上传到网站服务器，推荐码云的pages，切换到show 分支，点右上角的【服务】-【Gitee Pages】把网站发布，勾选强制Https，复制网站网址，使用短网址平台把网址短化一下（短信按字数收费），可以使用百度https://dwz.cn/，或https://4m.cn/进行短化，然后在短信里使用即可