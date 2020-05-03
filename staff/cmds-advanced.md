# 进阶使用指南

?> 需要「背景知识」才知道怎么用的指令/插件会写在这里。

!> 请注意本页面仍在施工中。

以下每个插件都包含了**官方/非官方资料**。有条件的话可以直接看官方资料（往往更佳全面）不用等这个页面更新。

## 记录查询 CO :id=co

原版服（非模组服）都在使用的[记录查询](/plugins/logblock.md)插件。

了解指令`lookup`，`rollback`和`restore`的用法就足够啦。

- [官方说明 - 作者的教程帖](http://minerealm.com/community/viewtopic.php?f=32&t=6781)
- [MinePlugin](http://mineplugin.org/CoreProtect)

## 记录查询 PR :id=pr

[探索模组服](/mod)使用的记录查询插件。

[官方说明 - GitHub 仓库](https://github.com/prism/Prism)

## 保护区 WG :id=wg

保护区插件，简单来说是一个给管理员使用的领地插件。

了解以下功能就足以应付大多数情况：

- 创建/删除保护区
- 给保护区添加成员
- 修改 flags
- 重新确定保护区的位置
- 保护区的优先级

[官方百科 - 保护区的创建](https://worldguard.enginehub.org/en/latest/regions/)

## 创世神 WE :id=we

再熟悉不过的游戏内地图编辑器了，也叫“WE”、“创世神”。

- [MinePlugin](http://mineplugin.org/WorldEdit)
- [官方百科 - 全部用法](https://worldedit.enginehub.org/en/latest/usage/)
- [视频教程 by MaxKim](https://www.bilibili.com/video/av1379382/)

## 基础指令 ESS :id=ess

Ess 这个插件的第一个用处就是提供最基础的指令，大家常用的`tp`，`home`等都是 Ess 的功能。除此之外，常用的功能还有自定义新手礼包（初次进服务器所给予的物品），修改 MOTD（进服时看到的提示信息），设置服务器级别的重生点，自定义聊天样式等等。所有功能都可在`{plugin_dir}/Essentials/config.yml`里找到。

*TO-DO* 写上如何用 Ess 刷出特定的物品以用来**补偿特定物品**或**制作活动奖励**。

- `/enchant` - 用来给物品附魔
- `/item` - 用来产生指定物品

[官方百科 - Ess 的所有指令列表](https://essinfo.xeya.me/commands.html)

## 村民商店 ShopKeepers :id=shopkeepers

让你可以随意编辑村民的交易公式。

城镇生存服的**建材兑换商店**、**玩家村民商店**就是该插件的实际应用。

[官方百科 - 如何创建村民商店](https://github.com/Shopkeepers/Shopkeepers-Wiki/wiki/Creating-Shops)

## 悬浮文字 HD :id=hd

创建/编辑/调整悬浮文字。

[官方说明 - 如何创建/移动/删除悬浮文字](https://filoghost.me/docs/holographic-displays/basics)

## 物品管理 MMCRestrict :id=mmcrestrict

违禁品管理插件，用来控制特定物品的使用权限。该插件只能在`模组服`使用。

基本用法：

1. 把`要禁用的物品`放如一个`原版箱子`
2. `主手`用`打火石`<kbd>Shift</kbd><kbd>鼠标右键</kbd>箱子，即可把物品禁用
3. 要确认物品已被禁用，输入`/banneditems`
4. 确认好后，箱子就可以拆掉了（或留在原地作为违禁品展示）

以上方法对于已经被禁用的物品，会自动跳过。所以你不用担心会重复添加。

如果箱子是大箱子，则需要用打火石分别<kbd>Shift</kbd><kbd>鼠标右键</kbd>左右两个小箱子。

[官方说明 - 插件发布页](https://ore.spongepowered.org/leelawd93/MMCRestrict)

## 多世界管理 MV :id=mv

多世界管理（简称 MV）支持快速添加/删除世界。还可以编辑单个世界的游戏设定，如PVP，游戏模式。

[官方说明 - GitHub 仓库](https://github.com/Multiverse/Multiverse-Core/wiki)

*施工中……*

## 边界管理 WB :id=wb

边界管理（简称 WB）可以给世界创建边界，限制玩家走出边界。此边界管理比原版的更加强大，例如支持设置圆形边界。另一个主要用途是**事先填充好边界内的所有区块**，以加快世界的加载速度和防止生成区块带来的服务器卡顿。

*施工中……*

[官方说明 - Spigot 发布页](https://www.spigotmc.org/resources/worldborder.60905/)