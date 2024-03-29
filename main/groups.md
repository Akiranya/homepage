[server-survival]: /servers/survival.md
[server-creative]: /servers/creative.md
[worlds-of-survival]: /servers/survival.md#home

# 权限组 {docsify-ignore-all}

- 玩家所属的权限组决定他可以使用哪些指令、功能。
- 每个玩家都有平等的机会来获得某个权限组。
- 玩家权限组在上古的所有服务器之间同步。
- 一个玩家可以同时属于多个权限组。

> [!warning|label:公平游戏]
> 在处理纠纷、参与讨论时，权限组的高低不会影响管理组裁决。

## 所有权限组

<!-- tabs:start -->

#### **初心者**

**获得条件**

新玩家的权限组默认为`初心者`，无需再获得。

**拥有权限**

`初心者`可以使用服务器里绝大多数的指令/功能。

#### **冒险家**

**获得条件**

`初心者`在[城镇生存服][server-survival]在线总时长超过`1`小时后会自动升级为`冒险家`。

**拥有权限**

与`初心者`一致。

#### **米团**

**获得条件**

向服务器捐助资金即可获得，详见[捐助我们](/sponsor.md)。

**拥有权限**

详细的额外权限请在游戏输入`/c`点击左上角**米团菜单**查看。

#### **工匠**

**获得条件**

如果在[建筑比赛](games/build.md)中完成了作品，但未能成功晋级`建筑师`，那么参赛选手有机会获得工匠。

**拥有权限**

- 继承`初心者`的所有权限
- 可以在[城镇领地](/features/towny.md)里飞行（俗称`城镇飞行`）
- 修改当前世界的天气（在[自由创造服][server-creative]）

#### **建筑师**

?> `建筑师`是拥有较高建筑审美与建造能力的玩家。应积极参与服务器公共设施的建设。

**获得条件**

`建筑师`的获得途径为参加[建筑比赛](games/build.md)并晋级。

**拥有权限**

- 继承`工匠`的所有权限
- 在[自由创造服][server-creative]使用`WorldEdit`
- 使用[盔甲架编辑器](/features/ast.md)（在[自由创造服][server-creative]）

#### **设计师**

?> `设计师`是由`建筑师`提升、拥有高度建筑审美与建造/设计能力的玩家。在遵守`建筑师`的原则上，`设计师`往往能够快速响应服务器的企划，规划庞大的建筑群，设计游戏（场地），并且具有较好的领导能力，能够带领其他`建筑师`完成目标建筑。

**获得条件**

综合在论坛、企鹅群、游戏内的活跃度与建筑创作成果。也有机会从建筑比赛中诞生。

**拥有权限**

- 继承`建筑师`的所有权限
- 使用`城镇飞行`不受领地限制（可在任何地方飞行）
- ~~拥有所有保护区的所有权限（例如主城保护区）~~

#### **贡献者**

?> `贡献者`是为服务器有过重大贡献的玩家。贡献包括但不限于资金支持、制作视频、撰写主页等。

**获得条件**

*自2021年7月25日起，服务器正式决定不再产生新的贡献者。原先的所有贡献者以及权限保留。*

**拥有权限**

根据所做的贡献大小，`贡献者`分为三个等级：

1. 贡献I
2. 贡献II
3. 贡献III

其中`贡献I`和`贡献II`的权限与`初心者`一致。`贡献III`继承前者所有权限，并且可以`城镇飞行`。

#### **风纪委**

?> `风纪委`属于服务器管理组的一部分，负责响应玩家的举报，处理玩家间的纠纷。

#### **OP**

?> `OP`负责服务器内的插件维护、配置，以及部分游戏内容的制作。

<!-- tabs:end -->

## 特殊权限组

**特殊权限组**没有绝对统一的升级途径。一般是在特殊的事件中获得特殊权限组。

<!-- tabs:start -->

#### **破壁者**

破壁者的由来是因为当时上古服从离线（盗版）服务器转换成了正版服务器后，出现了正版玩家无法打开之前自己盗版游戏角色下的牌子锁。为了能够快速响应玩家的“拆锁”要求，故设立了**破壁者**权限组。

**拥有权限**

拥有牌子锁的管理权限，可以打开已上锁的箱子，也可以拆除牌子锁。

#### **主持人**

即**建筑比赛主持人**，是专门管理建筑比赛的开始/结束的权限组。也有权限提拔玩家，详见[技术指南](/staff/build-battle/tech-spec.md)。

#### **风纪委长**

**风纪委**当中的元老级人物，负责监督和引导新的/现有的所有风纪委。

拥有更高级的管理权限，如使用[记录查询](/features/logblock.md)的回档指令`/co rollback(rb)`。

<!-- tabs:end -->

## 前缀优先级 :id=priority

玩家可以拥有多个权限组，默认会显示优先级最高的前缀。

如果玩家想展示其他前缀，可以在个人菜单（`/w`）中自行选择。
