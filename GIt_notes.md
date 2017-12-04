# git笔记   
[TOC]   
*** 
# 1. 常用命令 git config / git status / git add / git init  / git diff / git commit
# 2. .gitignore  
常见:   
1. *.c  
2. []
3. /
4. !    
> 1. \* 与 printf和scanf中的 * 具有差异性: 此处是任意, 而在格式位串中是可变或者忽略.   但是某种程度上,它们又是统一的 (此处\*好像是一种融合).     
> 2. []与| 差异性在于, 前者是只取一个, 而后者是只要存在即可. 但是统一性在于, 前者的结果是可以归结为后者, 而后者, 在C语言中也和前者一致.   
> 3. /表明文件目录层级关系。    
> 4. !表示取反。    

# 3.git config     
一个参数:global system
两个对象:user,core.
# 4.git commit 两个常用选项参数    
1. *-m* message 表示此次提交的附带消息.    
2. *-a* 直接提交所有被跟踪的文件。

# 5.关于git的一些基本概念:
1. branch  
branch类似于河流的分流与汇合 (feature, merge)

2. 总之, commit 是对branch进行更改  
pull request 是将branch与master汇合


3. git文件的三种状态    
已提交  
已修改  
已暂存  

4. $ git config --global user.name "John Doe"   
$ git config --global user.email johndoe@example.com

这命令行    
差异化: 参数竟然要强调 “字符串”     
统一化: 其他的主要参数都在命令行中体现，目标，附带参数，主动者，，，
