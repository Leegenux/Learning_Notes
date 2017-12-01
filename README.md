# Markdown_notes
#### markdown的段落是由空行标定的

> 此处和python的统一性: python的空格也有的有严格定义, 有的没有.

> 差异化: 此处的空行上只要没有非空字符(所以可以堆积一些制表符) 而python则不同.

#### 标题

> 两种: Setext 用底线 (两行, 类似于emphasize)

> atx: 用#

#### 区块引用:

> 用>, 在>右边的内容又好像在另一个文本内, 而左边的这一列>就类似于一栋墙, 这也就和"嵌套"用法相合了(同样也和别的语法在内部使用相合)

>> 差异化: 只用一个>是什么鬼>这瞬间就像变成了一个命令行了(没错fish)

#### 列表

> 有序和无序: 只要保证一点 (语法使用正确)

> 注意数字的正确性不是必须的, 只要是数字即可.

> 代表列表结束可以尝试空行, 但是如果你**保持缩进**, 你永远结束不了. 

> "\."可以解除列表.

>> 这和C语言缩进规范或者Python的缩进规则相统一.

#### 链接:
> 参考式 和 行内式

>> 统一性: 先网页, 后接一个标题字符串 标题"title"可以用双引号, 单引号. 

>> 差异化: 行内就在括号里面直接弄内容, 而参考式则是分立式的 ; 另外: " 参考式的title还可以用括号, 其网址可以用尖括号括起来.

>> 注意: 参考式中, 标签并不区分大小写.

>> 还有就是可以省去标记, 并将链接文字直接作为"链接标签".

#### 强调

> 星号或者下划线.  一个表示斜体, 两个表示粗体
.
> 重点是: 强调一定要和文字紧密结合.

> 然后其他的非紧密结合的都算是单独的符号.

> 总之, 这和C语言的*运算符或者%d这类

>> 统一处: 组合生效, 使用转义序列进行代替等

>> 差异化: markdown强调一定要紧密结合.

#### 代码:

> 一个是缩进代码, 一个是引用: 用键盘左上角的~ 下面的 `标定.

> 同时, 可以用成对的 连续多个``来达到相同的目的, 同时和内部的`区分开来.

>> 和强调或者区块引用的统一性:(强调) 配对非常重要. (区块引用) 通过控制数量

>> 差异化: ....比较多

#### 图片:

> 除了那个感叹号, 其余地方和超链接完全一样.

---
