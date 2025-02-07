# 我的世界 Nukkit 核心权限节点 (Nukkit Permission ID)
## **前言**
1. **这里列出了[Nukkit](https://github.com/CloudburstMC/Nukkit/blob/master/src/main/java/cn/nukkit/permission/DefaultPermissions.java)核心的命令权限节点**  
2. **建议搭配[LuckPerms权限组插件](https://github.com/LuckPerms/LuckPerms)记得下载`Nukkit`分支的[LuckPerms](https://luckperms.net/download)**  
3. **普通玩家的权限是默认拥有的，不需要给予即可使用的** 
4. **如果有问题或疑问请发[issue](https://github.com/stevei5mc/Nukkit_Permission/issues)以便我能判断问题所在**  
5. **如果有错误或遗漏您可以为本内容提供[PR](https://github.com/stevei5mc/Nukkit_Permission/pulls)来修复问题**
## 权限类型
- **[普通玩家权限](./player.md)**
### **管理员玩家权限**
- **[封禁与解封权限](./admin/ban_and_unban.md)**
- **[游戏模式权限](./admin/gamemode.md)**
- **[游戏时间权限](./admin/time.md)**
- **[保存世界的权限](./admin/save_world_and_op.md#保存世界的权限)**
- **[添加和撤销OP权限](./admin/save_world_and_op.md#添加和撤销op权限)**
- **[击杀命令权限](./admin/save_world_and_op_and_kill.md#击杀命令权限)**
- **[服务器白名单的权限](./admin/whitelist.md)**
- **其余权限**

|权限节点|描述|备注|
|:-:|:-:|:-:|
|nukkit.broadcast.admin|允许玩家接收管理广播||
|nukkit.command.say|允许玩家作为控制台讲话||
|nukkit.command.give|允许玩家给予自己或其他玩家物品||
|nukkit.command.effect|允许玩家使用药水效果||
|nukkit.command.particle|允许玩家创建粒子效果||
|nukkit.command.teleport|允许玩家传送玩家||
|nukkit.command.kick|允许玩家踢玩家||
|nukkit.command.stop|允许玩家停止服务器||
|nukkit.command.list|查看在线的玩家||
|nukkit.command.plugins|查看服务器插件加载情况||
|nukkit.command.reload|重新加载服务器配置和插件||
|nukkit.command.defaultgamemode|更改默认游戏模式||
|nukkit.command.seed|查看地图(世界)的种子||
|nukkit.command.status|查看服务器运行状态||
|nukkit.command.gc|清理无用数据||
|nukkit.command.dumpmemory|允许用户转储内存内容|这个在代码中以备注释掉了|
|nukkit.command.gamerule|设置或查询游戏规则值||
|nukkit.command.timings|允许玩家记录所有插件事件的计时||
|nukkit.command.title|允许玩家向玩家发送标题||
|nukkit.command.spawnpoint|允许文件更改更改自己或他人的出生点||
|nukkit.command.setworldspawn|允许用户更改世界出生点||
|nukkit.command.weather|允许玩家更改天气||
|nukkit.command.xp|允许玩家添加经验||
|nukkit.command.enchant|允许玩家为物品添加附魔效果||
|nukkit.command.difficulty|允许玩家更改难度||
|nukkit.command.debug.perform|允许玩家使用debugpaste命令||
|nukkit.command.clear|允许玩家清理背包物品|[NK PR# 2172](https://github.com/CloudburstMC/Nukkit/pull/2172)|
|nukkit.textcolor|允许玩家编写彩色文本||