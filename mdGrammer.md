# <iframe src="https://www.baidu.com" />

## Overview

说明：本文档按Typora官方文档结构组织，Typora采用Github Flavored Markdown 

## Block Elements

### Paragraph and line break

better to use <kbd>enter</kbd> making two single lines to begin a new Paragraph.

### Headers

use from one to six **\#** to differ the header level

```markdown
# 一级标题
#### 四级标题 
```

### Blockquotes

use > and support nestblocked block quote by continuing to write a sub >

```markdown
> 鲁迅说：
> > 刘和珍说：
```

### Lists

```markdown
~ unordered list, use * or + or -
* item1
* item2

~ ordered list
1. item1
2. item2

~ task list ,useless and ignore
```

### Code Blocks

```markdown
​``` java 
    code
​```
```

### Math Blocks

```latex
~ use $$ to support Tex/LaTex
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$
```

find more about [this](http://support.typora.io/Math/)

### Tables

```markdown
~ in second line to use :--, --:, :--: to make left, right, or center-aligned 
| header1 | header2 |
|  :---    |   ---   |
| content1|content2 |
```

### Footnotes

```markdown
“一览众山小”[^fn1]和“不识庐山真面目，只缘身在此山中”[^fn2]是学习的两种状态，它们是时刻共存的。
[^fn1]: 出自杜甫的诗《泰山》
[^fn2]:出自苏轼的诗《题西林壁》
```

### Horizontal Rules

use *** or --- to draw a horizontal line.

### YAML Front Matter

find more about [this](http://jekyllrb.com/docs/frontmatter/)

### Table of Contents (TOC)

enter **[toc]** to make a catalog.

## Span Elements

### Links

```markdown
~ Inline Links
[Caffeine Uses, Effects & Safety Information](https://www.drugs.com/caffeine.html)

~ Internal Links:jump to the appointed headers
You can refer to Section[Horizontal Rules](#horizontal-rules) in this eaasy.

~ Reference Links
example1:
    This is [an example][id] reference-style link.
    [id]: http://example.com/  "Optional Title Here"
example2: omit the id and use name to cite
	This is [an example][] reference-style link.
    [an example]: http://example.com/  "Optional Title Here"
```

### Images

```markdown
![I cannot stop to cry](/cry.jpg)
```

PS: about specify a URL prefix via editing YAML Front Matter while building website.

### Emphasis and Strong

```markdown
~ use * or _ to emphasis(to be italic)
*hello* , _good bye_

~ use ** or __ to be strong
**hello**, __good bye__
```

### Code

```markdown
~ write code within a normal paragraph
Use the `printf()` function
```

### Strikethrough

`~~Mistaken text.~~` becomes ~~Mistaken text.~~

### Inline Math

```markdown
$\lim_{x \to \infty} \exp(-x) = 0$
```

### Subscript, Superscript, Highlight

just support in Typora if you enable it in setting.

## HTML

### Underline

```html
<u>s</u>
```

### Embed Contents

<iframe height='265' scrolling='no' title='Fancy Animated SVG Menu' src='http://codepen.io/jeangontijo/embed/OxVywj/?height=265&theme-id=0&default-tab=css,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'></iframe>

### Video

`<video src="x.mp4"/>`

### More

HTML Tag、转义、公式

mermaid: [Doc](https://mermaid-js.github.io/mermaid/#/), online Editor

```mermaid
gantt
dateFormat  YY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 14-01-10

section A section
Completed task            :done,    des1, 14-01-06,14-01-08
Active task               :active,  des2, 14-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, 13-01-09, 50000000d
```



### Math

向量积
$$
\mathbf{K}_1 \times \mathbf{V}_2
$$


三阶矩阵
$$
\begin{vmatrix}
\mathbf{p} & \mathbf{q} & \mathbf{r} \\
\frac{\partial M}{\partial p} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$


分段函数
$$
函数名=\begin{cases}
公式1 & 条件1 \\
公式2 & 条件2 \\
公式3 & 条件3 
\end{cases}
$$
