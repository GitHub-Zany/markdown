# MarkDown
###### （纯文本格式的标记语言）

## 标题
```
语法：# 一级标题
```
# 一级标题
```
语法：## 二级标题
```
## 二级标题
```
语法：### 三级标题
```
### 三级标题
```
语法：#### 四级标题
```
#### 四级标题
```
语法：##### 五级标题
```
##### 五级标题
```
语法：###### 六级标题
```
###### 六级标题
* 文字前加\#即可。一个\#表示一级标题，二个\#表示二级标题，依次类推，一共有六级。
  *注意：使用时符号和文字中间要用空格隔开。*[^1]

## 分割线
```
语法：---
```
---
```
语法：***
```
***
* 三个或者三个以上的\-或者\*单独一行，两者效果相同。

## 字体
### 加粗
```
语法：**加粗**
```
* **加粗**
```
语法：<b>加粗</b>
```
* <b>加粗</b>


* 文字左右分别用两个\*或\<b>标签包裹起来。

### 斜体
```
语法：*斜体*
```
* *斜体*
```
语法：_斜体_
```
* _斜体_
```
语法：<i>斜体</i>
```
* <i>斜体</i>


* 文字左右分别用一个\*或一个\_或\<i>标签包裹起来。

### 斜体加粗
```
语法：***加粗斜体***
```
* ***加粗斜体***
```
语法：**_加粗斜体_**
```
* **_加粗斜体_**


* 文字左右分别用三个\*或\_包裹起来。

### 删除线
```
语法：~~删除线~~
```
* ~~删除线~~


* 文字左右分别用两个\~包裹起来。

### 上标
```
语法：x<sup>y</sup>
```
* x<sup>y</sup>
* 文字左右分别用\<sup>标签包裹起来。

### 下标
```
语法：x~y~
```
* x~y~
```
语法：x<sub>y</sub>
```
* x<sub>y</sub>


* 文字左右分别用一个\~或\<sub>标签包裹起来。

### 强调
```
语法：*强调*
```
* *强调*
```
语法：<em>强调</em>
```
* <em>强调</em>
* 文字左右分别用一个\*或\<em>标签包裹起来。

### 键盘文本
```
语法：<kbd>Ctrl</kbd>
```
* <kbd>Ctrl</kbd>


* 文字左右分别用\<kbd>标签包裹起来。

## 引用
```
语法：> 一级引用
```
* > 一级引用
```
语法：> > 二级引用
```
* > > 二级引用
```
语法：> > > 三级引用
```
* > > > 三级引用
```
语法：> > > > 多级引用
```
* > > > > 多级引用
* 文字前加\>即可，引用可以嵌套，加两个\>，三个\>都可以，可以无限嵌套。
```
语法：
> 引用
   引用
   引用
```
> 引用
   引用
   引用
* 多行引用时在第一行加\>即可,结束时在下一行插入空行或下一行以新标记开头。
  *注意：使用时符号和文字中间要用空格隔开。*[^2]

## 图片
### 行内式
```
语法：![图片alt](图片地址 "图片title")
![Hello World](https://raw.githubusercontent.com/GitHub-Zany/markdown/master/images/helloworld.jpg "Hello World")
```
![Hello World](https://raw.githubusercontent.com/GitHub-Zany/markdown/master/images/helloworld.jpg "Hello World")
* 图片alt：图片的描述，图片无法显示时用来描述图片内容。
* 图片title：图片的标题，当鼠标移到图片上时显示，可加可不加。
* 目前为止， Markdown 还没有办法指定图片的宽高，如果需要，可以使用html语言的\<img>标签。
  *注意：图片地址和图片title中间有一个空格。*[^1]
### 参考式
```
![图片alt][图片id]
![Hello World][1]
[1]: https://raw.githubusercontent.com/GitHub-Zany/markdown/master/images/helloworld.jpg "Hello World"
```
![Hello World][1]
[1]: https://raw.githubusercontent.com/GitHub-Zany/markdown/master/images/helloworld.jpg

## 超链接
```
语法：[超链接的文字](超链接地址 "超链接title")
[百度一下](https://www.baidu.com "https://www.baidu.com")
```
[百度一下](https://www.baidu.com "https://www.baidu.com")
```
语法：<a href="超链接地址" title="超链接title" target="_blank">超链接的文字</a>
<a href="https://www.baidu.com" title="https://www.baidu.com" target="_blank">百度一下</a>
```
<a href="https://www.baidu.com" title="https://www.baidu.com" target="_blank">百度一下</a>
* 超链接title：超链接的标题，当鼠标移到超链接上时显示，可加可不加。
* 第一种超链接可能不是在新页面打开，可以用第二种html语言的a标签代替。
 *注意：第一种超链接的地址和超链接title中间有一个空格。*[^1]

## 换行
* [boostnote](https://boostnote.io/ "https://boostnote.io/")，[stackedit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")回车即可换行。[github](https://github.com/ "https://github.com/")在需要换行的文字后面加两个空格键。
  
## 无序列表
```
语法：
* 列表
* 列表
```
* 列表
* 列表
```
语法：
- 列表
- 列表
```
- 列表
- 列表
```
语法：
+ 列表
+ 列表
```
+ 列表
+ 列表
* 文字前加\-，\+，\*任何一种都行,效果相同。
  *注意：使用时符号和文字中间要用空格隔开。*[^1]

## 有序列表
```
语法：
3. 列表3
2. 列表2
```
* 3. 列表3
  2. 列表2


* 文字前加数字加点，如果数字是乱序，显示时会从第一个数字开始累加，当列表嵌套时[github](https://github.com/ "https://github.com/")会自动转为罗马数字或字母的形式，此时第一个数字必须是1，且将来markdown可能支持设置开始数字，因此建议每次都以数字1开始。
  *注意：使用时符号和文字中间要用空格隔开。*[^1]

## 任务列表
```
语法：- [ ] 未完成
```
* - [ ] 未完成
```
语法：- [x] 已完成
```
* - [x] 已完成


* 空格：表示未完成。
  x：表示已完成，一般小写，[boostnote](https://boostnote.io/ "https://boostnote.io/")，[stackedit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")）支持大写，[github](https://github.com/ "https://github.com/")不支持，推荐小写。
  *注意：\-和\[]之间有一个空格，\[]和文字之间有一个空格，\[]中只能有一个空格或一个x。*[^1]

## 列表嵌套
```
语法：
- 列表
  1. 列表
  2. 列表
- 列表
  1. 列表
  2. 列表
```
* - 列表
    1. 列表
    2. 列表
  - 列表
    1. 列表
    2. 列表


  *注意：嵌套时，上一级和下一级之间缩进两个空格，一般也不能多于五个，否则嵌套无效。*[^1]
```
语法：
- 2018
    - 一月
    - [ ] 未完成1
    - [ ] 未完成2
      - [x] 第一周
        - [ ] 已完成1
        - [x] 已完成2
  - 2019
    - [ ] 一月
      - [ ] 第一周
        - [ ] 未完成1
    - [ ] 二月
```
* - 2018
     - 一月
      - [ ] 未完成1
      - [ ] 未完成2
        - [x] 第一周
          - [ ] 已完成1
          - [x] 已完成2
    - 2019
      - [ ] 一月
        - [ ] 第一周
          - [ ] 未完成1
      - [ ] 二月

## 表格
```
语法：
表头\|表头\|表头
-----|:----:|----:
内容|内容|内容
内容|内容|内容
  
姓名|性别|年龄|爱好
----|----:|:----:|----
张三|男|18|足球
李四|女|18|美食
```
姓名|性别|年龄|爱好
----|----:|:----:|----
张三|男|18|足球
李四|女|18|美食
* 第二行分割表头和内容，\-有一个就行，为了对齐，多加了几个。
  文字默认居左
  \-两边加：表示文字居中
  \-右边加：表示文字居右
  *注意：原生的语法两边都要用 | 包起来。此处省略*[^2]

## 代码域
```
语法：`单行代码域`
```
* `单行代码域`
* 代码之间分别用一个反引号包起来
```
语法：代码之间分别用三个反引号包起来，且两边的反引号单独占一行。
```
```
多行代码域
多行代码域
```
* 根据不同的语言配置不同的代码着色。
```java
  public static void main(String[] args) {
      System.out.println("hello world");
  }
```
```javascript
  var num = 0;
  for (var i = 0; i < 5; i++) {
      num+=i;
  }
  console.log("hello world");
```

## 流程图
```
语法：与代码域语法类似。
```
* \```mermaid
    graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
    \```
* ```mermaid
  graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
  ```
* 语法详情参考[stackedit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")，部分（如：[boostnote](https://boostnote.io/ "https://boostnote.io/")，[stackedit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")）支持这种语法，[github](https://github.com/ "https://github.com/")不支持。

## 锚点
```
语法：[锚点名称\](目标)

[跳转到MarkDown](#MarkDown)
```
* [跳转到MarkDown](#MarkDown)
  *注意：锚点的目标必须是标题的名称，如果存在多个同名标题则跳转第一个标题。*
  语法详情参考[Jump by a header in a note · BoostIO/Boostnote Wiki · GitHub](https://github.com/BoostIO/Boostnote/wiki/Jump-by-a-header-in-a-note "https://github.com/BoostIO/Boostnote/wiki/Jump-by-a-header-in-a-note")

## 脚注
```
文字\[^脚注名称\]
[^脚注名称]: 脚注内容

百度[^1]
[^1]: www.baidu.com
```
* 百度[^3]
[^3]: www.baidu.com  
* 脚注内容推荐写在文档最后，若写在文档中脚注内容结束时需要插入一行空格或下一行以任一文档标识开头与下面内容隔断。
  *注意：脚注名称可写任意字符，特殊字符需要转义。显示时会自动按在文中第一次出现的先后顺序排序，并自动转成数字，从1开始计数，出现在第一位即转为数字1，第二位即转为数字2。即使第一个脚注名称为数字2，依旧会被转为数字1。*[^2]  
  部分支持（如：[boostnote](https://boostnote.io/ "https://boostnote.io/")，[stackedit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")）支持这种语法，[github](https://github.com/ "https://github.com/")不支持。  

> 参考文档  
  [Markdown] <https://www.appinn.com/markdown/index.html>  
  [StackEdit] <https://stackedit.io/app#>  

[^1]: 强制  
[^2]: 非强制  
  





  
