### 简答题
1. 什么是 Dom？为什么要用 Dom？
    * 页面的文档对象模型
    * 通过可编程的对象模型，js获得了足够的能力来创建动态的HTML

1. Dom 有哪些常见属性？
    * document对象常用属性包括doctype,head,body,activeElement,title、characterSet,
    cookie,innerText,innerHTML,outerHTML等

1. 如何设置 Cookie？
    * 键值对。document.cookie=.....

1. innerText 和 innerHTML 有什么异同？
    * innerText返回元素内包含的文本内容，多层次下回按照元素由浅到深的顺序拼接其内容
    * 返回所有html内容

1. innerHTML 和 outerHTML 有什么不同？
    * outerHTML包括了元素标签等内容。xxx.outerHTML=""是替换。xxx.innerHTML=""是添加

1. 我们可以使用 document.write() 动态生成文档流吗？如何可以，如何操作？
    * 可以。
    * document.write(""),把要动态生成的文档写在括号内。

1. 在什么时候，document.write() 会重写文档流
    * 在页面已经渲染完的情况下

### 代码题
* [Link](https://github.com/a735315482/mfs-homework/blob/master/31-40/34.html)