### 参考资料
[Markdown教程](https://markdown.com.cn/intro.html)
### 1. Markdown是什么？

**Markdown**是一种轻量级**标记语言**，它以纯文本形式(_易读、易写、易更改_)编写文档，并最终以HTML格式发布。  
**Markdown**也可以理解为将以MARKDOWN语法编写的语言转换成HTML内容的工具。

### [](https://github.com/Guyungy/Markdown#2-%E8%B0%81%E5%88%9B%E9%80%A0%E4%BA%86%E5%AE%83)2. 谁创造了它？

它由[**Aaron Swartz**](http://www.aaronsw.com/)和**John Gruber**共同设计，**Aaron Swartz**就是那位于去年（_2013年1月11日_）自杀,有着**开挂**一般人生经历的程序员。维基百科对他的[介绍](http://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8)是：**软件工程师、作家、政治组织者、互联网活动家、维基百科人**。

他有着足以让你跪拜的人生经历：

-   **14岁**参与RSS 1.0规格标准的制订。
-   **2004**年入读**斯坦福**，之后退学。
-   **2005**年创建[Infogami](http://infogami.org/)，之后与[Reddit](http://www.reddit.com/)合并成为其合伙人。
-   **2010**年创立求进会（Demand Progress），积极参与禁止网络盗版法案（SOPA）活动，最终该提案被撤回。
-   **2011**年7月19日，因被控从MIT和JSTOR下载480万篇学术论文并以免费形式上传于网络被捕。
-   **2013**年1月自杀身亡。
- 天才都有早逝的归途。

### [](https://github.com/Guyungy/Markdown#3-%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E4%BD%BF%E7%94%A8%E5%AE%83)3. 为什么要使用它？

-   它是易读（看起来舒服）、易写（语法简单）、易更改**纯文本**。处处体现着**极简主义**的影子。
-   兼容HTML，可以转换为HTML格式发布。
-   跨平台使用。
-   越来越多的网站支持Markdown。
-   更方便清晰地组织你的电子邮件。（Markdown-here, Airmail）
-   摆脱Word（我不是认真的）。

### [](https://github.com/Guyungy/Markdown#4-%E6%80%8E%E4%B9%88%E4%BD%BF%E7%94%A8)4. _怎么使用？

如果不算**扩展**，Markdown的语法绝对**简单**到让你爱不释手。

Markdown语法主要分为如下几大部分： **标题**，**段落**，**区块引用**，**代码区块**，**强调**，**列表**，**分割线**，**链接**，**图片**，**反斜杠 `\`**，**符号'`'**。

#### [](https://github.com/Guyungy/Markdown#41-%E6%A0%87%E9%A2%98)4.1 标题

两种形式：  
1）使用`=`和`-`标记一级和二级标题。

> 一级标题  
> `=========`  
> 二级标题  
> `---------`

效果：

> # [](https://github.com/Guyungy/Markdown#%E4%B8%80%E7%BA%A7%E6%A0%87%E9%A2%98)一级标题
> 
> ## [](https://github.com/Guyungy/Markdown#%E4%BA%8C%E7%BA%A7%E6%A0%87%E9%A2%98)二级标题

2）使用`#`，可表示1-6级标题。

> # 一级标题  
> ## 二级标题  
> ### 三级标题  
> #### 四级标题  
> ##### 五级标题  
> ###### 六级标题

效果：

> # [](https://github.com/Guyungy/Markdown#%E4%B8%80%E7%BA%A7%E6%A0%87%E9%A2%98-1)一级标题
> 
> ## [](https://github.com/Guyungy/Markdown#%E4%BA%8C%E7%BA%A7%E6%A0%87%E9%A2%98-1)二级标题
> 
> ### [](https://github.com/Guyungy/Markdown#%E4%B8%89%E7%BA%A7%E6%A0%87%E9%A2%98)三级标题
> 
> #### [](https://github.com/Guyungy/Markdown#%E5%9B%9B%E7%BA%A7%E6%A0%87%E9%A2%98)四级标题
> 
> ##### [](https://github.com/Guyungy/Markdown#%E4%BA%94%E7%BA%A7%E6%A0%87%E9%A2%98)五级标题
> 
> ###### [](https://github.com/Guyungy/Markdown#%E5%85%AD%E7%BA%A7%E6%A0%87%E9%A2%98)六级标题

#### [](https://github.com/Guyungy/Markdown#42-%E6%AE%B5%E8%90%BD)4.2 段落

段落的前后要有空行，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用**两个以上**空格加上回车（引用中换行省略回车）。

#### [](https://github.com/Guyungy/Markdown#43-%E5%8C%BA%E5%9D%97%E5%BC%95%E7%94%A8)4.3 区块引用

在段落的每行或者只在第一行使用符号`>`,还可使用多个嵌套引用，如：

> > 区块引用  
> >> 嵌套引用

效果：

> 区块引用
> 
> > 嵌套引用

#### [](https://github.com/Guyungy/Markdown#44-%E4%BB%A3%E7%A0%81%E5%8C%BA%E5%9D%97)4.4 代码区块

代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如  
普通段落：

void main()  
{  
printf("Hello, Markdown.");  
}

代码区块：

```
void main()
{
    printf("Hello, Markdown.");
}
```

**注意**:需要和普通段落之间存在空行。

#### [](https://github.com/Guyungy/Markdown#45-%E5%BC%BA%E8%B0%83)4.5 强调

在强调内容两侧分别加上`*`或者`_`，如：

> *斜体*，_斜体_  
> **粗体**，__粗体__

效果：

> _斜体_，_斜体_  
> **粗体**，**粗体**

#### [](https://github.com/Guyungy/Markdown#46-%E5%88%97%E8%A1%A8)4.6 列表

使用`·`、`+`、或`-`标记无序列表，如：

> -（+*） 第一项 -（+*） 第二项 - （+*）第三项

**注意**：标记后面最少有一个_空格_或_制表符_。若不在引用区块中，必须和前方段落之间存在空行。

效果：

> -   第一项
> -   第二项
> -   第三项

有序列表的标记方式是将上述的符号换成数字,并辅以`.`，如：

> 1 . 第一项  
> 2 . 第二项  
> 3 . 第三项

效果：

> 1.  第一项
> 2.  第二项
> 3.  第三项

#### [](https://github.com/Guyungy/Markdown#47-%E5%88%86%E5%89%B2%E7%BA%BF)4.7 分割线

分割线最常使用就是三个或以上`*`，还可以使用`-`和`_`。

#### [](https://github.com/Guyungy/Markdown#48-%E9%93%BE%E6%8E%A5)4.8 链接

链接可以由两种形式生成：**行内式**和**参考式**。  
**行内式**：

> [Guyungy的Markdown库](https:://github.com/Guyungy/Markdown "Markdown")。

效果：

> [Guyungy的Markdown库](https://github.com/Guyungy/://github.com/Guyungy/Markdown "Markdown")。

**参考式**：

> [Guyungy的Markdown库1][1]  
> [Guyungy的Markdown库2][2]  
> [1]:https:://github.com/Guyungy/Markdown "Markdown"  
> [2]:https:://github.com/Guyungy/Markdown "Markdown"

效果：

> [Guyungy的Markdown库1](https://github.com/Guyungy/://github.com/Guyungy/Markdown "Markdown")  
> [Guyungy的Markdown库2](https://github.com/Guyungy/://github.com/Guyungy/Markdown "Markdown")

**注意**：上述的`[1]:https:://github.com/Guyungy/Markdown "Markdown"`不出现在区块中。

#### [](https://github.com/Guyungy/Markdown#49-%E5%9B%BE%E7%89%87)4.9 图片

添加图片的形式和链接相似，只需在链接的基础上前方加一个`！`。

#### [](https://github.com/Guyungy/Markdown#410-%E5%8F%8D%E6%96%9C%E6%9D%A0)4.10 反斜杠`\`

相当于**反转义**作用。使符号成为普通符号。

#### [](https://github.com/Guyungy/Markdown#411-%E7%AC%A6%E5%8F%B7)4.11 符号'`'

起到标记作用。如：

> `ctrl+a`

效果：

> `ctrl+a`

#### [](https://github.com/Guyungy/Markdown#5-%E8%B0%81%E5%9C%A8%E7%94%A8)5. _谁_在用？

Markdown的使用者：

-   GitHub
-   简书
-   Stack Overflow
-   Apollo
-   Moodle
-   Reddit
-   Obsidian
-   等等

#### [](https://github.com/Guyungy/Markdown#6-%E5%B0%9D%E8%AF%95%E4%B8%80%E4%B8%8B)6. 尝试一下

-   **Chrome**下的插件诸如`stackedit`与`markdown-here`等非常方便，也不用担心平台受限。
-   **在线**的dillinger.io评价也不错
-   **Windowns**下的MarkdownPad也用过，不过免费版的体验不是很好。
-   **Mac**下的Mou是国人贡献的，口碑很好。
-   **Linux**下的ReText不错。

**当然，最终境界永远都是笔下是语法，心中格式化 :)。**

---

**注意**：不同的Markdown解释器或工具对相应语法（扩展语法）的解释效果不尽相同，具体可参见工具的使用说明。 虽然有人想出面搞一个所谓的标准化的Markdown，
[没想到还惹怒了健在的创始人John Gruber](http://blog.codinghorror.com/standard-markdown-is-now-common-markdown)

---

以上基本是所有traditonal markdown的语法。

### [](https://github.com/Guyungy/Markdown#%E5%85%B6%E5%AE%83)其它：

列表的使用(非traditonal markdown)：

用`|`表示表格纵向边界，表头和表内容用`-`隔开，并可用`:`进行对齐设置，两边都有`:`则表示居中，若不加`:`则默认左对齐。

代码库

链接

MarkDown

[https://github.com/Guyungy/Markdown](https://github.com/Guyungy/Markdown "Markdown")

MarkDownCopy

[https://github.com/Guyungy/Markdown](https://github.com/Guyungy/Markdown "Markdown")

关于其它扩展语法可参见具体工具的使用说明。
