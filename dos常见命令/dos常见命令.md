# dos 常见命令

* A:d: 回车	盘符切换
* B:dir(directory):列出当前目录下的文件以及文件夹
* C:cd (change directory)改变指定目录(进入指定目录)
* D:cd.. : 退回到上一级目录
* E:cd\: 退回到根目录
* F:cls : (clear screen)清屏
* G:exit : 退出dos命令行(分割线上的需要掌握,下的了解)

# 创建文件

 cd>a.txt，type nul>a.txt，copy nul>a.txt 三种方式创建空文件；

 echo [file content]>a.txt 创建非空文件

### 删除文件夹

我们可以使用 rd folderName或rmdir folderName命令来删除空文件夹(rd:remove directory)；

使用命令 rd/s  folderName或rmdir/s  folderName命令删除文件夹(不管是否为空)，会提示是否删除，输入y才能删除；

使用命令 rd/s/q folderName或rmdir/s/q folderName 命令删除文件夹(不管是否为空)，可以直接删除(/q，即quiet，安静模式;/s:subdirectory,子目录)；