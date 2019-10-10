### 问答题

1. dom 元素常用属性有哪些？
    * document:doctype,head,body,activeElement,title、characterSet,
    cookie,innerText,innerHTML,outerHTML等
    * Element:nodeName,nodeType,className,id,children,childNodes,firstChile,lastChild,
    nextSibling,previousSibling,parentNode、parentElement;

1. 如何查找元素？
    * getElementById();getElementByClassName();getElementByTagName();getElementByName;
    querySelect();querySelectALL();ElementFormPoint();

1. 如何增/删/改/查元素？
    * 创建元素：creatElement();creatTextNode();creatDocumentFragment();
    * 修改元素：appendChild();insertBefore();replaceChild();
    * 删除元素： removeChild();

1. HTMLCollectioin 和 NodeList 有何异同？
    * HTMLCollection和我们看到的网页结构一样
    * NodeList得到的结果和代码结构相关，如一些我们看不见的空的回车等，以及一些空格
    * 有很大的相似性。都是类数组对象，都有length属性，可以通过for循环迭代。都是只读；都是实时的；
    都有item()方法；
    * 不同在于HTMLCOllection具有namedItem()方法，可以传递id或name获得元素。其item()方法和通过属性获取元素可以
    支持id和name。而NodeList只支持Id

### 代码题
* [link](https://github.com/a735315482/mfs-homework/blob/master/31-40/35.html)