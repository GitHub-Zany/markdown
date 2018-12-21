# MarkDown
###### （纯文本格式的标记语言）
---
## 标题
* \# 标题
  # 一级标题
  ## 二级标题
  ### 三级标题
  #### 四级标题
  ##### 五级标题
  ###### 六级标题
* 文字前加\#即可，一个\#表示一级标题，二个\#表示二级标题，依次类推，一共有六级。  
  *注意：使用时符号和文字中间要用空格隔开。*[^1]
  
## 分割线
* \---
* \***
---
----
*****
******
* 三个或者三个以上的\-或者\*单独一行，两者效果一样。

## 字体
* #### 加粗
  \*\*加粗\*\* --> **加粗** 或 <b>加粗</b>  
  文字左右分别用两个\*包裹起来。  
  
* #### 斜体
  \*斜体\* --> *斜体*  或 \_斜体\_ --> _斜体_  或 <i>斜体</i>  
  文字左右分别用一个\*号包裹起来。  
  
* #### 斜体加粗
  \*\*\*斜体加粗\*\*\* --> ***加粗斜体*** 或  \*\*\_斜体加粗\*\*\_ --> **_加粗斜体_**  
  文字左右分别用三个\*或\_号包裹起来。  
  
* #### 删除线
  \~\~删除线\~\~ --> ~~删除线~~  
  文字左右分别用两个\~号包裹起来。  

* #### 上标 
  文字\<sup>上标\</sup> --> 文字<sup>上标</sup>  

* #### 下标
  文字\~下标\~ --> 文字~下标~ 或 文字\<sub>下标\</sub> --> 文字<sub>下标</sub>  
  文字左右分别用一个\~号包裹起来。  
  
* #### 强调
  \*强调\* --> *强调* 或 \<em>强调\</em> --> <em>强调</em>  
  
* #### 键盘文本
  \<kbd>Ctrl\</kbd> --> <kbd>Ctrl</kbd>  
  
## 引用
* \> 引用 
  > 一级引用
  > > 二级引用
  > > > 三级引用
  > > > > ……
* 文字前加\>即可，引用可以嵌套，如加两个\>，三个\>都可以，可以无限嵌套。  
  *注意：使用时符号和文字中间要用空格隔开。*[^2]
  
## 图片
* !\[图片alt\](图片地址 ''图片title'')  
  ![Hello World](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1545368508152&di=90478925c69952c4008db81378d7988e&imgtype=0&src=http%3A%2F%2Fp.cdn.sohu.com%2F49dc1158%2Fc7375836d22fb7c42d357cf754d78835.jpeg "Hello World")  
  图片alt就是显示在图片下面的文字，相当于对图片内容的解释。  
  图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加。  
  *注意：图片地址和图片title中间有一个空格。*[^1]  
  
## 超链接
* \[超链接名\](超链接地址 "超链接title")  
  [百度一下](https://www.baidu.com "https://www.baidu.com")  
  \<a href="https://www.baidu.com" title="https://www.baidu.com" target="_blank">百度一下</a>  
  <a href="https://www.baidu.com" title="https://www.baidu.com" target="_blank">百度一下</a>  
  title可加可不加。  
  Markdown本身语法不支持链接在新页面中打开，有的平台做了处理可以在新页面中打开。  
  如果想要在新页面中打开的话可以用html语言的a标签代替。  
  *注意：超链接地址和超链接title中间有一个空格。*[^1]  
  
## 换行
* boostnote回车即可换行。  
  github 在需要换行的文字后面加两个空格键。  
  
## 无序列表
* \* 列表
* \- 列表
* \+ 列表
  * 列表
  - 列表
  + 列表
* 文字前加\-，\+，\*任何一种都行。  
  *注意：使用时符号和文字中间要用空格隔开。*[^1]
    
## 有序列表
* 1\. 列表A
* 2\. 列表B 
* 1. 列表A
  2. 列表B
* 文字前加数字加点。  
  *注意：使用时符号和文字中间要用空格隔开。*[^1]

## 任务列表
* \- [空格或x] 
  - [ ] 未完成A
  - [ ] 未完成C
  - [x] 已完成B
  
  *注意：\-和\[]之间有一个空格，\[]和文字之间有一个空格，\[]中只能有一个空格或一个x。*[^1]  
  
## 列表嵌套
* 列表
  - 列表
      1. 列表A
      2. 列表B
  - 列表
      1. 列表A
      2. 列表B
  *注意上一级和下一级之间敲两到五个空格即可，少于两个或多于五个空格无效。*[^1]

* TODO 列表也能嵌套
  - 2018
  - [ ] 未完成A
  - [ ] 未完成C
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
* > 表头\|表头\|表头  
  > -----|:----:|----:  
  > 内容|内容|内容  
  > 内容|内容|内容  
* 第二行分割表头和内容，\-有一个就行，为了对齐，多加了几个。  
  文字默认居左  
  \-两边加：表示文字居中  
  \-右边加：表示文字居右  
  *注意：原生的语法两边都要用 | 包起来。此处省略*[^2]  
  
  姓名|性别|年龄|爱好  
  ----|----:|:----:|----  
  张三|男|18|足球  
  李四|女|18|美食  
  
## 代码
* \`单行代码\` --> `单行代码`  
  单行代码：代码之间分别用一个反引号包起来  
  \```  
  多行代码  
  多行代码  
  \```  
  ```
  多行代码
  多行代码
  ```
  \```java  
    public static void main(String[] args) {  
        System.out.println("hello world");  
    }  
  \```  
  ```java
    public static void main(String[] args) {
        System.out.println("hello world");
    }
  ```
  \```javascript  
    var num = 0;  
    for (var i = 0; i < 5; i++) {  
        num+=i;  
    }  
    console.log("hello world");  
  \```  
  ```javascript
    var num = 0;
    for (var i = 0; i < 5; i++) {
        num+=i;
    }
    console.log("hello world");
  ```
  根据不同的语言配置不同的代码着色，部分支持（如：[boostnote](https://boostnote.io/ "https://boostnote.io/")，[StackEdit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")）支持这种语法，github不支持  
  *注意：代码之间分别用三个反引号包起来，且两边的反引号单独占一行*[^1]  
  
##  流程图
```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```
部分支持（如：[boostnote](https://boostnote.io/ "https://boostnote.io/")，[StackEdit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")）支持这种语法，github不支持  

## [锚点](#标题)  
[Jump by a header in a note · BoostIO/Boostnote Wiki · GitHub](https://github.com/BoostIO/Boostnote/wiki/Jump-by-a-header-in-a-note "https://github.com/BoostIO/Boostnote/wiki/Jump-by-a-header-in-a-note")  

## 脚注
* 注意\[^2\]
  \[^2\]: 脚注  
  注意[^2]  
  [^2]: 脚注  
  部分支持（如：[boostnote](https://boostnote.io/ "https://boostnote.io/")，[StackEdit](https://stackedit.io/app&#35; "https://stackedit.io/app&#35;")）支持这种语法，github不支持  

> 参考文档  
> [Markdown] <https://www.appinn.com/markdown/index.html>  
> [StackEdit] <https://stackedit.io/app#>  

[^1]: 强制  
[^2]: 非强制  
  





  
