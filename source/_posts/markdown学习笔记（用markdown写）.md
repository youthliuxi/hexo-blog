---
title: markdown学习笔记（用markdown写）
tags:
  - markdown
  - 学习笔记
id: 255
categories:
  - 程序猿
date: 2016-01-12 14:42:44
---

## 写在前面

&emsp;&emsp;markdown是一个不错的标记语言，之前为了在线文档学过reStructuredText，名字太长了，而且，挺小众的，python程序员可能接触多一点，用这个搭建在线文档，简单方便，快捷。可惜，我忘了，不过没关系，我现在想学markdown，今后还可以用markdown写博客呢，应该会记得吧。

<!--more-->
&emsp;&emsp;首先，markdown的手册讲了markdown有多好，忽略，markdown兼容html，而且不需要处理&lt;和&amp;这两个符号，如果是html的话

> “&amp;”要变成“&amp;amp;”
> “&lt;”要变成“&amp;lt;”
> “©”要变成“&amp;copy;”

&emsp;&emsp;但是markdown会自动分辨这些符号，并且在需要转化的时候自动转化，而像是在html这种不需要转化的时候不作处理，嗯，点赞，but，同样忽略。
&emsp;&emsp;接下来才是重点中的重点，markdown的语法规范来啦，这不是演习，强调一遍，这不是演习，这不是演习。

## markdown来啦

1. 标题
> 标题当然使用的是#来做标记喽，“#”表示&lt;h1&gt;，“##”表示&lt;h2&gt;，
> 以此类推

2. 列表
> 无序列表就是*.
> 有序列表就是1\. 2\. 3.

3. 引用
> 想引用什么东西，比如代码，就在这一行前面加上&gt;
> 搞定

4. 图片与连接
> 连接和图片的语法仅仅只相差一个“!”
> \[baidu\](http://baidu.com )表示的就是一个连接“ [baidu](http://baidu.com/) ”
> \!\[baidu\](http://图片的地址 )表示的就是一张图片

5.粗体与斜体
> 用两个“\*”包起来，类似“**粗体**”表示的就是**粗体**
> 用一个“\*”包起来，类似“*斜体*”表示的就是_斜体_

6.表格
<table><thead><tr><th>A</th><th>B</th></tr></thead><tbody><tr><td>这是第一条记录的A</td><td>这是第一条记录的B</td></tr><tr><td>这是第二条记录的A</td><td>这是第二条记录的B</td></tr><tr><td>这是第三条记录的A</td><td>这是第三条记录的B</td></tr><tr><td>这是第四条记录的A</td><td>这是第四条记录的B</td></tr><tr><td>这是第五条记录的A</td><td>这是第五条记录的B</td></tr><tr><td>这是第六条记录的A</td><td>这是第六条记录的B</td></tr><tr><td>

> 用“\|”来划分各个列，用“-”来划分表头和内容

7.代码框
> 程序员福音来了，插入代码
> 用“```”把代码包裹起来就好了，支持缩进，类似这样：

> > \`\`\`
> > &lt;?php
> > &emsp;&emsp;echo&nbsp;"hello&nbsp;world";
> > ?&gt;
> > \`\`\`

8.分割线
&emsp;&emsp;使用三个型号，例如“\*\*\*”即可表示一个华丽丽的分割线

* * *

### 笔记小结

1.学会写标题、粗体斜体、表格、列表、图片和链接、代码框，就可以整理出一个比较好的笔记来了
2，markdown支持html的语法，所以也支持类似html里的转移字符，即以“&amp;”开头，以“;”结尾的转移字符；同时，markdown还支持反斜线“\”转移字符，尤其是在处理html源代码或者需要表示特殊字符的时候，都要注意。

#### 先写到这里，开始做**自动控制理论课程设计**

[来自为知笔记(Wiz)](http://www.wiz.cn/i/d15372b9 "来自为知笔记(Wiz)")