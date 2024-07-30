# Markdown语法

## 第一部分 基础语法

### 1.标题语法

形式：

第一种形式：#+空格  【几级标题就几个#】

第二种形式：在文本下方添加任意数量的==来标识一级标题，用“-”来标识二级标题
换行 末尾加2空格

### 2.段落语法

第一种形式：句后两空格。使用两个以上空格加上回车

第二种形式：使用空白行。段落后面使用一个空行来表示重新开始一个段落

### 3.换行语法

要创建段落，请使用空白行将一行或多行文本进行分隔。

### 4.强调语法

#### 4.1 粗体：

1.在文本的前后各添加两个星号

2.在文本的前后各添加两个下划线

注：句中加粗同理。一般建议使用星号

#### 4.2 斜体

1.在文本的前后各添加一个星号

2.在文本的前后各添加一个下划线

注：句中斜体同理。一般建议使用星号

#### 4.3 粗体+斜体

1.在文本的前后各添加三个星号

2.在文本的前后各添加三个下划线

### 5.引用

#### 5.1块引用

要创建块引用，请在段落前添加一个 `>` 符号。

#### **5.2多个段落的块引用**

块引用可以包含多个段落。为段落之间的空白行添加一个 `>` 符号。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/910e5cda-126a-42ef-9359-e8d87822e01a/Untitled.png)

#### **5.3嵌套块引用**

块引用可以嵌套。在要嵌套的段落前添加一个 `>>` 符号。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/1096ab97-a59d-416b-8cf0-761fa90308c6/Untitled.png)

#### 5.4**带有其它元素的块引用**

块引用可以包含其他 Markdown 格式的元素。并非所有元素都可以使用，你需要进行实验以查看哪些元素有效。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/62aceb50-a223-4a96-b43f-d2ee31edc1e6/Untitled.png)

### 6.列表语法

#### 6.1有序列表

要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。

#### **6.2无序列表**

要创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表。

#### **6.3在列表中嵌套其他元素**

要在保留列表连续性的同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符，

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/154da411-b5c3-400e-aeac-5dc0e2be67fd/Untitled.png)

#### **6.4代码块**

[**代码块**](https://markdown.com.cn/basic-syntax/lists.html#code-blocks)通常采用四个空格或一个制表符缩进。当它们被放在列表中时，请将它们缩进八个空格或两个制表符。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/f724d06a-92eb-4835-897d-3de3cd7f5716/Untitled.png)

### 7.代码语法

要将单词或短语表示为代码，请将其包裹在反引号 (```) 中。

#### **转义反引号**

如果你要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号(````)中。

#### **代码块**

要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。


### 8.分割线语法

要创建分隔线，请在单独一行上使用三个或多个星号 (`***`)、破折号 (`---`) 或下划线 (`___`) ，并且不能包含其他内容。

### 9.链接语法

链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。

超链接Markdown语法代码

`[超链接显示名](超链接地址 "超链接title")`

#### **9.1给链接增加 Title**

链接title是当鼠标悬停在链接上时会出现的文字，这个title是可选的，它放在圆括号中链接地址后面，跟链接地址之间以空格分隔。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/78ac3023-0b4b-4e24-ad4f-5a4227bf691d/Untitled.png)

#### **9.2网址和Email地址**

使用尖括号可以很方便地把URL或者email地址变成可点击的链接。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/5fc435d0-7828-43eb-9a50-276c6864b2f4/Untitled.png)

渲染效果

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/48e99070-3f4b-4b18-beed-be79b178f92e/Untitled.png)

#### **9.3带格式化的链接**

[**强调**](https://markdown.com.cn/basic-syntax/links.html#emphasis) 链接, 在链接语法前后增加星号。 要将链接表示为代码，请在方括号中添加反引号。

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/8ffc19e3-5cd3-4af7-8515-a892ac9c7a6f/Untitled.png)

渲染效果

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/115b7918-0683-4941-ad6f-150dc4ca2eb8/2faad268-41e2-42f5-b271-2d2d5a21a806/Untitled.png)

#### **9.4引用类型链接**

引用样式链接是一种特殊的链接，它使URL在Markdown中更易于显示和阅读。参考样式链接分为两部分：与文本保持内联的部分以及存储在文件中其他位置的部分，以使文本易于阅读。

##### **9.4.1链接的第一部分格式**

引用类型的链接的第一部分使用两组括号进行格式设置。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接。

尽管不是必需的，可以在第一组和第二组括号之间包含一个空格。第二组括号中的标签不区分大小写，可以包含字母，数字，空格或标点符号。

以下示例格式对于链接的第一部分效果相同：

- `[hobbit-hole][1]`
- `[hobbit-hole] [1]`

##### **9.4.2链接的第二部分格式**

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

### 10.图片语法

要添加图像，请使用感叹号 (`!`), 然后在方括号增加替代文本，图片链接放在圆括号里，括号里的链接后可以增加一个可选的图片标题文本。

插入图片Markdown语法代码：`![图片alt](图片链接 "图片title")`。

对应的HTML代码：`<img src="图片链接" alt="图片alt" title="图片title">`

`![这是图片](/assets/img/philly-magic-garden.jpg "Magic Gardens")`

渲染效果如下：

图片.png

#### **链接图片**

给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中。

`[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)`

渲染效果如下：

图片.png


## 第二部分 扩展语法

### 11.表格
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

#### 11.1 表格对齐
在标题行中的连字符的左侧，右侧或两侧添加冒号，将列中的文本对齐到左侧，右侧或者中心
表格中也可以添加链接
您可以使用表格的HTML字符代码（&#124;）在表中显示竖线（|）字符。
### 12.Markdown 围栏代码块
Markdown基本语法允许您通过将行缩进四个空格或一个制表符来创建代码块。如果发现不方便，请尝试使用受保护的代码块。根据Markdown处理器或编辑器的不同，您将在代码块之前和之后的行上使用三个反引号（(```）或三个波浪号（~~~）。
#### 语法高亮
许多Markdown处理器都支持受围栏代码块的语法突出显示。使用此功能，您可以为编写代码的任何语言添加颜色突出显示。要添加语法突出显示，请在受防护的代码块之前的反引号旁边指定一种语言。
### 13. Markdown 脚注
脚注使您可以添加注释和参考，而不会使文档正文混乱。当您创建脚注时，带有脚注的上标数字会出现在您添加脚注参考的位置。读者可以单击链接以跳至页面底部的脚注内容。

要创建脚注参考，请在方括号（[^1]）内添加插入符号和标识符。标识符可以是数字或单词，但**不能包含空格或制表符**。标识符仅将脚注参考与脚注本身相关联-在输出中，**脚注按顺序编号**。

在括号内使用另一个插入符号和数字添加脚注，并用冒号和文本（[^1]: My footnote.）。您不必在文档末尾添加脚注。您可以将它们放在除列表，块引号和表之类的其他元素之外的任何位置。
### 14.标题编号
许多Markdown处理器支持标题的自定义ID - 一些Markdown处理器会自动添加它们。添加自定义ID允许您直接链接到标题并使用CSS对其进行修改。要添加自定义标题ID，请在与标题相同的行上用大括号括起该自定义ID。
示例
`my great heading {#custom-id}`


#### 链接到标题ID (#headid)
通过创建带有数字符号（#）和自定义标题ID的[标准链接]((/basic-syntax/links.html)，可以链接到文件中具有自定义ID的标题。

### 15.定义列表
一些Markdown处理器允许您创建术语及其对应定义的定义列表。要创建定义列表，请在第一行上键入术语。在下一行，键入一个冒号，后跟一个空格和定义。
`First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.`

渲染结果：
`First Term

    This is the definition of the first term.

Second Term

    This is one definition of the second term.

    This is another definition of the second term.`
### 16.markdown 删除线
您可以通过在单词中心放置一条水平线来删除单词。结果看起来像这样。此功能使您可以指示某些单词是一个错误，要从文档中删除。若要删除单词，请在单词前后使用两个波浪号~~。
`~~123456~~`
~~明天更美好~~
### 17.Markdown 任务列表语法
任务列表使您可以创建带有复选框的项目列表。在支持任务列表的Markdown应用程序中，复选框将显示在内容旁边。要创建任务列表，请在任务列表项之前添加破折号-和方括号[ ]，并在[ ]前面加上空格。要选择一个复选框，请在方括号[x]之间添加 x 。   
`- [X] 第一件事`  
`- [ ] 第二件事`  
`- [ ] 第三件事`  

渲染效果：
- [X] 第一件事
- [ ] 第二件事
- [ ] 第三件事
### 18.Markdown 使用 Emoji 表情
有两种方法可以将表情符号添加到Markdown文件中：将表情符号复制并粘贴到Markdown格式的文本中，或者键入emoji shortcodes(https://emojipedia.org/)。

#### 18.1 复制和粘贴表情符号
在大多数情况下，您可以简单地从Emojipedia 等来源复制表情符号并将其粘贴到文档中。许多Markdown应用程序会自动以Markdown格式的文本显示表情符号。从Markdown应用程序导出的HTML和PDF文件应显示表情符号。

Tip: 如果您使用的是静态网站生成器，请确保将HTML页面编码为UTF-8。.
#### 18.2 使用表情符号简码
一些Markdown应用程序允许您通过键入表情符号短代码来插入表情符号。这些以冒号开头和结尾，并包含表情符号的名称。

去露营了！ :tent: 很快回来。

真好笑！ :joy:
呈现的输出如下所示：

去露营了！⛺很快回来。

真好笑！😂

Note: 注意：您可以使用此表情符号简码列表，但请记住，表情符号简码因应用程序而异。有关更多信息，请参阅Markdown应用程序的文档。
### 19.自动网址链接
许多Markdown处理器会自动将URL转换为链接。这意味着如果您输入http://www.example.com，即使您未使用方括号，您的Markdown处理器也会自动将其转换为链接。

http://www.example.com
呈现的输出如下所示：

http://www.example.com

#禁用自动URL链接
如果您不希望自动链接URL，则可以通过将URL表示为带反引号的代码来删除该链接。

`http://www.example.com`
呈现的输出如下所示：

http://www.example.com

### 20.公式语法
语法
`$...$`
`$$...$$`
使用KaTeX或者MathJax来渲染数学表达式
$...$  或者 \(...\)中的数学表达式将会在行内显示
$$...$$或者 \[...\] 或者 ```math 中的数学表达式将会在块内显示。


---
*至此基本语法与扩展语法整理完毕，后续会主要对latex进行深入了解*  
整理时间：*2021-07-30*  
整理人：*ISereino*  
