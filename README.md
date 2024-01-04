# 我的世界 Nukkit 核心权限节点 (Nukkit Permission ID)
> **这里列出了Nukkit核心的命令权限节点**  
> **建议搭配[LuckPerms权限组插件](https://githubfast.com/LuckPerms/LuckPerms)记得下载[Nukkit](https://luckperms.net/download)分支**  
> **普通玩家的权限一般是不用给予的**  
> **[点击这里查看具体信息](https://githubfast.com/CloudburstMC/Nukkit/blob/master/src/main/java/cn/nukkit/permission/DefaultPermissions.java)**  
> **如果有问题或疑问请发`issue` 以便我能判断问题所在**
## 普通玩家权限
|权限节点|描述|
|-|-|
|```nukkit.broadcast.user```|允许玩家接收玩家广播|
|```nukkit.command.me```|让玩家聊天做出指定操作|
|```nukkit.command.help```|获取命令帮助|
|```nukkit.command.kill.self```|允许玩家自杀|
|```nukkit.command.version```|获得服务器版本信息|
|```nukkit.command.tell```|允许玩家私下向其他玩家发送消息|
## 管理员玩家权限
|权限节点|描述|备注|
|-|-|-|
|```nukkit.command.ban```|执行封禁相关的命令||
|```nukkit.command.ban.player```|封禁玩家||
|```nukkit.command.ban.ip```|封禁ip||
|```nukkit.command.ban.list```|查看封禁列表||
|```nukkit.command.unban```|执行解封相关的命令||
|```nukkit.command.unban.player```|解封玩家||
|```nukkit.command.unban.ip```|解封ip||
|```nukkit.command.gamemode```|切换游戏模式||
|```nukkit.command.gamemode.survival```|切换游戏模式为生存模式(对自己有效)||
|```nukkit.command.gamemode.creative```|切换游戏模式为创造模式(对自己有效)||
|```nukkit.command.gamemode.adventure```|切换游戏模式为冒险模式(对自己有效)||
|```nukkit.command.gamemode.spectator```|切换游戏模式为观察者模式(对自己有效)||
|```nukkit.command.gamemode.other```|切换其他玩家的游戏模式||
|```nukkit.command.time```|更改游戏时间||
|```nukkit.command.time.add```|添加游戏时间||
|```nukkit.command.time.set```|设置游戏时间||
|```nukkit.command.time.start```|启动时间流逝||
|```nukkit.command.time.stop```|停止时间流逝||
|```nukkit.command.time.query```|查询时间||
|```nukkit.command.save```|保存世界||
|```nukkit.command.save.enable```|启用自动保存世界||
|```nukkit.command.save.disable```|关闭自动保存世界||
|```nukkit.command.save.perform```|手动保存世界||
|```nukkit.command.op```|允许玩家改动op权限||
|```nukkit.command.op.give```|允许玩家给予另一个玩家op权限||
|```nukkit.command.op.take```|允许玩家撤销另一个玩家op权限||
|```nukkit.command.whitelist```|白名单命令||
|```nukkit.command.whitelist.add```|添加白名单||
|```nukkit.command.whitelist.remove```|移除白名单||
|```nukkit.command.whitelist.reload```|重载白名单||
|```nukkit.command.whitelist.enabl```|启用白名单||
|```nukkit.command.whitelist.disable```|关闭白名单||
|```nukkit.command.whitelist.list```|查看白名单中的玩家||
|```nukkit.broadcast.admin```|允许玩家接收管理广播||
|```nukkit.command.say```|允许玩家作为控制台讲话||
|```nukkit.command.give```|允许玩家给予自己或其他玩家物品||
|```nukkit.command.effect```|允许玩家使用药水效果||
|```nukkit.command.particle```|允许玩家创建粒子效果||
|```nukkit.command.teleport```|允许玩家传送玩家||
|```nukkit.command.kick```|允许玩家踢玩家||
|```nukkit.command.stop```|允许玩家停止服务器||
|```nukkit.command.list```|查看在线的玩家||
|```nukkit.command.plugins```|查看服务器插件加载情况||
|```nukkit.command.reload```|重新加载服务器配置和插件||
|```nukkit.command.defaultgamemode```|更改默认游戏模式||
|```nukkit.command.seed```|查看地图(世界)的种子||
|```nukkit.command.status```|查看服务器运行状态||
|```nukkit.command.gc```|清理无用数据||
|```nukkit.command.dumpmemory```|允许用户转储内存内容|这个在代码中以备注释掉了|
|```nukkit.command.gamerule```|设置或查询游戏规则值||
|```nukkit.command.timings```|允许玩家记录所有插件事件的计时||
|```nukkit.command.title```|允许玩家向玩家发送标题||
|```nukkit.command.spawnpoint```|允许文件更改更改自己或他人的出生点||
|```nukkit.command.setworldspawn```|允许用户更改世界出生点||
|```nukkit.command.weather```|允许玩家更改天气||
|```nukkit.command.xp```|允许玩家添加经验||
|```nukkit.command.enchant```|允许玩家为物品添加附魔效果||
|```nukkit.command.difficulty```|允许玩家更改难度||
|```nukkit.command.debug.perform```|允许玩家使用debugpaste命令||
|```nukkit.textcolor```|允许玩家编写彩色文本||
