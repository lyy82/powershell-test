# Markdown 説明文書作成

这是一个示例的 README 文件。

## Markdown 基本用法

Markdown 常见的基本用法

### 1.标题语法、

 #Heading level 1 也可用 =============== 表示 h1
 ##Heading level 2 也可用 --------------- 表示 h2

### 2.段落语法

要创建段落，请使用空白行将一行或多行文本进行分隔。
不要用空格（spaces）或制表符（ tabs）缩进段落。

### 3.换行语法

在一行的末尾添加两个或多个空格，  
然后按回车键,即可创建一个换行(br)。  

### 4.强调语法

要加粗文本，请在单词或短语的前后各添加 **两个星号**asterisks）或 下划线（underscores）。如需加粗一个 单词或短语 的中间部分用以表示强调的话，请在要加粗部分的两侧各添加两个星号（asterisks）。  
*斜体* 请在单词或短语前后添加一个星号（asterisk）或下划线（underscore）。要斜体突出单词的中间部分，请在字母前后各添加一个星号，中间不要带空格  
***really important粗体（Bold）和斜体（Italic）*** 单词或短语的前后各添加三个星号或下划线。要加粗并用斜体显示单词或短语的中间部分，请在要突出显示的部分前后各添加三个星号，后边要带个空格，中间不要带空格

### 5.引用语法

>多个段落的块引用
>
>块引用可以包含多个段落。为段落之间的空白行添加一个 > 符号。
>> 嵌套块引用
块引用可以嵌套。在要嵌套的段落前添加一个 >> 符号。

带有其它元素的块引用

> #### The quarterly results look great
>
> - Revenue was off the chart.
> - Profits were higher than ever.
> *Everything* is going according to **plan**.

### 6.列表语法

请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item、

- First item

### 7.代码语法

单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号
At the command prompt, type `nano`.  
``Use `code` in your Markdown file.``  

代码块
要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。
  &lt;html>
      &lt;head>
      &lt;/head>
    &lt;/html>  

### 8.分割线语法

分隔线语法
要创建分隔线，请在单独一行上使用三个或多个星号 (***)、破折号 (---) 或下划线 (___) ，并且不能包含其他内容。  前后均添加空白行
Try to put a blank line before...

---

...and after a horizontal rule.

### 9.链接语法

   ```bash
   git clone (https://markdown.com.cn/basic-syntax/ "最好的markdown教程")
  ```

### 10.图片语法

插入图片Markdown语法代码：![图片alt](图片链接 "图片title")。

[![沙漠中的岩石图片](./图片_20250917132103_10_1.jpg "Shiprock")](https://markdown.com.cn)

### 11.转义语法

| 字符      | 英文名称             | 中文意思 / Markdown 作用                                      |                              |    |    |                         |
| ------- | ---------------- | ------------------------------------------------------- | ---------------------------- | -- | -- | ----------------------- |
| `\`     | backslash        | **反斜杠**。用来转义特殊字符，例如 `\*` 可以显示 `*` 而不是变成斜体。              |                              |    |    |                         |
| `` ` `` | backtick         | **反引号**。用于代码标记，如 `` `code` `` 表示行内代码。                   |                              |    |    |                         |
| `*`     | asterisk         | **星号**。用作斜体 `*text*` 或粗体 `**text**`，或者列表符号。             |                              |    |    |                         |
| `_`     | underscore       | **下划线**。和星号一样，也可表示斜体 `_text_` 或粗体 `__text__`。           |                              |    |    |                         |
| `{ }`   | curly braces     | **大括号**。在标准 Markdown 中不常用，但某些扩展语法里用于占位或参数。              |                              |    |    |                         |
| `[ ]`   | brackets         | **方括号**。用来写链接文字 `[Google]` 或图片描述。                       |                              |    |    |                         |
| `( )`   | parentheses      | **圆括号**。配合方括号用来写链接地址，例如 `[Google](https://google.com)`。 |                              |    |    |                         |
| `#`     | pound sign       | **井号 / 号码符**。表示标题，`# 一级标题`，`## 二级标题` 等。                 |                              |    |    |                         |
| `+`     | plus sign        | **加号**。在 Markdown 列表中可作为无序列表符号之一。                       |                              |    |    |                         |
| `-`     | minus sign       | **减号 / 连字符**。无序列表符号，也可表示水平线 `---`。                      |                              |    |    |                         |
| `.`     | dot              | **点 / 句点**。有序列表符号，如 `1. 第一点`。                           |                              |    |    |                         |
| `!`     | exclamation mark | **感叹号**。和方括号配合写图片，例如 `![Alt text](image.jpg)`。          |                              |    |    |                         |
| \`      | \`               | pipe                                                    | **竖线 / 管道符**。在表格中表示列分隔，例如 \` | 列1 | 列2 | `。如果列内容里有竖线，需要转义`\|\`。 |

### 12.内嵌HTML标签

 这是Markdown格式

This is a regular paragraph.

| Foo |
|-----|

This is another regular paragraph.

如果不是必须用 HTML 表格，尽量用 Markdown 表格语法，这样兼容性最好，也不会报错。
