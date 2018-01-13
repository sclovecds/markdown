#### Markdown 标记区块引用是使用类似 email 中用 > 的引用方式。如果你还熟悉在 email 信件中的引言部分，你就知道怎么在 Markdown 文件中建立一个区块引用，那会看起来像是你自己先断好行，然后在每行的最前面加上 >


###### Markdown 也允许你偷懒只在整个段落的第一行最前面加上 >
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

###### 区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > 
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

###### 引用的区块内也可以使用其他的 Markdown 语法，包括标题、列表、代码区块等
> ## 这是一个标题
>
> 1. 这是第一个列表项
> 2. 这是第二个列表项
> 给出一些例子代码
>
> return shell_exec("echo $input | $markdown_script");