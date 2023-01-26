## Markdown 标题语法

创建标题，请在单词或短语前面添加井号(#) ，它的数量代表了标题的级别。

## Markdown 段落

创建段落，使用 **空白行** 将一行或多行文本进行分隔。

## Markdown 换行语法

在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行标签 br。  

## Markdown 强调语法

### 粗体（Bold)

加粗文本，请在单词或短语的前后各添加两个星号（asterisks）或下划线（underscores）。

### 斜体（Italic）

斜体显示文本，请在单词或短语前后添加一个星号（asterisk）或下划线（underscore）。

## Markdown 引用语法

- 创建块引用，请在段落前添加一个 > 符号。

>Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor

- 块引用可以嵌套。在要嵌套的段落前添加一个 >> 符号。

>Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor

## Markdown 列表语法

- 有序列表

创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。

- 无序列表

创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表。

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## Markdown 代码语法

单词或短语表示为代码，请将其包裹在反引号 (`) 中。

要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号(``)中。

## 代码块

创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。

## Markdown 分隔线语法

创建分隔线，请在单独一行上使用三个或多个星号 (***)、破折号 (---) 或下划线 (___) ，并且不能包含其他内容。

---

## Markdown 链接语法

链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。

超链接Markdown语法代码：[超链接显示名](超链接地址 "超链接title")

- 网址和Email地址  
<https://markdown.com.cn>
<fake@example.com>

- 引用类型链接
[asdfas][1]

[1]: www.baidu.com

## Markdown 图片语法

插入图片Markdown语法代码：![图片alt](图片链接 "图片title")。

- 链接图片
给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中。

[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)

    #include<stdio.h>
    int main()
    {
        int a = 3;
        return 0;
    }