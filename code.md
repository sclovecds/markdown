### 代码区块

#### 要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以，例如，下面的输入

这是一个普通的段落

    这是一个代码区块

    <div class="wrap">
        <p>Hello Markdown!</p>
    </div>


#### 链接
##### 链接文字都是用 [方括号] 来标记
###### 要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可，例如

This is [an example](http://example.com/ "Title") inline link.

[this link](http://example.net/) has no title attribute

#### 参考式的链接是在链接文字的括号后面再接上另一个方括号，而在第二个方括号里面要填入用以辨识链接的标记：

This is [an example][id] reference-style link.

你也可以选择性地在两个方括号中间加上一个空格：

This is [an example] [id] reference-style link.

接着，在文件的任意处，你可以把这个标记的链接内容定义出来：

[id]: http://example.net/ "Optional Title Here"

###### 链接内容定义的形式为：
*   方括号（前面可以选择性地加上至多三个空格来缩进），里面输入链接文字
*   接着一个冒号
*   接着一个以上的空格或制表符
*   接着链接的网址
*   选择性地接着 title 内容，可以用单引号、双引号或是括弧包着
    
    [foo]: http://example.net/ "Optional Title Here"
    [foo]: http://example.net/ 'Optional Title Here'
    [foo]: http://example.net/ (Optional Title Here)