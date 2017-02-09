# tree
tree是用nodeJS实现的一个shell命令，可以对当前目录下的所有文件以及子文件进行遍历，并且通过文件树的形式展现。

# Install

方法一：

$ git clone 

$ cd 进入tree所在目录

执行下面命令(建立一个软链接,也可以写进Path里)

$ npm link

$ tree

方法二：

$ npm install tree_shell -g

$ tree  

#Usage

$ tree 

类似如下显示

|--dir

|  |--a.txt

|--dir2

|  |--dir3

|  |  |--b.txt


