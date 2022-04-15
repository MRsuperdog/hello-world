# hello-world
My first repository

# 关于 Markdowm 的简明教程

标签： Markdown

---

### 1.斜体和粗体

使用 * 和 ** 表示斜体和粗体

示例：

这是*斜体*，这是**粗体**。

### 2.分级标题

使用 === 表示一级标题，使用---表示二级标题。

实例：

```
这是一个一级标题
=========================

这是一个二级标题
---------------------------------------------

### 这是一个三级标题
```

你也可以选择在行首加井号表示不同级别的标题（H1-H6）

### 3.外链接

使用\[描述]（链接地址）为文字增加外链接。

示例：

这是去往 [本人博客](https://github.com/MRsuperdog) 的链接。

### 4.无序列表

使用*，+，- 表示无序列表。

示例：

- 无序列表项 一
- 无序列表项 二
- 无序列表项 三

### 5.有序列表

使用数字和点表示有序列表。

示例：

1. 有序列表项 一
2. 有序列表项 二
3. 有序列表项 三

### 6.文字引用

使用 > 表示文字引用。

示例：

> 野火烧不尽，春风吹又生。

### 7.行内代码块

使用\`代码`表示行内代码块。

示例：

让我们聊聊`html`。

### 8.  代码块

使用 四个缩进空格 表示代码块。

示例：

    这是一个代码块，此行左侧有四个不可见的空格。
    
### 9. 插入图像

使用 \!\[描述](图片链接地址) 插入图像。

示例：

![你的头像](https://avatars.githubusercontent.com/u/88034260?s=400&u=4b13eca6d48c846200ceca718de15db65e5250c6&v=4)

# Markdowm 高阶语法手册

### 1.内容目录

在段落中填写 `[TOC]` 以显示全文内容的目录结构。

[TOC]

### 2. 标签分类

在编辑区任意行的列首位置输入以下代码给文稿标签：

标签： 数学 英语 Markdown

或者

Tags： 数学 英语 Markdown

### 3. 删除线

使用 ~~ 表示删除线。

~~这是一段错误的文本。~~

### 4. 注脚

使用[^keyword]表示注脚。

这是一个注脚[^footnote]的样例。

这是第二个注脚[^footnote2]

### 5. LaTeX 公式

$ 表示行内公式：

质能守恒方程可以用一个很简洁的方程式 $E=mc^2$ 来表达。

$$ 表示整行公式：

$$\sum_{i=1}^n a_i=0$$

$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$

$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$

访问 [MathJax](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)参考更多使用方法。

### 6.加强的代码块

支持四十一种编程语言的语法高亮的显示，行号显示。

非代码示例：

```
$ sudo apt-get install vim-gnome
```

Python示例：

```python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print(Greater)
    return(param2 - param1 + 1) or None
    
class SomeClass:
    pass
    
>>> message = '''interpreter
... prompt'''
```

### 7. 流程图

#### 示例

```flow
st=>start: Start:>https://www.zybuluo.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```

#### 更多语法参考：[流程图语法参考](http://adrai.github.io/flowchart.js/)

### 8. 表格支持

|   项目    |价格   |数量  |
|-------   |----:  |:----:  |
|   计算机    |\$1600   |5  |
|   手机    |\$12   |12  |
|   管线    |\$1    |234  |

### 9. 待办事宜 Todo 列表

- [ ] **一月旅行准备**
    - [ ] 准备邮轮上需要携带的物品
    - [ ] 浏览日本免税店的物品
    - [x] 购买蓝宝石公主号一月一日的船票


    
[^footnote]: 这是一个 *注脚* 的 **文本**

[^footnote2]: 这是一个 *注脚* 的 **文本**
