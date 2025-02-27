---
title: Divider 分割线
description:
type: 0
group: ⚙ 组件
menuName: Divider 分割线
icon:
order: 42
---

## 基本用法

```schema: scope="body"
{
    "type": "divider"
}
```

## 不同样式

```schema: scope="body"
[
    {
        "type": "divider"
    },
    {
        "type": "divider",
        "lineStyle": "solid"
    }
]
```

## 属性表

| 属性名    | 类型     | 默认值       | 说明                                       |
| --------- | -------- | ------------ | ------------------------------------------ |
| type      | `string` |              | `"divider"` 指定为 分割线 渲染器           |
| className | `string` |              | 外层 Dom 的类名                            |
| lineStyle | `string` | `solid`      | 分割线的样式，支持`dashed`和`solid`        |
| direction | `string` | `horizontal` | 分割线的方向，支持`horizontal`和`vertical` |
| color     | `string` |              | 分割线的颜色                               |
| rotate    | `number` |              | 分割线的旋转角度                           |
