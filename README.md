# ATM-GUI-Socket-Mysql
ATM机项目 技术栈包括GUI Socket Mysql
# 1.数据库配置

首先在本地创建一个atm数据库，然后用navicat等数据库可视化软件在atm数据库中运行提供的atm.sql文件，得到数据库表。

# 2.配置文件

config文件夹中的mysql.properties文件中有数据库相关配置

使用者需要确保数据库名为atm，然后输入自己数据库的user，password，根据不同的mysql版本，driver驱动使用com.mysql.jdbc.Driver  或者com.mysql.cj.jdbc.Driver

在源程序src文件夹中，需要配置util工具包下的Config类，把配置路径改成你的绝对路径（不用相对路径的原因是有时会报错）

另外ui包中的MainFrame类61行需要配置你的logo绝对路径，即logo文件夹中的logo路径

# 3.项目环境

我用的是jdk8，需要把libs文件夹加载为库，然后运行

如果有数据库相关报错，可以根据你mysql数据库版本更换libs中的驱动，我这边提供的只有5和8的。

# 5.文档ppt

如果有需要，可以联系邮箱23200107116@post.usts.edu.cn,获取ppt和项目文档
