### 问答题

1. BOM 是什么？提供的 API 让我们能操作什么？
    * 浏览器对象模型
    * 访问窗口对象，比如改变窗口大小，移动窗口位置，打开新的窗口和关闭窗口，弹出对话框，
    进行导航以及获取客户的一些信息。

1. window.name 有怎样的特性
    * 浏览器刷新后该属性保持不变

1. 如何获取窗口的尺寸？
    * window.innerWidth;window.innerHeight

1. 如何调整滚动条位置
    * window.scrollX;window.scrollY

1. 如何获取浏览器相关信息
    * window.navigator

1. 如何得到一个元素计算后的属性值
    * window.getComputedStyle("元素,"伪类")

1. 如何模拟点击前进后退按钮的点击？
    * history.back();history.forward()