[![Page Views Count](https://badges.toozhao.com/badges/01JJKDKJ0F551WYNBTCJDR81TB/green.svg)](https://badges.toozhao.com/stats/01JJKDKJ0F551WYNBTCJDR81TB "Get your own page views count badge on badges.toozhao.com")

# 关于 GGCC-UI

## GGCC-UI 是什么

GGCC-UI 是一套基于 C++ 和 Raylib 的“所见即所得”的用户界面（GUI）系统，采用面向对象的编程理念，但是封装了一套类似 Dear ImGui 的控件创建方案，使得开发者可以通过一行代码创建一个控件。

GGCC-UI 的设计初衷是数学可视化，并吸收了 Dear ImGui 的设计特点，因此早期的 GGCC-UI 采取了极为紧凑的控件布局。后经过向 WinUI 的学习借鉴，逐渐调整为较为宽松的设计，一定程度上提高了用户界面的可读性。

## 为什么选择 GGCC-UI

- 美观与流畅的设计：

GGCC-UI 大量使用非线性动画，极大地提高了 GUI 运行的流畅程度，增进视觉体验。

- 简单的代码结构：

在 GGCC-UI 中，用户可以通过一行代码创建一个控件，并利用 lambda 表达式表达嵌套关系，使代码的结构与界面设计结构相统一，使用贴近自然语言的方法进行编程。

## GGCC-UI 有什么局限性

- 高系统占用：

GGCC-UI 基于 Raylib 视频游戏引擎，采用每帧全部重绘的方法，虽然这种方式在游戏开发中比较通用，但是对于动态效果较少的工具性应用程序而言，则大量占用了 CPU 和 GPU。

- 静态设计思路：

GGCC-UI 采用静态控件，意味着你将不能随时更改控件的参数。
