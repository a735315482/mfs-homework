### 问答题
1. 什么是事件绑定？我们为什么需要它？
    * 在事件发生时执行js，在发生之前指定事件的相应函数，这个指定的过程就是事件绑定。
    * 使js有能力对html事件做出反应；

1. 有哪三种方法绑定事件？
    * 在DOM元素中直接绑定。&lt;div onclick="">
    * 在jS代码中绑定elementObject.onclick() ={}
    * .addEventListener()

1. document.getElementById("eleID").onclick = onclickHandle 和 addEventListener() 绑定事件处理函数有何异同？不同之处请至少说出3点。
    * .onclick绑定时间函数会存在着替换，即绑定一个会把原来的替换掉，而addEventListener()则是再多绑定一个，并存，需要用removeEventListener()来解绑
    * addEventListener()作用于DOM元素而不是html元素
    * addEventListener()可以通过事件流三个阶段更好地控制何时触发事件处理程序。

1. 什么是事件对象？我们如何获取事件对象？
    * elementObject。绑定的事件需要有一个目标对象
    * geiElementBy....

### 代码题
* [Link](https://github.com/a735315482/mfs-homework/blob/master/31-40/37%E6%A0%87%E7%AD%BE%E9%A1%B5.html)