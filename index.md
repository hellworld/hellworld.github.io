# 2015.12.25分享会

---

# 学习Markdown

---

# 思维导图
![思维导图](https://raw.githubusercontent.com/hellworld/hellworld.github.io/master/Res/mymind.png)

---

# Markdown是什么

>Markdown是一种轻量级标记语言,它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）“。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。
>
> ——维基百科

<br/><br/><br/>

>Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。
>
> ——百度百科

---

## 谁发明了Markdown
<br/>
它由**Aaron Swartz**和**John Gruber**共同设计.
<br/>
**John Gruber**是苹果社群著名的**blogger、作家、UI设计师、软件工程师**,持续观察和发表苹果公司相关资讯和观点长达十余年。  
<br />

**Aaron Swartz**就是那位于*2013年1月11日*自杀,有着**开挂**一般人生经历的程序员。维基百科对他的[介绍](http://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8)是：**软件工程师、作家、政治组织者、互联网活动家、维基百科人**。
<br/><br/><br/>
![Aaron Swartz](https://raw.githubusercontent.com/hellworld/hellworld.github.io/master/Res/AaronSwartz.png)

---

他有着足以让你跪拜的人生经历：
<br/>  

- **14岁**参与RSS 1.0规格标准的制订。     
- **2004**年入读**斯坦福**，之后退学。   
- **2005**年创建[Infogami](http://infogami.org/)，之后与[Reddit](http://www.reddit.com/)合并成为其合伙人。   
- **2010**年创立求进会（Demand Progress），积极参与禁止网络盗版法案（SOPA）活动，最终该提案**居然**被撤回。   
- **2011**年7月19日，因被控从MIT和JSTOR下载480万篇学术论文并以免费形式上传于网络被捕。     
- **2013**年1月自杀身亡。
- **2013**年3月15日，获得美国James Madison Award奖。



天才都有早逝的归途（又是一位**犹太人**）。

纪念斯沃茨[Remeber Aron Swartz](http://www.rememberaaronsw.com/memories/)这个网站就是用纯**Markdown**写的，听者伤心，闻者流泪。

---

#为什么要使用Markdown？

---
# 优点

* 简单，容易上手（易读、易写、易更改）

* 纯文本实现，容易扩展，方便和其他工具联通

* 平台支持广：以**Github**为首的各种平台，各种博客都支持，基本上现在面向程序员的输入框都可以用Markdown来写了

* 丰富的工具链
    * 编辑器：各种支持所见即所得的编辑器
    * 和各种其他格式互相转换的工具：PDF、Mobi、Equb、HTML等等

---

## Markdown编辑器
* **Windows** 平台
    * [MarkdownPad](http://markdownpad.com/)
* **Linux** 平台
    * [ReText](http://sourceforge.net/p/retext/home/ReText/)
* **Mac** 平台
    * [Mou](http://mouapp.com/)
* **IOS** 平台
    * Byword
* **Android** 平台
    * MarkdownX
* **在线编辑器**
    * [Cmd Markdown](https://www.zybuluo.com/mdeditor)

 ---

# 推荐使用编辑器

***[Atom](https://atom.io/)***
一款由**Github**打造的先进的开源跨平台编辑器
<br/><br/><br/><br/>
![AtomScreenshot](https://raw.githubusercontent.com/hellworld/hellworld.github.io/master/Res/atom_screenshot.png)

---

# 转换工具

- 制作文档
    - [mkdocs](http://www.mkdocs.org/)  
- 制作电子书
    - [gitbook](https://www.gitbook.com)，利用Markdown写电子书的工具，并提供免费托管。

- 制作slides
    - [landslide](https://github.com/adamzap/landslide), [Demo](http://adamzap.com/misc/presentation.html#slide1)

---

# Markdown语法

---
# 标题
\# 一级标题  
\## 二级标题  
\### 三级标题  
\#### 四级标题  
\##### 五级标题   
\###### 六级标题  
<br /><br />

# 一级标题:
## 二级标题:
### 三级标题:
#### 四级标题:  
##### 五级标题:  
###### 六级标题:  

---

#空格与空行  

<br />
Markdown的**空格**与**空行**直接使用Html标签和转义符来实现
<br /><br /><br />

* 空格: 使用 `&#160;`  

<br />

* 空行: 使用 &lt;br&gt; 或者 &lt;br /&gt;

---
# 列表  

* 无序列表：  
在文字前面加上`#`或者`*`  <br />  
\* 1  
\* 2  
\* 3  <br /><br />
\# 1  
\# 2  
\# 3


* 有序列表：  
在文字前加`1.` `2.` `3.`  <br />   
1\. 1  
2\. 2  
3\. 3  

---

# 引用
如果你需要引用一小段别处的句子，那么就要用引用的格式，只需要在文本前面加上`>`

<br />
>例如这样

<br />
嵌套使用：
<br />

>数据结构
>>数
>>>二叉树

---

# 粗体和斜体
* 用两个*或两个_包含一段文本就是粗体的语法  <br /><br />
\*\*我是粗体\*\*  
\_\_我也是粗体\_\_  <br /><br />
**我是粗体**  
__我也是粗体__  <br /><br />
* 用一个*或一个_包含一段文本就是斜体的语法  <br /><br />
\*我是斜体\*  
\_我也是斜体\_  <br /><br />
*我是斜体*
_我也是斜体_

---

# 图片与链接
插入链接与插入图片的语法很像，区别在于一个!号   
图片为: ![]\(ImageUrl\)    
链接为: []\(\)
<br /><br />
插入图片的地址需要图床


---
# 代码块


---

#表格

---


# 相关及参考链接

此PPT链接:
http://yexiang.me


我的**Github**地址:  
https://github.com/hellworld/hellworld.github.io  


Markdown入门——指南
http://www.jianshu.com/p/1e402922ee32/

用Markdown写一个极客范儿的PPT
http://www.jianshu.com/p/e063303317cb






---

#分享几个网站：

[MindStore.io](http://mindstore.io):一个发现、分享、探讨新酷产品的社区，帮助你找到最好的产品和想法。
### 微信公众号: mindstore
<br/>
[Next](http://next.36kr.com):一个快速发现、分享和讨论新产品的社区
### 微信公众号: findgreatproduct
<br/>
[Appsolution](http://app.so):专注于推荐新酷精华应用
### 微信公众号: appsolution

---

# 圣诞快乐!!!

---

# 谢谢大家!!!
