[toc]
##### 无法打开侧边预览，重启软件（重启电脑）
#### 一、标题的使用和转义字符
使用 # 表示标题，其中 # 号必须在行首，##二级标题，**特殊字符无法打出前缀\即可打出。**
####二、粗体与斜体
用一对*括起来为斜体，两对为粗体，三对为又粗又斜体，可以选中在加粗。
#### 三、分割线的使用
使用三个以上及以上的***或---，独占一行。
#### 四、文字上划线表示删除
用两个~为一边括起来，可在文字上划线。
#### 五、超链接与图片写法
第一个方括号为链接名（图片介绍），后紧接一个[]或()写链接。而图片前加一个！即可。
#### 六、列表
6.1.无序列表：使用‘-’ ‘+’ ‘*’表示无序列表，可嵌套。
6.2.有序列表：<数字.两个空格>
#### 七、区块
markdown区块是在段落开头使用 “>”，依然是紧跟空格，可嵌套使用，如“>>”表示第一区块内的又一区块。
#### 八、代码插入
8.1.一行用单引号括起来，多行用三个为一组单引号括起来。
#### 九、表格
每排单元格要用| 分开 表头与内容用 — 分开，加:可以实现左对齐，右对齐，居中。不加则默认为左对齐。
eg：
“|  表头   | 表头  | 表头 | 表头 |
| :---  | ---:  | :--: | ---- |
| 单元格  | 单元格 |单元格|单元格|
| 单元格  | 单元格 |单元格|单元格|”

|  表头   | 表头  | 表头 | 表头 |
| :---  | ---:  | :--: | ---- |
| 单元格  | 单元格 |单元格|单元格|
| 单元格  | 单元格 |单元格|单元格|
***
#### 十、标签
1.  不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。
<h1>一级标题</h1>
<h2>二级标题</h2> 
<h3>三级标题</h3>
<p>段落标签</p>

2.  hgroup标签主要作用是用来为标题分组，可以将一组相关的标题放到hgroup里面。
+  第一em标签的样式是斜体，而strong标签的样式是加粗
+  第二em标签是强调语义的，而strong标签是强调内容的
+   q标签和blockquote标签都是引用，不同的是q标签是短引，用而blockquote标签是长引用会换行的。
+   br标签的作用是，强制换行，它是一个自结束标签。
+    hr标签就是给页面加一个分割线,这个del标签就是删除标签
+    center标签的作用就是剧中，把文字啊图片啊啥的全部居中到页面中间
+     div标签是用来布局的，并没有语义，只是一个区块。
+     span标签，没有语义，一般用来包裹文字,让文字更好被选中。
+     b是加粗

#### 十二、
+ 创建目录：在需要的地方输入[toc\]
***
# GitHub
1. 终端输入git可查看常用命令
## 上传文件
查看->终端
git add markdown-help.md
git commit -m "newfile"
git branch -M main
git push -u origin main（-f强制推送）
443错误：git config --global --unset http.proxy
        git config --global --unset https.proxy
        <font color='red'> C </font>