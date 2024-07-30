# 1.标题语法

形式：

第一种形式：#+空格  【几级标题就几个#】

第二种形式：在文本下方添加任意数量的==来标识一级标题，用“-”来标识二级标题
换行 末尾加2空格

# 2.段落语法

第一种形式：句后两空格。使用两个以上空格加上回车

第二种形式：使用空白行。段落后面使用一个空行来表示重新开始一个段落

# 3.换行语法

要创建段落，请使用空白行将一行或多行文本进行分隔。

# 4.强调语法

## 4.1 粗体：

1.在文本的前后各添加两个星号

2.在文本的前后各添加两个下划线

注：句中加粗同理。一般建议使用星号

## 4.2 斜体

1.在文本的前后各添加一个星号

2.在文本的前后各添加一个下划线

注：句中斜体同理。一般建议使用星号

## 4.3 粗体+斜体

1.在文本的前后各添加三个星号

2.在文本的前后各添加三个下划线

# 5.引用

## 5.1块引用

要创建块引用，请在段落前添加一个 `>` 符号。

## **5.2多个段落的块引用**

块引用可以包含多个段落。为段落之间的空白行添加一个 `>` 符号。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/910e5cda-126a-42ef-9359-e8d87822e01a/Untitled.png)

## **5.3嵌套块引用**

块引用可以嵌套。在要嵌套的段落前添加一个 `>>` 符号。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/1096ab97-a59d-416b-8cf0-761fa90308c6/Untitled.png)

## 5.4**带有其它元素的块引用**

块引用可以包含其他 Markdown 格式的元素。并非所有元素都可以使用，你需要进行实验以查看哪些元素有效。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/62aceb50-a223-4a96-b43f-d2ee31edc1e6/Untitled.png)

## 6.列表语法

## 6.1有序列表

要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。

## **6.2无序列表**

要创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表。

## **6.3在列表中嵌套其他元素**

要在保留列表连续性的同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符，

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/154da411-b5c3-400e-aeac-5dc0e2be67fd/Untitled.png)

## **6.4代码块**

[**代码块**](https://markdown.com.cn/basic-syntax/lists.html#code-blocks)通常采用四个空格或一个制表符缩进。当它们被放在列表中时，请将它们缩进八个空格或两个制表符。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/f724d06a-92eb-4835-897d-3de3cd7f5716/Untitled.png)

# 7.代码语法

要将单词或短语表示为代码，请将其包裹在反引号 (```) 中。

### **转义反引号**

如果你要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号(````)中。

### **代码块**

要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。

---

# 8.分割线语法

要创建分隔线，请在单独一行上使用三个或多个星号 (`***`)、破折号 (`---`) 或下划线 (`___`) ，并且不能包含其他内容。

# 9.链接语法

链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。

超链接Markdown语法代码

`[超链接显示名](超链接地址 "超链接title")`

## **9.1给链接增加 Title**

链接title是当鼠标悬停在链接上时会出现的文字，这个title是可选的，它放在圆括号中链接地址后面，跟链接地址之间以空格分隔。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/78ac3023-0b4b-4e24-ad4f-5a4227bf691d/Untitled.png)

## **9.2网址和Email地址**

使用尖括号可以很方便地把URL或者email地址变成可点击的链接。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/5fc435d0-7828-43eb-9a50-276c6864b2f4/Untitled.png)

渲染效果

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/48e99070-3f4b-4b18-beed-be79b178f92e/Untitled.png)

## **9.3带格式化的链接**

[**强调**](https://markdown.com.cn/basic-syntax/links.html#emphasis) 链接, 在链接语法前后增加星号。 要将链接表示为代码，请在方括号中添加反引号。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/8ffc19e3-5cd3-4af7-8515-a892ac9c7a6f/Untitled.png)

渲染效果

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/2faad268-41e2-42f5-b271-2d2d5a21a806/Untitled.png)

## **9.4引用类型链接**

引用样式链接是一种特殊的链接，它使URL在Markdown中更易于显示和阅读。参考样式链接分为两部分：与文本保持内联的部分以及存储在文件中其他位置的部分，以使文本易于阅读。

### **9.4.1链接的第一部分格式**

引用类型的链接的第一部分使用两组括号进行格式设置。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接。

尽管不是必需的，可以在第一组和第二组括号之间包含一个空格。第二组括号中的标签不区分大小写，可以包含字母，数字，空格或标点符号。

以下示例格式对于链接的第一部分效果相同：

- `[hobbit-hole][1]`
- `[hobbit-hole] [1]`

### **9.4.2链接的第二部分格式**

引用类型链接的第二部分使用以下属性设置格式：

1. 放在括号中的标签，其后紧跟一个冒号和至少一个空格（例如`[label]:`）。
2. 链接的URL，可以选择将其括在尖括号中。
3. 链接的可选标题，可以将其括在双引号，单引号或括号中。

以下示例格式对于链接的第二部分效果相同：

- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)`

可以将链接的第二部分放在Markdown文档中的任何位置。有些人将它们放在出现的段落之后，有些人则将它们放在文档的末尾（例如尾注或脚注）。

注：**不同的 Markdown 应用程序处理URL中间的空格方式不一样。为了兼容性，请尽量使用%20代替空格。**

# 10.图片语法

要添加图像，请使用感叹号 (`!`), 然后在方括号增加替代文本，图片链接放在圆括号里，括号里的链接后可以增加一个可选的图片标题文本。

插入图片Markdown语法代码：`![图片alt](图片链接 "图片title")`。

对应的HTML代码：`<img src="图片链接" alt="图片alt" title="图片title">`

`![这是图片](/assets/img/philly-magic-garden.jpg "Magic Gardens")`

渲染效果如下：

图片.png

## **链接图片**

给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中。

`[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)`

渲染效果如下：

图片.png

# 11.表格
添加表格需要  
`|标题行|内容|`  
`|---|---|`  
`|text1|tex2|`  
渲染效果
|标题行|内容| 
|---|---|  
|text1|tex2|

其中短划线可以用来控制单元格的长度
[也可以使用在线网站生成列表，然后复制格式到md文件中](https://www.tablesgenerator.com/markdown_tables# "点击链接到达在线生成列表")  
Markdown tables generator:https://www.tablesgenerator.com/markdown_tables#

## 11.1
