# 城镇生存服·第十四周目

> 城镇生存服是一个以冒险与探索、收集与建造为主题的服务器。建设并经营自己的[城镇](/plugins/towny.md)是这里的主要玩法之一。这里完全继承原版生存的游戏机制和基本玩法，刷怪塔和大型红石机器在这里皆允许建造。此外我们还添加了一些完善联机游戏体验的插件，详见[插件列表](/welcome/plugins.md)。

![ruin](../assets/images/townsgallery/ruin.jpg ':class=img-small')
![cover-yukumo](../assets/images/cover-yukumo-fixed.jpg ':class=img-small')
![fantasy](../assets/images/townsgallery/fantasy.jpg ':class=img-small')
![kong-1](../assets/images/townsgallery/kong-1.jpg ':class=img-small')
![suno-3](../assets/images/townsgallery/suno-3.jpg ':class=img-small')
![scv](../assets/images/townsgallery/scv.jpg ':class=img-small')
![hongmoguan](../assets/images/townsgallery/hongmoguan.jpg ':class=img-small')
![cafe-1](../assets/images/townsgallery/cafe-1.jpg ':class=img-small')
![purple_fox-1](../assets/images/townsgallery/purple-fox-1.jpg ':class=img-small')

以上截图来自`主世界`<sub>(版本1.12)</sub>的玩家城镇。该世界现已迁移至[创造服](/mc-servers/creative.md)。

## 长期不换图

城镇生存服的每个`主世界`都会至少保持在线`2`年。

大家可以在这里放心大胆的开坑，建设自己的城镇，不用担心服务器突然换图～

并且当世界从服务器离线后，会开放世界存档的下载。届时大家可以下载到自己电脑自行游玩。

具体的换图策略[请看这里](/welcome/faq.md#save-policy)。

## 开放时间

城镇生存服 7×24小时 全年长期开放。

## 如何加入 :id=how-to-join

使用 *原版客户端*（允许加模组）直接加入以下服务器地址即可

    play.mimaru.me

当前生存服的版本为`1.15.2`。记得使用与此版本一致的客户端加入游戏哦～

**小提示**

- 新玩家背包自带`快捷菜单(钟)`。<kbd>鼠标右键</kbd>使用它，里面有你需要的大部分东西！
- 如果你不小心把快捷菜单弄丢了，不用担心～你还可以直接输入指令`/c`来打开它。

## 指令帮助

👉[点击查看](/welcome/commands.md)

## 插件列表 & 帮助 :id=plugins

👉[点击查看](/welcome/plugins.md)

<!-- panels:start -->

<!-- div:title -->

## 世界列表 :id=worlds

> [!tip|label:世界旅行指南]
> 在游戏里你可以输入`/c`打开`快捷菜单`，然后点击`跨世界传送`可以进行跨世界传送。

这里世界分为两大类：家园世界 & 资源世界。

- **家园世界** - 专用来建造和发展，永远不会删除（另见[服务器的换图策略](/welcome/faq.md#save-policy)）。  
- **资源世界** - 专用来采集自然资源。这些世界会不定期重置，<span style="color: red">请不要在这类世界中留下贵重物品</span>。

> [!tip|label:关于下方表格]
> `版本`是当时生成世界所使用的 Minecraft 版本。这决定世界拥有的地形和生物种类。

<!-- div:left-panel -->

### 家园世界

| 世界类型                  | 聊天框中显示为 | 版本  |
| :------------------------ | :--------------: | :---: |
| 🌍[主世界][the_overworld] |       w14        | 1.14  |
| 🌍[主世界][the_overworld] |       w13        | 1.13  |
| 👹[下界][the_nether]      |    w14_nether    | 1.14  |
| 🌃[末路之地][the_end]     |   w14_the_end    | 1.14  |

<!-- div:right-panel -->

### 资源世界

| 世界类型     | 聊天框中显示为 | 版本  |
| :---------------- | :--------------: | :---: |
| 🌍主世界<sub>资源</sub>   |      mining      | 1.15  |
| 👹下界<sub>资源</sub>     |  mining_nether   | 1.15  |
| 🌃末路之地<sub>资源</sub> |  mining_the_end  | 1.15  |

<!-- panels:end -->

[the_overworld]: https://minecraft-zh.gamepedia.com/%E4%B8%BB%E4%B8%96%E7%95%8C
[the_nether]: https://minecraft-zh.gamepedia.com/%E4%B8%8B%E7%95%8C
[the_end]: https://minecraft-zh.gamepedia.com/%E6%9C%AB%E8%B7%AF%E4%B9%8B%E5%9C%B0
[superflat]: https://minecraft-zh.gamepedia.com/%E8%B6%85%E5%B9%B3%E5%9D%A6%E4%B8%96%E7%95%8C
[bbs]: http://bbs.mimaru.me/

## 常见问题 & 解答

👉[点击查看](/mc-servers/survival/faq.md)

## 已修复的漏洞

城镇生存服已修复下列 *漏洞*。这意味着使用这些漏洞不会有任何效果：

- 0-tick 农作物瞬间生长 ([详情](https://bugs.mojang.com/browse/MC-113809))
- 重力方块复制物品 ([详情](https://minecraft.gamepedia.com/Tutorials/Block_and_item_duplication))

对于没有修复的 *游戏原版漏洞*（即 Minecraft 单机纯净版就存在的漏洞），玩家可以自由利用。

## 服务器优化

为了保证玩家能在服务器高负载时仍能够正常游玩，

当游戏服务器的负载过高时，将按条件自动采取以下一个/多个措施来降低负载：

### 暂停红石电路 :id=supress-redstone

一些运行频率过高的红石电路将在服务器负载过高时自动被暂停运行（不会被拆除）。

被暂停的红石电路不会因此而损坏，只是暂时不工作。降低频率或等待负载降低都可以让电路恢复运行。

### 降低生物智商 :id=supress-ai

降智之后的生物不会对周遭事物做出反应，例如苦力怕遇到玩家不会爆炸，牛羊不会吃草，鸡不会下蛋。

不是所有生物在高负载时都会被降智。末影人、僵尸猪人、海豚永远不会降智。

### 降低[方块随机刻][random-tick-speed] :id=set-random-tick-speed

当随机刻被降低后，游戏世界里关于方块的随机事件发生频率将会变低，例如植物的生长会变慢。

[random-tick-speed]: https://minecraft-zh.gamepedia.com/%E5%88%BB#.E6.96.B9.E5.9D.97.E5.88.BB

### 恢复 :id=recovery

当服务器负载较低时，将自动解除上面的限制措施。
