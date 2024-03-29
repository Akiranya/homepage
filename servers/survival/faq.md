# 常见问题 & 解答

## 软妹币是什么 :id=ruanmeibi

`软妹币`是城镇生存服的虚拟货币。

玩家可以用软妹币与其他玩家进行交易/购买系统服务，也可用来创建城镇/圈地。

!> `软妹币`跟人民币没有任何关联。上古服不会用人民币出售任何游戏道具/权限等。

## 软妹币是怎么来的 :id=how-ruanmeibi-is-generated

这里只说明软妹币如何从"零"产生，不包括玩家间的交易。

当游戏刚开始时，游戏内的软妹币总和为零。随着玩家的各种活动，越来越多的软妹币陆续被产生。以下是软妹币产生的所有途径：

- 玩家初次加入游戏会赠送`1000`软。
- 玩家每日在线`30`分钟获得签到奖励`200`软。
- 玩家总在线时间超过一定时数可获得奖励：
  - 输入`/ptt`查看自己的在线时间。
  - 超过`10`小时获得`1000`软妹币+不死图腾，
  - 超过`20`小时获得`2500`软妹币+不死图腾，
  - 超过`30`小时获得`5000`软妹币+不死图腾，
  - 超过`40`小时获得`7500`软妹币+不死图腾，
  - 超过`50`小时获得`10000`软妹币+不死图腾，
- 参加服务器的大型活动，获得软妹币奖励。
- 向系统商店出售钻石（输入`/c`打开快捷菜单，里面有系统商店菜单）。
- ~~每当`城镇日`到来时，`城镇银行`和`居民`基于领地的数量会获得一笔城镇补贴。~~
- ~~挑战怪物竞技场（游戏中输入`/ma j`），坚持到特定波数之后会获得软妹币奖励。~~

## 怎么圈地 :id=land-claiming

在城镇生存服，创建城镇就相当于圈地。点[这里](/features/towny.md)查看创建城镇的方法。

## 怎么锁箱 :id=chest-protection

直接往箱子上贴木牌即可（不需要进入潜行状态）。

## 刷怪上限是怎样的

城镇生存服的怪物上限是「根据每个玩家独立计算」而不是「根据一个世界里的怪物总数」。

前者是服务端特别改进后的算法，后者是 Minecraft 原版的算法。

这意味着，同一个世界里，如果某个玩家周围有40只守卫者<small>（假设上限=40）</small>，那么在世界另一端的其他玩家周围仍然会正常的刷新出最多40只守卫者。某个玩家周围有大量的生物A，并不会导致其他玩家周围刷不出生物A。

这种改进过的刷怪上限算法可以让分布在地图各处的刷怪场同时正常运行。
