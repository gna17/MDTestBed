# This is a testbed for markdown editing!

# 这里是markdown试验田！
## 我是atx格式的二级标题，1到6个井号决定级别


我是settext格式一级标题，下一行有任意个数的等号
==
我是settext格式二级标题，下一行有任意个数的减号
-

## 教程  
我是教程：https://markdown.cn/

## HTML格式段落引用  
<table>
    <tr>
        <td>
         我是一个普通段落<br/>
         我是在在 HTML 区块标签间的<br/>
         Markdown 格式语法将不会被处理!
        </td>
    </tr>
</table>

一些corner cases： AT&T AT&amp;T &copy; 4 < 5 4 &lt; 5

## 列表和代码区块用法  
要在md文件中使用一个代码区块，下面空一行，左边打四个tab！

    我是md文件里面的一个代码区块！
    Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

>我是区块引用  
我是第二行，换行在句尾打两个空格，然后一个回车！
>>我是嵌套引用！
>区块内也可以用markdown 语法！
>>1. 我是猫咪
>>2. 我是小兔子  
以下顺序不变，序号按数字调整了哟！
>>3. Bird
>>1. McHale
>>8. Parish

        <  
        一列表项包含一个列表区块  
        我是一个列表中的代码区块！   
        我在一个列表里，我前面有8个tab，我上面有一个空行  
        >

这两种缩进都可以
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
    
        <我是一个代码区块！我在一个列表里，我前面有8个tab，我上面有一个空行>
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.

        <我是一个代码区块！我在一个列表里，我前面有8个tab，我上面有一个空行>

注意！行首出现数字-句点-空白，要避免这样的状况，在句点前面加上反斜杠, 也就是backslash, 就是backspace key 下面那个。  
这样不好：1986. What a great season.  
这样好：1986\. What a great season.

列表：

  * 張三
  * 李四
  * 王二

編號列表：

  1. 不論
  2. 三七
  3. 二十一

## 分隔线  
一行中用3个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：

---

* * *

***

*****

- - -

---------------------------------------

## MISC  
段落之间打空格。  
行末打两个空格，产生断行  
文本属性：_我是italic_、**我是bold**、`我是等宽字形Monospace`。

[連結](http://example.com)

![Image](https://i.ibb.co/dQPh7cV/Screenshot-Wikipedia-Markdown.png)

> Markdown使用電郵用字元「>」來引用。

行間<abbr title="Hypertext Markup Language">HTML</abbr>亦受支援。

## 超链接引用方式  
行内式和参考式都行。  
链接文字用 [方括号] 来标记。  
要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可  
如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可  
例如：  

    This is [an example](http://example.com/ "Title") inline link.
    [This link](http://example.net/) has no title attribute.
如果你是要链接到同样主机的资源，你可以使用相对路径：

    See my [About](/about/) page for details.
参考式的链接是在链接文字的括号后面再接上另一个方括号，而在第二个方括号里面要填入用以辨识链接的标记：

    This is [an example][id] reference-style link.
你也可以选择性地在两个方括号中间加上一个空格：

    This is [an example] [id] reference-style link.
接着，在文件的任意处，你可以把这个标记的链接内容定义出来：

    [id]: http://example.com/  "Optional Title Here"

## 强调  
to be added later...
## 代码  
to be added later...
## 图片
to be added later...
