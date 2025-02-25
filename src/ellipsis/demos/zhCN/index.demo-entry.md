# 文本省略 Ellipsis

复杂度不会消失，只会转移。

当你听到一些人对于精致的概念模型侃侃而谈，请保持清醒。

## 演示

```demo
basic
line-clamp
expand-trigger
custom-tooltip
dynamic-debug
```

## Props

| 名称 | 类型 | 默认值 | 说明 | 版本 |
| --- | --- | --- | --- | --- |
| expand-trigger | `'click'` | `undefined` | 展开的触发方式 | 2.1.0 |
| line-clamp | `number \| string` | `undefined` | 最大行数 | 2.1.0 |
| tooltip | `boolean \| TooltipProps` | `true` | Tooltip 的属性 | 2.1.0 |

## Slots

| 名称    | 参数 | 说明           |
| ------- | ---- | -------------- |
| default | `()` | 文本省略的内容 |
| tooltip | `()` | tooltip 的内容 |
