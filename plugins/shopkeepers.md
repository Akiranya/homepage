# 村民商店

**村民商店** 这个插件可以让你创建村民的交易公式，从而让你与其他玩家交易。例如你可以创建一个用3金锭换1钻石的村民交易公式，这样其他玩家就可以用他们的3金锭来换你的1钻石。当然，作为店主需要及时为商店补充库存（放在这里就是钻石）以保证村民商店的正常交易。

## 创建商店

### 准备材料

- 箱子
- 你要交易的物品

### 具体步骤

1、把箱子放在你想开店的地方。箱子可以是单箱子，也可以是大箱子。

![shopkeppers-step1](../assets/images/plugins/shopkeepers-step1.jpg ':size=400')

2、准心对着刚刚放下的箱子，然后输入`/shopkeepers trade sign`。

![shopkeepers-step2](../assets/images/plugins/shopkeepers-step2.jpg ':size=400')

3、把你要交易的物品放到箱子里。

![shopkeepers-step3](../assets/images/plugins/shopkeepers-step3.jpg ':size=400')

4、按住 <kbd>潜行键</kbd>（默认 <kbd>Shift</kbd>）后 <kbd>右键</kbd>    点击商店木牌来打开「商店编辑器」，如下图。

![shopkeepers-step4](../assets/images/plugins/shopkeepers-step4.jpg ':size=400')

商店编辑器是个特殊的箱子界面。你会看到刚刚放进去的青金石出现在第一行的第一个槽位里。在这个界面里，第一行的所有槽位代表的是「你需要给其他玩家的物品」，也称作「结果物品」。青金石正下方有两个槽位，都代表「其他玩家需要给你的物品」，也叫做「花费物品」。每一列代表的是一个村民交易公式；单个页面可以创建9个交易公式。通过翻页*（点击商店编辑器里的书与笔）*玩家最多可以在单个商店里设置45个交易公式。

要设置「花费物品」，在打开商店编辑器后，点击你背包里的一个物品，然后拿着这个物品点击第二/三行的槽位。举个例子，你想让其他玩家用1金锭换你的1青金石，就先拿起你背包里的金锭，然后左键点击青金石下方的槽位，即可设置好「花费物品」。一旦物品放下来了，你就可以用 <kbd>左键/右键点击</kbd> 物品来调整其数量。按住 <kbd>Shift</kbd> <kbd>左键/右键点击</kbd> 物品可一次增加/减少10个。

详见下图。

|1|2|3|
|:-:|:-:|:-:|
|![shopkeepers-step5](../assets/images/plugins/shopkeepers-step5.jpg ':size=250')|![shopkeepers-step6](../assets/images/plugins/shopkeepers-step6.jpg ':size=250')|![shopkeepers-step7](../assets/images/plugins/shopkeepers-step7.jpg ':size=250')|

5、设置好商店后，关掉商店编辑器界面即可保存。你可以通过 <kbd>右键点击</kbd> 商店木牌来预览交易公式是否正确。

![shopkeepers-step8](../assets/images/plugins/shopkeepers-step8.jpg ':size=400')

6、要删除你的村民商店，点击商店编辑器里的骨头即可。注意此操作不可撤销，谨慎使用！

## 常见问题

1、如何删除某项交易公式？

把「花费物品」设置为0即可，也就是不断 <kbd>右键点击</kbd> 「花费物品」把数量设置为0。
