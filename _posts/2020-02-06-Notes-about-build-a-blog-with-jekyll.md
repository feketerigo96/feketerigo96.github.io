---
layout: post
title: Notes about build a blog with jekyll
date: 2020-2-06
categories: learning
tags: [Github Page,jekyll,Markdown]
descrpition: "Notes about build a blog with jekyll"
---

To build a static personal blog by Github Page is very easy. You can check official tutorial or this [Chinese tutorial](https://www.zhihu.com/question/20463581/answer/25478916)<br/>
Moreover, the favicon may not show as it supposed to be. You should add ```?``` after the favicon souece file name. For example,it is like<br/>
```<link rel="shortcut icon" type="image/png" href="{{ "/img/favicon.png?" | prepend: site.baseurl}}">```<br/><br/><br/>
Building a personal blog also needs to learning some Markdown syntax.(and some html syntax).Here are some basic Markdown syntax:<br/>
<pre>
    Markdown 目录：
    [TOC]

    Markdown 标题：
    # 这是 H1
    ## 这是 H2
    ### 这是 H3

    Markdown 列表：
    - 列表项目
    1. 列表项目

    *斜体*或_斜体_
    **粗体**
    ***加粗斜体***
    ~~删除线~~

    Markdown 插入链接：
    [链接文字](链接网址 "标题")

    Markdown 插入图片：
    ![alt text](/path/to/img.jpg "Title")

    Markdown 插入代码块：
    ```python
    #!/usr/bin/python3
    print("Hello, World!");
    ```

    Markdown 引用：
    > 引用内容

    Markdown 分割线：
    ---

    Markdown 换行：
    &lt;br&gt;
</pre>
And you can also check the [offical document](https://www.markdownguide.org/basic-syntax/).

