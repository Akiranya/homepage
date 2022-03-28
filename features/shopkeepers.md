# 村民商店

**村民商店** 可以让你自己创建村民的交易公式，从而让你与其他玩家交易。例如你可以创建一个用`金锭×3`换`钻石×1`的村民交易公式，这样其他玩家就可以用他们的`金锭×3`来换你的`钻石×1`。当然，作为店主需要及时为商店补充库存（在这个例子里，库存即钻石），以保证村民商店的正常交易。

## 创建商店

### 准备材料

- 箱子
- 你要交易的物品

### 具体步骤

1、把箱子放在你想开店的地方。箱子可以是小箱子，也可以是大箱子。这里以小箱子为例

![shopkeppers-step1](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/shopkeepers-step1.jpg ':class=img-uni')

2、选择一个方案，创建好`交易媒介`

!> 选择**以下其一**操作就可以了哦，请不要多选！

- 如果你想立个真的村民在你的商店旁，考虑`选项A`
- 如果你想节省空间，想容纳更多商店，考虑`选项B`

<!-- tabs:start -->

#### **选项A-村民媒介**

把鼠标准心对着刚刚放下的箱子，然后输入指令 `/shopkeeper trade`

之后你的箱子附近会生成一只`村民`，这就是你的商店的`交易媒介`。

其他玩家<kbd>右键点击</kbd>这只村民即可与你的商店进行交易。

#### **选项B-木牌媒介**

把鼠标准心对着刚刚放下的箱子，然后输入指令 `/shopkeeper trade sign`

之后你的箱子上会生成一个`告示牌`，这就是你的商店的`交易媒介`。

其他玩家<kbd>右键点击</kbd>这个告示牌即可与你的商店进行交易。

<!-- tabs:end -->

3、把你要交易的物品放到箱子里。

![shopkeepers-step3](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/shopkeepers-step3.jpg ':class=img-uni')

4、按住<kbd>潜行键</kbd>（默认<kbd>Shift</kbd>）后<kbd>右键点击</kbd>刚才生成的村民（或木牌）打开`商店编辑器`，如下图。

![shopkeepers-step4](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/shopkeepers-step4.jpg ':class=img-uni')

`商店编辑器`是个特殊的箱子界面。你会看到刚刚放进去的青金石出现在`第一行`的第一个槽位里。在这个界面里，`第一行`的所有槽位代表的是`你需要给其他玩家的物品`，也称作`结果物品`。青金石正下方有`两个槽位`（也就是`第二行`和`第三行`），都代表`其他玩家需要给你的物品`，也叫做`花费物品`。

要设置`花费物品`，在打开商店编辑器后，点击你背包里的一个物品，然后拿着这个物品点击第二/三行的槽位。举个例子，你想让其他玩家用`金锭×1`换你的`青金石×1`，就先拿起你背包里的金锭，然后左键点击青金石下方的槽位，即可设置好`花费物品`。一旦物品放下来了，你就可以用<kbd>左键/右键点击</kbd>这个物品来增加/减少这个物品的数量。按住<kbd>Shift</kbd><kbd>左键/右键点击</kbd>物品可一次增加/减少10个。

详见下面的操作。

|首先"拿起"一个物品|然后拿着物品左键点击|这样就设置好花费物品啦|
|:-:|:-:|:-:|
|![shopkeepers-step5](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/shopkeepers-step5.jpg ':class=img-uni')|![shopkeepers-step6](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/shopkeepers-step6.jpg ':class=img-uni')|![shopkeepers-step7](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/shopkeepers-step7.jpg ':class=img-uni')|

商店编辑器里的`每一竖列`代表的是`1`个村民交易公式；箱子有`9`竖列，所以单个页面可以创建`9`个交易公式。通过翻页<small>（点击商店编辑器里的书与笔）</small>玩家最多可以在单个商店里设置`45`个交易公式。

5、设置好商店后，直接关掉商店编辑器界面即可保存。

> [!tip]
> 你可以通过<kbd>右键点击</kbd>商店木牌来预览商店的交易公式是否正确。

![shopkeepers-step8](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/shopkeepers-step8.jpg ':class=img-uni')

6、要删除你的村民商店，点击商店编辑器里的`骨头`即可。

> [!danger]
> 删除商店不可撤销，谨慎使用！（商店删除后箱子里的内容会完全保留）。

## 常见问题

### 如何删除某项交易公式

把`花费物品`设置为`0`即可（也就是不断<kbd>右键点击</kbd>`花费物品`把数量设置为0）。

### 别人能打开我的商店箱子吗

不能（即使没有上牌子锁）。

但如果你把商店删除了，那么箱子是可以被打开的。

### 交易所得的物品去哪了

商店交易所得的物品都会被自动放入商店的箱子里。
