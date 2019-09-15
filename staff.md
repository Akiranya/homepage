# 管理员小屋

!> Working in progress.

?> 该页面是为了普及参与服务器贡献所需要的知识与技能。

*参与服务器贡献所需要的知识与技能* 大概分为 *技术* 和 *管理* 两方面，包括但不限于：风纪委行为准则、OP行为准则，以及管理员指令、活动流程规范、事件处理规范，还有服务器后台的操作说明。对于有意愿参与服务器贡献的玩家，可以提前学习该页面的知识与技能。

## ⚙️指令·Commands

?> 一些较为简单的管理指令将直接写在 *指令·Commands* 下面。

相关链接：[邮箱](plugins/nu.md#mail)

- `/nu mailbox create [Player ID]` Create mailbox for specified player.
- `/nu mailbox remove [Player ID]` Remove mailbox for specified player.
- `/nu mailbox info [Player ID]` Check mailbox information for specified player.

WIP.

## 📖插件教程·Tutorials

?> 如果指令用法较为复杂，将单独写在 *插件教程·Tutorials* 下面，供大家参考。

### WorldGuard

WIP. 保护区插件。

- [ ] 创建/删除保护区
- [ ] 给保护区添加成员
- [ ] 修改 flags
- [ ] 重新确定保护区的位置

### WorldEdit

WIP. 地图编辑器。

### Essentails

WIP. 基础指令。包含常用指令用法如`/mute`、`/kick`、`/ban`、`/item`（需要细说，补偿物品会用到）

### 自定义头颅

WIP.

### ShopKeepers

WIP. 自定义村民交易。

### NPC

WIP. 创建属于自己的NPC。

### 悬浮文字

WIP. 创建/编辑/调整悬浮文字。

## 📝流程规范·Workflows

### 建筑比赛

WIP. 从公开比赛题目，到比赛结束、裁判评分的完整流程。

### 物品补偿

WIP. 规范从玩家申请物品补偿到玩家收到物品补偿之间的流程。

### 刷新资源世界

WIP. 说明如何安全的刷新生存服的资源世界。

## 👮风纪委·Judgements

### 该做的事

需要规范风纪委应该做哪些事，不该做哪些事。风纪委不应该跨越职权。

WIP.

## 🧩技术概览·Architecture

?> 这里主要从技术层面简单介绍我们游戏服务器的网络结构和游戏服务端的基础操作。

### 网络架构

目前游戏服务器运行于阿里云的ECS主机上。为了可以根据需求灵活部署服务器，我们的游戏服务器被分成了前端与后端。前端服务器暴露于公网之下，上面运行了 BungeeCord、生存服、创造服。后端服务器未接入公网，但玩家可以通过前端服务器的 BungeeCord 转发来加入后端服务器。后端服务器主要运行短期或临时开放的服务端，如小游戏服务端、模组服务端等。后端服务器可以灵活的上线和离线，以快速满足当前的需求。

简而言之，前端服务器的配置与部署保持稳定不变，后端服务器灵活部署与调整。

因此如果要新增一台短期使用的服务器，例如开放三个月的游戏服、模组服等，应该购买一台 *不接入公网* 的ECS服务器，但 *必须* 和前端服务器处在同一地区、同一[VPC](https://help.aliyun.com/product/27706.html)网络。

### 服务端

这里列出了上古时代可能会用到的所有种类的服务端 *官网*。关于如何下载服务端、启动服务端、调试服务端，以及服务端的相关配置文件说明，请参考下方各服务端的官网。

- [Paper](https://paper.readthedocs.io/en/stable/)
- [Spigot](https://www.spigotmc.org/)
- [Sponge](https://www.spongepowered.org/)

### 寻找插件

WIP.

### 挑选地图

WIP.
