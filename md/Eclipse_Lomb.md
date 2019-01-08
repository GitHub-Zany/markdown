## Eclipse lombok插件安装步骤
1. 下载[Lombok](https://www.projectlombok.org/)。
2. 把jar包放入eclipse安装目录的dropins下。
3. 在eclipse.ini文件中添加以下配置：
    > -Xbootclasspath/a:lombok.jar
    > -javaagent:___Eclipse根目录\[如：D:\admin\eclipse-oxygen\]___\dropins\lombok.jar
4. 重启eclipse，查看Help --> About Eclipse，如下图即安装完成。
5. ![About Eclipse](https://github.com/GitHub-Zany/markdown/blob/master/images/abouteclipse.jpg)
