### Git FQA
1. 由于SSH配置文件的不匹配，导致的Permission denied (publickey)及其解决方法
    [解决方案](https://www.cnblogs.com/lpdi/p/6816380.html)
    > 输入命令：ssh -T git@github.com
    > 正常会打印：
    > "Hi XXX! You've successfully authenticated, but GitHub does notprovide shell access."
    > 没有打印以上信息尝试生成ssh key：ssh-keygen -t rsa -C "XXXXXX@163.com”
    > 生成的key文件默认保存在C盘用户名目录下的.ssh文件中，将id_rsa.pub文件中的内容复制到github上生成新的ssh key。
    > 重试命令：ssh -T git@github.com

2. Warning: Permanently added the RSA host key for IP address '13.250.177.223' to the list of known hosts.
    > 警告的意思是需要在hosts配置文件中添加 *13.250.177.223 github.com*

3. git push remote: Invalid username or password. fatal: Authentication failed for 
    [解决方案](https://stackoverflow.com/questions/32669323/remote-invalid-username-or-password-fatal-authentication-failed-for)

4. 出现Everything up-to-date
    > 原因：
    > 1）没有git add .
    > 2）没有git commit -m "提交信息"
    > 如果上面两个步骤都成功执行，还出现这个错误是因为创建的目录下是空的，目录下必须有文件才能git push上传成功。
    > 在github上创建文件的时候，在新文件名后加/符号就是文件夹，但是这种方式只支持英文名目录，中文名目录不支持。
    > 要是想创建中文名文件夹，就通过客户端工具或终端命令行实现。
    > 如果在github一个文件夹下只有一个文件，那么删除这个文件的同时，它所在的文件夹也一同删除了。