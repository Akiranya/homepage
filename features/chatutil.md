# 聊天扩展

## 颜色&格式代码

颜色&格式代码是诸如 `&2`、`&b`、`&m`的特殊符号，可以让你给 Minecraft 中的文字加上颜色。

<!-- tabs:start -->

#### **颜色代码**

  <table>
    <tbody>
      <tr>
        <th>颜色</th>
        <th>变量名</th>
        <th>颜色代码</th>
      </tr>
      <tr style="background: #aa0000; color: #fafafa;">
        <td>暗红色</td>
        <td>dark_red</td>
        <td>&4</td>
      </tr>
      <tr style="background: #ff5555; color: #fafafa;">
        <td>红色</td>
        <td>red</td>
        <td>&c</td>
      </tr>
      <tr style="background: #ffaa00; color: black;">
        <td>金色</td>
        <td>gold</td>
        <td>&6</td>
      </tr>
      <tr style="background: #ffff55; color: black;">
        <td>黄色</td>
        <td>yellow</td>
        <td>&e</td>
      </tr>
      <tr style="background: #00aa00; color: #fafafa;">
        <td>暗绿色</td>
        <td>dark_green</td>
        <td>&2</td>
      </tr>
      <tr style="background: #55ff55; color: black;">
        <td>绿色</td>
        <td>green</td>
        <td>&a</td>
      </tr>
      <tr style="background: #55ffff; color: black;">
        <td>青色</td>
        <td>aqua</td>
        <td>&b</td>
      </tr>
      <tr style="background: #00aaaa; color: #fafafa;">
        <td>暗青色</td>
        <td>dark_aqua</td>
        <td>&3</td>
      </tr>
      <tr style="background: #0000aa; color: #fafafa;">
        <td>深蓝色</td>
        <td>dark_blue</td>
        <td>&1</td>
      </tr>
      <tr style="background: #5555ff; color: #fafafa;">
        <td>蓝色</td>
        <td>blue</td>
        <td>&9</td>
      </tr>
      <tr style="background: #ff55ff; color: #fafafa;">
        <td>亮紫色</td>
        <td>light_purple</td>
        <td>&d</td>
      </tr>
      <tr style="background: #aa00aa; color: #fafafa;">
        <td>暗紫色</td>
        <td>dark_purple</td>
        <td>&5</td>
      </tr>
      <tr style="background: #ffffff; color: black;">
        <td>白色</td>
        <td>white</td>
        <td>&f</td>
      </tr>
      <tr style="background: #aaaaaa; color: black;">
        <td>灰色</td>
        <td>gray</td>
        <td>&7</td>
      </tr>
      <tr style="background: #555555; color: #fafafa;">
        <td>深灰色</td>
        <td>dark_gray</td>
        <td>&8</td>
      </tr>
      <tr style="background: #000000; color: #fafafa;">
        <td>黑色</td>
        <td>black</td>
        <td>&0</td>
      </tr>
    </tbody>
  </table>

#### **格式代码**

| 格式代码 | 说明   |
| ---- | ------ |
| &k   | 混淆   |
| &l   | **加粗**   |
| &m   | ~~删除线~~ |
| &n   | <u>下划线</u> |
| &o   | <i>斜体</i>   |
| &r   | 重置   |

<!-- tabs:end -->

## 代码用法

- 在代码**右边**的文字，都会变成该代码对应的样式。
- 文字的样式永远是以离文字**左边最近**的代码为准。

如果要达到下面这样的效果：

![秀秀我们的爱](https://mewcraft-homepage.oss-cn-zhangjiakou.aliyuncs.com/images/color-code-example.png)

那么像下面这样使用颜色代码即可：

```
&a溴 &b溴 &c我 &d们 &e的 &f爱
```

## 聊天频道

?> 频道功能是[城镇系统](/features/towny.md)的一部分功能。

- 世界频道
  - 加入指令`/g`
  - 所有人默认已经加入这个频道，无需再次加入。
- 城镇频道
  - 加入指令`/tc`
  - 进入这个频道后，你说的话只有来自你城镇的人才能看到。
  - 如果你加入了一个城镇，即便不进入这个频道，你依然能看到该频道里信息。
- 国家频道
  - 加入指令`/nc`
  - 进入这个频道后，你说的话只有来自你国家的人才能看到。
  - 如果你加入了一个国家，即便不进入这个频道，你依然能看到该频道里信息。
- 附近频道
  - 加入指令`/lc`
  - 加入这个频道以后，你说的话只有附近`100`格以内的人能看到。

## 修改聊天昵称

昵称是你的ID显示在聊天框的样子。你可以输入`/nick`来修改自己的昵称。

## 添加聊天后缀

后缀是显示在你的ID后面的文字。你可以输入`/mu suffix`为自己添加后缀。

## 屏蔽聊天消息

不想看到某人的聊天消息？输入`/ignore`即可将他屏蔽。