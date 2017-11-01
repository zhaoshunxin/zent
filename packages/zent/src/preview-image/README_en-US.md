---
title: PreviewImage
path: component/preview-image
group: Data Display
---

## previewImage 图片预览

这是一个图片预览组件。

### 使用指南

-  用于缩略图放大预览显示
-  支持图片上一张、下一张、翻转功能

## API

| 参数            | 说明               | 类型             | 默认值      | 备选值     |
|------          |------              |------            |--------    |--------   |
| images         | 待预览图片url       | array            |         |              |
| index          | 显示第几张，从0开始  | number           | 0       |              |
| showRotateBtn  | 是否显示翻转按钮     | bool             | true     |  true,false |
| className      | 可选，自定义类名     | string           | `''`     |         |
| prefix         | 可选，自定义前缀     | string           | `'zent'` |         |