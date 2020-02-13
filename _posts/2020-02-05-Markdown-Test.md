---
layout: post
title: Markdown modules test
date: 2020-2-05
categories: test
tags: [test]
descrpition: "Markdown modules test"

---
### plain text display
Hello World!

### image display
<img src="{{ "/img/post_img/PX4_logo.png" | | prepend: site.baseurl}}" alt="PX4 logo">

### code display1
```
#include <stdio.h>
int main(){
    printf("Hello World!");
    std::cout<<"Hello World!"<<std::endl;
    return 0；
}
```
### code display2
<pre>
#include &lt;stdio.h&gt;
int main(){
    printf("Hello World!");
    return 0；
}
</pre>

### LaTeX Math formula display
$$ c = \sqrt{a^{2}+b_{0}^{2} +e^{x}} $$