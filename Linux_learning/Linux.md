# Linux_LearingNotes

## 命令格式

`commmad [-options] [parameter]`

由命令+可选项+参数构成，参数可以是目标文件或者地址

如：

`ls -l / `

- ls 命令本身

- -l 可选项
- / 参数

表示以竖向排列的形式展示目录/下的内容

## Linux目录结构

区别于windows

Linux只有一个顶级目录，叫根目录,记作 /

Windows有多个顶级目录，就是各个磁盘

 / 出现在开头则表示根目录,出现在后面则表示层级关系

如/user/local，第一个/表示根目录，第二个表示层级关系,表示uesr目录下的文件

## 工作目录

默认HOME目录为工作目录

它的路径是/home/用户名

## ls命令

`ls [-a -l -h] [Linux路径]`

平铺形式展示当前工作目录中的文件

-a 表示全部文件，包含隐藏文件（.开头的文件）

-l 以竖向排列的形式展示内容

-h 以易于阅读的形式列出文件大小与-l一起使用

-alh与-a -h -l 等效

## cd命令



