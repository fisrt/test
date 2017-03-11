# Markdown语法

### 标题写法

### H1-H6（分别一个# ~ 六个######）
##### H5


一级标题（符号个数不限）
========================
二级标题
-----

    
### 一、块引用(>、>>、>>>一个>表示块级，>>两个表示嵌套以此类推)   
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.

>> ipsum dolor sit amet,con
>>>fdsfdsfdsafsfsad

> m ipsum dolor sit amet,consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
    

### 二、代码框
1 '`'包围一段标注的文字：you code hehe~
1 '```' 包围需要加入的代码： function(){console.log(1)}

### 三、图片和链接（图片有!,链接无）
* 图片为：`![](){ImgCap}{/ImgCap}	`
 	
* 链接为：`[]()`
 
  ![文字描述](http://cdn.meia.me/public/images/ilogo.svg)

  [链接到美啊](https://meia.me)

 链接还有参考式写法：

	几个网站[GitHub][1]、[segmentfault][2]以及[mine][3]		
	[segmentfault][2]是一个不错的[网站][]。		
	[1]:https://github.com "GitHub"		
	[2]:https://segmentfault.com "segmentfault"		
	[3]:https://github.com/fisrt/test "mine"		
	[网站]:https://github.com/fisrt/test	

几个网站[GitHub][1]、[segmentfault][2]以及[mine][3]

[segmentfault][2]是一个不错的[网站][]。
[1]:https://github.com "GitHub"		
[2]:https://segmentfault.com "segmentfault"		
[3]:https://github.com/fisrt/test "mine"
[网站]:https://github.com/fisrt/test

自动转为链接用<>:
<http://meia.me>
<http://www.google.com>

### 四、无序列表（*、-、+都表示为一样 中间加空格）   
* 列表列表1
* 列表列表1
+ 列表列表2
+ 列表列表2
- 列表列表3
- 列表列表3

### 五、有序列表 （1. 2. 3.表示 中间加空格）   
1. 列表列表
2. 列表列表
3. 列表列表

### 六、粗体、斜体、删除线（***B&I粗斜体，**B粗体, *I斜体、_斜体, ~删除线）
1. **我是粗体**

2. ***我是加粗斜体*** 

3. *斜体* 或者是 _还是斜体_

5.  ~~ 删除线 ~~（未生效，待后续查证）


### 七、我是分割线、下划线：
***
---

### 八、表格
| 表格| 工具| 练习|
| ---| ---| ---|
| 表格| 工具| 练习|
| 表格| 工具| 练习|


```
|:---|:---|:---|      左对齐
|:---:|:---:|:---:|   居中对齐
|---:|---:|---:|      右对齐
```






后续补充。。。
