[server-survival]: /welcome/servers.md#survival
[server-creative]: /welcome/servers.md#creative
[worlds-of-survival]: /welcome/worlds-of-survival.md#home

# 权限组

* 每个玩家至少属于一个权限组。
* 一个玩家可以同时属于多个权限组。
* 玩家所属的权限组决定他可以使用哪些指令、功能。
* 每个玩家都有 *平等* 的机会来获得某个权限组。
* 出于公平起见，*氪金* 不在获得途径之内。
* 玩家权限组在上古的所有子服务器之间同步。

!> 在处理纠纷、参与讨论时，权限组的高低不会影响管理组裁决。

> 该页面只介绍权限相关。要寻找相关指令，请参考左侧边栏中的[常用指令](/welcome/commands.md)和插件帮助📖。
>  
> 以及请善用左上角的搜索功能🔍

----

## ❄️初心者（默认） :id=def

> *“初来乍到的萌新们。”*

### 获得条件

新玩家的权限组默认为「初心者」，无需额外获得。

### 拥有权限

?> 权限列表按照 *服务端插件* 来介绍。

* [Essentials](/welcome/commands.md#ess) - 基础指令 *使用传送、修改昵称、接收/支付软妹币等*
* [NyaaUtils](/plugins/nu.md) - 小工具 *使用飞行动力、给物品改名、展示物品到聊天框等*
* [CraftBook](/plugins/craftbook.md) - 机械工程 *建造和使用电梯、城门，以及快速换画等*
* [MyPet](/plugins/mypet.md) - 宠物系统 *抓宠物、养宠物*
* [HamsterEcoHelper](/plugins/trade.md) - 仓鼠经济助手 *使用天喵商城、木牌商店、拍卖等*
* ~~Towny - 城镇系统 *创建城镇、圈地等*~~
* [CoreProtect](/plugins/logblock.md) - 记录查询 *查询游戏世界中的事件记录*
* [Lockette](/welcome/commands.md#lock) - 牌子锁 *给箱子上锁*
* [MultiVerse](/welcome/commands.md#mv) - 多世界 *查看各个世界的玩家*
* *该列表可能不完善，有待补充……*

----

## 🧙‍冒险家·Adventurer :id=adv

> *“我不再是萌新啦！”*

### 获得条件

[初心者](#def)在[生存服][server-survival]在线总时长超过`1`小时后会自动升级为「冒险家」。

### 拥有权限

与初心者一致。

----

## 👨‍🏭工匠·Crafter :id=crafter

> *“独具匠心者”。*

### 获得条件

如果在[建筑比赛](games/build.md)中完成了作品，但未能成功晋级[建筑师](#arch)，那么参赛选手可以获得此权限组。

### 拥有权限

* 继承[初心者](#def)的权限
* 可以在[城镇领地](/plugins/towny.md)里飞行
* 修改当前世界的天气（在[创造服][server-creative]）

----

## 👷‍建筑师·Architect :id=arch

> *“对建筑的细致观察与理解”。*

建筑师是拥有较高建筑审美与建造能力的玩家，需要负责公共设施建设和配合管理组的工作。~~建筑师拥有飞行权限，但仅限用于方便建造，不可用于其他用途。滥用权限的行为将会导致丢失建筑师称号。~~

### 获得条件

自 *2019年2月18日* 起，建筑师的获得途径变为参加[建筑比赛](games/build.md)并晋级。

### 拥有权限

* 继承[工匠](#crafter)的权限
* 使用[盔甲架编辑器](../plugins/ast.md)（在[创造服][server-creative]）

----

## 👨‍🎨设计师·Designer :id=designer

> *“徒手撸个伊甸园不是什么大问题”。*

设计师是由建筑师提升、被管理组认可、拥有高度建筑审美与建造/设计能力的玩家。在遵守建筑师的原则上，设计师往往能够快速响应管理组的企划，规划庞大的建筑群，设计游戏（场地），并且具有较好的领导能力，能够带领其他建筑师完成目标建筑。特定情况下，设计师应协助管理组进行 `WorldEdit` 操作。

### 获得条件

综合在论坛、企鹅群、游戏内的活跃度与建筑创作成果，~~由管理组钦定~~。

### 拥有权限

* 继承[建筑师](#arch)的权限
* ~~立即更新[卫星地图](http://map.mimaru.me:8123)~~
* 无视所有~~领地~~和保护区的保护
* 开启飞行模式（在[生存服的家园世界][worlds-of-survival]）
* 使用地图编辑器 `WorldEdit`（在[创造服][server-creative]）

----

## 💗贡献者·Sponsor :id=sponsor

> “感谢所有玩家为上古所做的每一份贡献。”

### 获得条件

💕[捐助我们](/sponsor.md)

### 拥有权限

与[初心者](#def)一致。

----

## 👮‍♀️风纪委·Judgement :id=judgemt

「风纪委」属于服务器管理组的一部分，负责响应玩家的举报，处理玩家间的纠纷。

<!-- 🎁[参与贡献](/sponsor.md) -->

----

## 🎭统括领事·OP :id=op

「统括领事」属于服务器的决策层（也就是~~幕后黑手~~），主要负责技术开发和重大决策。

<!-- 🎁[参与贡献](/sponsor.md) -->

----

## 前缀优先级·Priority :id=priority

> 玩家可以拥有多个权限组，但只会显示优先级最高的前缀。

比如玩家同时属于「建筑师」和「贡献者」这两个权限组，那么只会显示「贡献者」的前缀，因为「贡献者」的前缀优先级比「建筑师」组要高。「建筑师」前缀会被隐藏，但玩家会拥有对应的权限。

| 权限组/前缀 | 优先级 |
| ----------- | ------ |
| 初心者      | 13     |
| 冒险家      | 14     |
| 工匠        | 15     |
| 建筑师      | 16     |
| 设计师      | 17     |
| 贡献I       | 20     |
| 贡献II      | 21     |
| 贡献III     | 22     |
| 风纪委      | 30     |
| 统括领事    | 100    |