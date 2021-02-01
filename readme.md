this is a markdown note
=======================

> 标题

```
一级标题  
========
```
一级标题
========
```
二级标题  
------
```
二级标题
-------
```
# 一级标题  
## 二级标题  
### 三级标题  
#### 四级标题  
##### 五级标题  
###### 六级标题  
```

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

> 段落

markdown段落的换行是使用两个以上的空格加回车  

也可以用一个空行来表示重新开始一个段落  

> 字体

markdown的字体有以下几种

`*斜体字体*`

 *斜体字体*

`_斜体字体_`

 _斜体字体_

`**粗体字体**`

 **粗体字体** 

 `__粗体字体__`

__粗体字体__

`***粗斜体字体***`

 ***粗斜体字体***

`___粗斜体字体___` 

___粗斜体字体___

> 分隔线

分隔线用三个或三个以上的*、-、_构成，以下写法可以构成分割线  
```
***  
* * *  
*****************  
___  
_   _   _  
_________________  
---  
-  -  -  
------------------
```
***  
* * *
*****************************
___
_ _ _
_____________________________
---
- - -
-----------------------------

> 删除线
```
我没被删除  
~~我被删除了~~  
```
我没被删除  
~~我被删除了~~

> 下划线  


使用html的\<u>和\</u>  
<u>我有下划线嘻嘻嘻</u>

> 脚注

由于GitHub Flavored Markdown不支持脚注，那么我们可以使用Unicode字符或者手动打上标签对其进行伪造\<sup>1\</sup>

说明脚注的用法<sup id="a1">[1](#f1)</sup>

<b id="f1">1</b>: 脚注内容在这里 [](#a1)


脚注\[2]

\[2]: 这是第二条脚注  
注：Github不支持此种脚注

> 列表

markdown支持有序列表和无序列表  
无序列表使用\*、\+、\-作为列表标记，这些标记后面要添加一个空格。
```
* 第一项  
* 第二项  
* 第三项  
```
* 第一项  
* 第二项  
* 第三项
```
+ 第一项  
+ 第二项  
+ 第三项  
```
+ 第一项  
+ 第二项  
+ 第三项  
```
- 第一项  
- 第二项  
- 第三项  
``` 
- 第一项  
- 第二项  
- 第三项  

有序列表使用数字加上\.表示  
``` 
1. 第一项  
2. 第二项  
3. 第三项  
```   
1. 第一项
2. 第二项
3. 第三项

列表嵌套  
```
1. 第一项:
   - 第一项元素一
   - 第一项元素二
   - 第一项元素三
2. 第二项:
   - 第二项元素一
   - 第二项元素二
   - 第二项元素三
```  
1. 第一项:
   - 第一项元素一
   - 第一项元素二
   - 第一项元素三
2. 第二项:
   - 第二项元素一
   - 第二项元素二
   - 第二项元素三
  

> 区块 

区块的引用使用>在段落开头，后紧跟空格  
区块嵌套  
```
> 嵌套一
> > 嵌套二
> > > 嵌套三
```   
> 嵌套一
> > 嵌套二
> > > 嵌套三   

列表中也可以使用区块,区块中也可以使用列表


> 代码  

如果是段落上的一个函数或者片段的代码可以用反引号把他包起来(`` ` ``)

\`printf()\`函数  
`printf()`函数  

> 代码区块

代码区块使用4个空格或者一个Tab  

      <?php
      echo 'RUNOOB';
      function test(){
      echo 'test';
      }>  
   
也可以用`` ``` ``包裹代码：  
```javascript
$(document).ready(function (){
   alert('RUNOOB');
});
```  
> 链接  

使用方法为\[链接名称](链接地址) 或者 <链接地址>,如:  
```
这是一个链接 [链接链接](www.google.com)  
```

这是一个链接 [链接链接](www.google.com)  

`<https://www.google.com>`

<https://www.google.com>  

> 图片  
  
```
![alt 属性文本](图片地址)
![alt 属性文本](图片地址 "可选标题")
```
* 开头一个!
* 接着一个[],里面放置图片的替代文字
* 再接着一个(),里面放置图片的地址，还可以用"title"包住图片的title

> 表格  

Markdown使用`|`来分隔不同的单元格，使用`-`来分隔表头和其他行  
```
|  表头  |  表头  |  表头  |
|  ---   |  ---  |   ---  |
|  内容  |  内容  |  内容  |
|  内容  |  内容  |  内容  |
```
|  表头  |  表头  |  表头  |
|  ---   |  ---  |   ---  |
|  内容  |  内容  |  内容  |
|  内容  |  内容  |  内容  |
  
对齐方式:
 
- `-:`设置内容和标题栏右对齐  
- `:-`设置内容和标题栏左对齐  
- `:-:`设置内容和标题栏居中对齐  
  
如：
```
|  表头1111111  |  表头2222  |  表头333333  |
|  :----   |  ----:  |   :----:  |
|  内容  |  内容  |  内容  |
|  内容  |  内容  |  内容  |
```
|  表头1111111 |  表头2222  |  表头333333  |
|  :----   |  ----:  |   :----:  |
|  内容  |  内容  |  内容  |
|  内容  |  内容  |  内容  |