# Badge

[![npm version](https://img.shields.io/npm/v/@hecom/badge.svg?style=flat)](https://www.npmjs.com/package/@hecom/badge)
[![Build Status](https://travis-ci.org/hecom-rn/Badge.svg?branch=master)](https://travis-ci.org/hecom-rn/Badge)

这是一个角标的UI组件，有四种可能：

* 没有数字，只有一个圆圈，有外层隔离间隔。
* 没有数字，只有一个圆圈，无外层隔离间隔。
* 有数字，有外层隔离间隔。
* 有数字，无外层隔离间隔。

外层隔离间隔，是在数字视图外面再多上一层间隔，比如红色中心圆圈外面有一圈白色间隔。

**属性**：

* `count: number`：展示的数字。
* `maxCount: number`：计数的最大值，如"99"。如果比最大值大，则显示"99+"。
* `radius: number`：数字两侧的圆角的半径大小。
* `bgColor: string`：数字的背景色。
* `outSpace: number`：外层与内层直接的间隔。
* `outBgColor: string`：外层的背景色。
* `innerVerticalSpace: number`：数字与内层圆圈的上下边距，用于计算字号。
* `style: any`：自定义外部样式。