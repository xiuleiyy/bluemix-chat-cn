千寻聊天室 qx-chat
=======

这是一个使用node.js socket.io以及Bootstrap构建的一个聊天室。

This chat room is constructed by node.js socket.io and Bootstrap.

构建方法
--------

 1. 在源代码目录执行npm install
 2. 将配置信息写入环境变量`QXCHAT_CONFIG`中
 3. 在源代码目录执行npm start

ok,你的聊天室可以访问了~!


配置信息示例

```json

{
	"mysql" : {
		"host" : "localhost",
		"port" : "3306",
		"username" : "username",
		"password" : "password",
		"db_name" : "db_name"
	}
}
```
    