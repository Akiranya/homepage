# 机械

该插件可以让你在服务器里建造电梯、城门；快速检测光照、红石强度；还有快速换画！

## 电梯

> [!tip|label:电梯的作用]
> 电梯可以让你在不同楼层（高度）之间快速穿行。

简单讲，`电梯`只是一些处在不同高度的`告示牌`。一个两层楼的电梯可以是下面这个样子：

<!-- panels:start -->
<!-- div:left-panel -->
![电梯](../assets/images/plugins/cb-elevator.png ':class=img-center')
<!-- div:right-panel -->
这台电梯的一楼告示牌的第二行写的是`[Lift Up]`，二楼告示牌的第二行写的是`[Lift Down]`。
<!-- panels:end -->

所以使用告示牌就可以创建一个电梯啦（当然你还需要为电梯建造框架）。不同楼层电梯告示牌的`坐标`除`y`*（高度）*之外，`x`与`z`坐标必须都保持一致，这样它们才能在楼层之间联系起来。

### 开始建造

告示牌里的内容决定了告示牌在特定一层中的作用。

> [!warning]
> 请使用`橡木告示牌`。其他告示牌不保证可以正常使用。

- 如果牌子`第二行`写`[Lift Up]`，那么当玩家点击这个牌子时，会传送到`正上方`的<mark>有效告示牌</mark><sub>见下注解</sub>
- 如果牌子`第二行`写`[Lift Down]`，那么当玩家点击这个牌子时，会传送到`正下方`的有效告示牌
- 如果牌子`第二行`写`[Lift]`，意味着玩家无法点击这个告示牌，但你可以配合其他类型的告示牌使用
- 牌子`第一行`可以写上楼层的名字，以告知玩家到达了哪一层
- 牌子`第三行`和`第四行`可写上任意内容

> [!note|label:有效告示牌]
> 有效告示牌指这里上面提到的三种任意告示牌之一

### 多楼层

当有三个及以上的楼层时，就需要用 *两竖列* 的牌子来建造电梯。

<!-- panels:start -->

<!-- div:left-panel -->

#### 三层楼的建造方案

下面是一个三层楼的建造方案（![三层楼](../assets/images/plugins/cb-elevator-3-floors.png ':class=img-16') 点击看大图）

| 楼层 | 告示牌          | 告示牌          |
| ---- | ------------- | ------------- |
| 三楼 | `[Lift Down]` | `无`          |
| 二楼 | `[Lift Up]`   | `[Lift Down]` |
| 一楼 | `无`          | `[Lift Up]`   |

<!-- div:right-panel -->

#### 五层楼的建造方案

| 楼层 | 告示牌        | 告示牌          |
| ---- | ----------- | ------------- |
| 五楼 | `[Lift]`    | `[Lift Down]` |
| 四楼 | `[Lift Up]` | `[Lift Down]` |
| 三楼 | `[Lift Up]` | `[Lift Down]` |
| 二楼 | `[Lift Up]` | `[Lift Down]` |
| 一楼 | `[Lift Up]` | `[Lift]`      |

<!-- panels:end -->

如果需要建造更高的电梯，以此类推摆放好告示牌即可。

## 城门

> [!tip|label:城门的作用]
> 城门可以让你在游戏里建造类似中世纪城堡的大型城门！

**开始建造**

> [!warning]
> 请使用`橡木栅栏`和`橡木告示牌`来建造城门。其他种类的方块不保证有效。

建造城门只需要：

1. 特定的建筑结构
2. 告示牌+特定的文字内容
3. 红石电路<sub>（可选）</sub>

详细的建造方法请在[城镇生存服](/mc-servers/survival.md)输入指令`/warp mech-demo`查看演示。

## 电表

> [!tip|label:操作说明]
> 用煤炭右键一段红石电路，可以检测电流强度（范围`0-15 A`）。

![电表](../assets/images/plugins/cb-ammeter.png ':class=img-center')

## 光感器

> [!tip|label:操作说明]
> 用萤石粉右键一个地方，可以检测光照强度（范围`0-15 L`）。

![光感器](../assets/images/plugins/cb-lightstone.png ':class=img-center')

## 换画

> [!tip|label:操作说明]
> 先鼠标右键一幅画，然后滚动<kbd>鼠标滚轮</kbd>就可以更换墙壁上的画。

![换画](../assets/images/plugins/cb-painting-switcher.png ':class=img-center')
