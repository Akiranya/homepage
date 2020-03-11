# 管理员手册

!> 本页面尚未完成。

## 指令 :id=cmds

?> 一些较为简单的管理指令将直接写在这里。

编辑中...

## 插件教程 :id=tuts

?> 如果指令用法较为复杂，将单独写在这里，供大家参考。

<!-- tabs:start -->

#### **CO**

原版服使用的记录查询插件。

主要了解`lookup`，`rollback`和`restore`的用法就可以了，具体见[官方说明](http://minerealm.com/community/viewtopic.php?f=32&t=6781)。

#### **PR**

模组服使用的记录查询插件。详见插件作者的[官方说明](https://github.com/prism/Prism)。

#### **WG**

保护区插件。

- 创建/删除保护区
- 给保护区添加成员
- 修改 flags
- 重新确定保护区的位置

#### **WE**

地图编辑器插件。详细用法参考[MinePlugin 百科](http://mineplugin.org/WorldEdit)。

#### **ESS**

基础指令。包含常用指令用法如`/mute`、`/kick`、`/ban`、`/item`（需要细说，补偿物品会用到）。

#### **自定义村民**

自定义村民交易。创建/编辑村民商店的方法[看这里](https://github.com/Shopkeepers/Shopkeepers-Wiki/wiki/Creating-Shops)。

#### **悬浮文字**

创建/编辑/调整悬浮文字。

#### **违禁品管理**

违禁品管理插件。该插件只能在模组服使用。基本用法：把 *要禁用的物品* 放入一个 *Minecraft 原版的箱子* 里，然后 *主手* 用 *打火石*<kbd>Shift</kbd><kbd>鼠标右键</kbd>箱子，即可把物品禁用。要确认物品已被禁用，输入`/banneditems`。确认好后，箱子就可以拆掉了。注意，以上方法对于已经被禁用的物品，会自动跳过。如果箱子是大箱子，则需要用打火石分别<kbd>Shift</kbd><kbd>鼠标右键</kbd>左右两个小箱子。

<!-- tabs:end -->

## 流程规范

<!-- tabs:start -->

#### **建筑比赛**

从公开比赛题目，到比赛结束、裁判评分的完整流程。

#### **物品补偿**

规范从玩家申请物品补偿到玩家收到物品补偿之间的流程。

#### **刷新资源世界**

说明如何安全的刷新生存服的资源世界。

<!-- tabs:end -->

## 风纪委 :id=judgments

大概列出风纪委应该做哪些事，不该做哪些事。

## 技术概览 :id=arch

?> 这里主要从技术层面简单介绍维护游戏服务端的基础操作。

<!-- tabs:start -->

#### **网络架构**

省略一千字...

#### **服务端**

这里列出了上古时代可能会用到的所有种类的服务端 *官网*。关于如何下载服务端、启动服务端、调试服务端，以及服务端的相关配置文件说明，请参考下方各服务端的官网。

- [Paper](https://paper.readthedocs.io/en/stable/)
- [Spigot](https://www.spigotmc.org/)
- [Sponge](https://www.spongepowered.org/)

#### **寻找插件**

W.I.P.

#### **挑选地图**

W.I.P.

<!-- tabs:end -->
