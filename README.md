# 使用说明

基于 [tspbbot-for-rq](https://github.com/protobufbot/js-pbbot) 的GroupAdminForRQ

## 指令说明

`.jin[QQ] [时间]`

禁言用户[QQ]，其中[QQ]可以为QQ号，也可以@某人，时间支持参数有s、 m 、h 和 d ，当[时间]为0时，解除禁言。

极端示例

`.jin@机姐小仝 1天2天2d3day4分钟5m6min7秒钟8秒9s10`

`.t[QQ]`

踢出用户[QQ]，其中[QQ]可以为QQ号，也可以@某人,小写t踢人可以再加群

`.T[QQ]`

踢出用户[QQ]，其中[QQ]可以为QQ号，也可以@某人,大写T踢人只能通过邀请进群

## 所需环境

[nodejs](https://nodejs.org/)

推荐安装版本: LTS (长期支持版)

## 运行方法

1. 下载源码并解压，然后进入解压目录

2. 执行`npm install`自动安装依赖（只有首次运行需要）

3. 执行`npm run start`开始运行消息处理器

运行 [pbrq](https://github.com/ProtobufBot/pbrq/releases) ，登陆机器人QQ
