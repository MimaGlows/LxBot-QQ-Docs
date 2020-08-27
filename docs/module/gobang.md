# 五子棋
<span class="span-group">群聊</span>

::: tip 注意
本模块并不包含黑方禁手的判定，请玩家自行根据[该链接](https://baike.baidu.com/item/%E7%A6%81%E6%89%8B)判定。
:::

---
::: theorem 你知道吗？
早期五子棋是使用 Emoji 输出的。
:::

## 帮助
```
/g help
/gobang help
```

## 创建房间
```
/g create [棋盘大小]
/gobang create [棋盘大小]
```
`[棋盘大小]` 为整数，取值范围为 **5 ~ 20**（默认 15）。

## 加入房间
```
/g join <房间 ID>
/gobang join <房间 ID>
```
`<房间 ID>` 由[创建房间](#创建房间)生成。

## 删除房间
该指令需要您在一个房间中。
```
/g stop
/g exit
/gobang stop
/gobang exit
```

## 获取棋盘
该指令用于图片无法正常获取时的重试方案。
```
/g get
/gobang get
```

## 放置棋子
该指令需要您在一个房间中。
```
/g put <x> <y>
/g place <x> <y>
/gobang put <x> <y>
/gobang place <x> <y>
```
`<x>`（横向）、`<y>`（竖向）为各轴坐标，在棋盘图片中显示。

示例指令：
```
/g put 7 8
```

## 清空所有房间
<span class="span-admin">Bot 管理员</span>
```
/g clear
/gobang clear
```