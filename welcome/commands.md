[creative]: /mc-servers/vanilla.md#creative
[modded]: /mc-servers/modded.md

# 常用指令

!> Working in progress.

<!-- ?> 下面指令将按照 *所属插件* 来排列。 -->

?> 输入`/c`打开 *快捷菜单*。

?> 指令说明后面带有[创造服][creative]和[模组服][modded]的意思是 *只能* 在给定的服务器使用。

## 上古网络·Wf :id=wf

- `/glist` 查看所有服务器的在线玩家
- `/server` 查看服务器列表
- `/server [服务器名字]` 连接到指定服务器
  - `服务器名字`必须使用`/server`中列出的

## 基础插件·Ess :id=ess

- 传送
  - `/back` 回到最近一次的死亡/传送点
  - `/tp <玩家名>` 传送到指定玩家身边*（创造服）*
  - `/tpa <玩家名>` 请求传送到他人身边
  - `/tpahere <玩家名>` 请求他人传送到自己身边
  - `/tppos <x> <y> <z>` 传送到当前世界的指定坐标*（创造服）*
  - `/top` 传送到当前位置的最顶层*（创造服）*
  - `/tptoggle` 是否允许其他玩家传送到自己身边
  - `/sethome` 设置脚底位置为家
  - `/home` 传送回家
  - `/delhome` 删除家的传送点
  - `/sethome [名字]` 使用 *不同名字* 最多可以设置`24`个家*（创造服）*
    - `[名字]`只能是英文+数字的组合，且只能以字母开头。
    - 例如要在三个不同的地方设置三个家，那么可以`/sethome food`、`/sethome hole3`、`/sethome tree`
    - 然后你可以使用`/home [名字]`传送回指定的家，例如`/home food`
    - 要删除家使用`/delhome [名字]`
  - `/warp [传送点名字]` 传送到固定地点
- 聊天
  - `/nick <昵称>` 修改昵称，支持[颜色代码](/plugins/chatutil.md)
  - `/helpop <信息>` 向 *在线* 管理员发送消息来请求帮助
  - `/ignore <玩家名>` 屏蔽指定玩家，同样的指令再输入一次可解除屏蔽
  - `/ignore` 查看自己屏蔽了哪些人
- 经济
  - `/bal` 查询自己的软妹币余额
  - `/pay <玩家名> <数额>` 向指定玩家转
  - `/baltop` 查看财富榜
- 信息
  - `/exp` 查看自己的经验值
  - `/near` 查看附近玩家
  - `/list` 查看在线玩家
  - `/motd` 查看每日信息
  - `/time` 查看游戏时间
  - `/ping` 测试延迟
  - `/rules` 查看游戏规则
  - `/seen <玩家名>` 查看上次在线时间
  - `/help` 查看指令帮助（建议参考我们的主页）
- 其他
  - `/afk` 进入暂离状态，再次输入可取消
  - `/hat` 将手中方块戴在头上
  - `/suicide` 自杀⚠️
- 作弊*（创造服）*
  - `/gm` 切换游戏模式
  - `/fly` 开启/关闭飞行模式
  - `/ptime <day/night/HH:MM>` 修改自己的游戏时间
  - `/weather <storm/sun> [时长]` 修改当前世界的天气

## 小工具·Nu :id=nu

- `/nu` 查看所有子指令
- `/nu el` 切换 鞘翅飞行模式
- `/nu format` 查看所有颜色和样式代码
- `/nu ping` 查看自己的 ping
- `/nu tps` 查看服务器的 TPS
- `/nu rename` 重命名手中的物品
- `/nu show` 展示手中的物品
- `/nu suffix` 修改自己在聊天框中的后缀

## 宠物·Pet :id=mypet

详见[宠物·指令](/plugins/mypet.md#cmds)。

## 仓鼠经济助手·Heh :id=heh

详见[仓鼠经济助手](/plugins/trade.md)。

## 记录查询·Co :id=co

- `/co i` 开启/关闭查询模式

## 锁箱锁门·Lock :id=lock

- `/lock` 查看锁箱帮助

## 多世界·Mv :id=mv

- `/mvl [页码]` 查看世界列表
- `/mvw` 查看大家都在哪个世界
- `/mvs` 传送到当前世界的重生点*（创造服）*
- `/mvtp <世界名>` 传送到指定世界*（创造服）*

## 自动整理·Cs :id=cs

- `/sort` 开启/关闭自动整理容器内的物品

## 城镇飞行·Towny :id=tfly

- `/tfly` 开启/关闭 *城镇飞行*
