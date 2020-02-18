---
title: 代码调试
header: develop
nav: devtools
sidebar: editor_debug
---

>此功能在`2.16.0-rc`之后版本可用。

目前在开发者工具中进行智能小程序断点调试时，须在调试器source面板中找到资源文件后加上断点，在实际使用时因资源文件层级较深，断点操作较为繁琐。
为提高开发者效率，编辑器提供了在代码编辑区域直接设置断点的方式，且断点状态与调试器保持同步。

### 设置断点

如图所示，在js文件行号左侧为断点设置区，点击可设置或取消断点，shift + 点击断点可将断点设置为不可用状态。
![](../../../img/tool/editor_debug1.png)

断点图标状态的含义如下：

|图标 | 含义 |
|---|---|
|小红点|此行已设置断点|
|小灰点|此行断点为不可用状态|
|小浅红点|此行可设置断点|

### 执行断点调试

设置断点后执行刷新操作![](../../../img/tool/editor_debug2.png)，将自动执行断点调试 。

如图所示，编辑器中断点状态与调试器保持同步，开发者可进一步在调试器中查看智能小程序此时的运行状态。

![](../../../img/tool/editor_debug3.png) 

**注：当代码运行到断点的时候，整个小程序都停止了，所以模拟器会出现白屏或者无法操作的情况**