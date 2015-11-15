oauth-for-qq-renren-sina
## 项目简介 ##
QQ，人人，新浪微博的OAuth认证demo

## 关于下载 ##
您可以直接在Downloads页面下载源码包
```
https://oauth-for-qq-renren-sina.googlecode.com/files/auth_demo.zip
```
也可以通过SVN同步下载源码
```
svn checkout http://oauth-for-qq-renren-sina.googlecode.com/svn/trunk/ oauth-for-qq-renren-sina-read-only
```
## 注意事项 ##
本Demo包含了QQ、人人、新浪微博的Oauth认证。

请将Demo中的appid及appkey更换成您申请的appid及appkey

将其中出现url更换成您的服务器所在地址



++++++++++++++++QQ连接部分++++++++++++++++

openqq/common/config.inc.php中出现的“xxxxxx”字样更换成您的appid、appkey、redirect\_url

++++++++++++++++++++++++++++++++++++++++++


++++++++++++++++人人连接部分++++++++++++++++

openrenren/common/config.inc.php中出现的“xxxxxx”字样更换成您的appid、appkey、app\_secretkey、redirect\_url

++++++++++++++++++++++++++++++++++++++++++++

++++++++++++++++新浪微博连接部分++++++++++++++++

opensina/success.php 中出现的“xxxxxx”字样更换成您的redirect\_url

opensina/common/config.inc.php中出现的“xxxxxx”字样更换成您的appkey、appsecret、redirect\_url

opensina/config.php中出现的“xxxxxx”字样更换成您的appkey、appsecret、redirect\_url

++++++++++++++++++++++++++++++++++++++++++




2012.03.28 17：39