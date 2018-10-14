# js原生的日常所用

## 获取dom元素
```
    var a=document.getElementById();//id
    var b=document.getElementByClassName();//类名
    var c=document.getElementByTagName();//标签;
    var d=document.querySelector();
    var e=document.querySelectorAll();
```
## dom对象的属性和方法
```
1. dom对象.属性名===dom对象[属性名];获取值和赋值;
2.get/set/removeAttribute();以方法形式操作属性;
```
```

```
## dom节点访问关系
```
1.父节点：子元素.parentNode;兼容性好;
2.前一个兄弟节点: previousElementSibing及previousSibing;二者结合解决兼容问题;
3.后一个兄弟节点:nextElementSibing及nextSibing
4.单个子节点:firstElementChild及firstChild;lastElementCHild及lastChild;兼容问题;
5.所有子节点:children;
6.节点自己.parentNode.children[index];随意得到兄弟节点;
```
## 节点操作
```
1.创建节点:document.creatElement('p');
2.添加节点:div.appendChild(新节点),div.insetbefore(新节点，参考节点);
3.删除节点:父节点.removeChild(子节点)及子节点.parentNode.removeChild(子节点);
4.克隆节点:被克隆节点.cloneNode();参数默认为false,true代表深层克隆;
```
## DOM对象的属性操作
```
1.普通(src,title,id);
2.特殊(className,innerHTML,href);
3.表单(disable,selected,checked);
4.stye(本属性为对象，其他为字符串);
```
## css3对类的操作;
```
div.classList.add()/remove()/contains()/toggle();
```


