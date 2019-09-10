# Linux_command_lines

<p align="center">
    <a href="https://github.com/elegantcoin/Linux_command_lines"><img src="https://img.shields.io/badge/status-updating-brightgreen.svg"></a>
    <a href="https://github.com/python/cpython"><img src="https://img.shields.io/badge/Python-3.7-FF1493.svg"></a>
    <a href="https://github.com/elegantcoin/Linux_command_lines"><img src="https://img.shields.io/badge/platform-Windows%7CLinux%7CmacOS-660066.svg"></a>
    <a href="https://opensource.org/licenses/mit-license.php"><img src="https://badges.frapsoft.com/os/mit/mit.svg"></a>
    <a href="https://github.com/elegantcoin/Linux_command_lines/stargazers"><img src="https://img.shields.io/github/stars/elegantcoin/Linux_command_lines.svg?logo=github"></a>
    <a href="https://github.com/elegantcoin/Linux_command_lines/network/members"><img src="https://img.shields.io/github/forks/elegantcoin/Linux_command_lines.svg?color=blue&logo=github"></a>
    <a href="https://www.python.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" align="right" height="48" width="48" ></a>
</p>
<br />

## :fire:Terminal终端:
-   `Ctrl + Alt + T` 打开终端。
-   `Ctrl + L` 清除屏幕(与clear稍微不同)。
-   `Ctrl + S` 停止输出到屏幕。
-   `Ctrl + Q` 在`Ctrl + S`停止输出后，恢复输出。
-   `Ctrl + C` 结束运行的进程并返回提示。
-   `Ctrl + D` 退出当前的shell会话。
-   `Ctrl + Z` 暂停正在运行的进程，返回shell提示符。
-   `Tab` 智能补充文件目录名。
-   `Tab Tab` 显示所有自动补充匹配项。
-   `Ctrl + Shift + W` 关闭terminal终端。
-   `Ctrl + Shift + Q` 多个终端的关闭。
  
## :fire:光标
-   `Ctrl + A` 当前活动行开头。
-   `Ctrl + E` 当前活动行末尾。
-   `Ctrl + XX` 当前活动行末尾和开头之前切换。
-   `Alt + F` 一次前跳一个单词
-   `Alt + B` 一次回跳一个单词
-   `Ctrl + F` 一次前跳一个字符串
-   `Ctrl + B` 一次回跳一个字符串

## :fire:文本操作
-   `Ctrl + U` 剪切当前位置到行首，添到剪贴板。
-   `Ctrl + K` 剪切当前位置到行尾，添到剪贴板。
-   `Ctrl + W` 删除光标前的单词，添到剪贴板。
-   `Ctrl + Y` 粘贴最近剪切内容。
-   `Alt + T` 交换光标前的两个词。
-   `Alt + L` 小写光标处到单词尾的字符。
-   `Alt + U` 大写光标处到单词尾的字符。
-   `Alt + C` 光标处到单词尾的字符首字母大写。
-   `Alt + D` 删除光标处到单词尾的字符。
-   `Alt + .` 打印最近一个命令。
-   `Ctrl + T` 交换光标前的两个字符串
 
## :fire:历史命令行
-   `Ctrl + R` 搜索之前使用过的命令。
-   `Ctrl + G` 退出`Ctrl + R`。
-   `Ctrl + J` 将当前匹配的命令复制到命令行，不运行命令。
-   `Alt + R` 撤销上条历史记录的命令。
-   `Ctrl + P` 显示上条执行的命令。
-   `Ctrl + N` 显示下一条执行的命令。

## :fire:特殊操作
-   `Ctrl + H` 相当于删除键。
-   `Ctrl + J` 相当于换行符。
-   `Ctrl + M` 相当于回车键。
-   `Ctrl + I` 相当于`Tab`键。
-   `Ctrl + G` Bell 字符。
-   `Ctrl + @` Null 字符。
-   `Esc` Deadkey，相当于`Alt`。

## :fire:文件目录
-   `pwd` 当前目录。
-   `cd -` 上个工作目录。
-   `cd ~`或者`cd` Home主目录。
-   `cd ..` 上级目录。
-   `ls -l` 目录list信息。
-   `ls -a` 目录list信息（包含隐藏文件）。
-   `ls -lh` 目录list信息（文件大小以K，Mb显示）。
-   `ls -lR` 目录list信息（包含次级目录）。
-   `tree` 目录树结构。
-   `du -sh .[!.]*` 目录下文件信息。

## :fire:文件/夹操作
-   `cp -p source destination` 复制文件。
-   `cp -R source_Dir destination_Dir` 复制文件夹。
-   `mv file1 file2` 移动文件。
-   `rm -i filename` 删除文件（加删除确认）。
-   `rm -R Dirname` 删除文件夹（加删除确认）。
-   `mkdir dir-name` 新建文件夹。
-   `touch filename` 新建文件。
-   `chmod go=+r myfile` owner和group组增加读取权限。
-   `chmod a +rwx myfile` 所有用户组添加读写执行权限。

``` shell
sudo -i
rm -rv /home/<your_username>/.local/*
exit
``` 
删除.local下的文件夹。



## :fire:帮助信息
-   `echo "hhhh"` 打印输出。
-   `man <name>` <name> 的手册页。
-   `man -k <keyword>` 所有包含<keyword> 的手册页。
-   `help <name>` <name>的帮助信息。
-   `info <name>` <name>的所有信息。
-   `dpkg -l` 系统的所有安装包。
-   `less /var/lib/dpkg/available` 系统的所有安装包简介。
-   `whatis vim` 安装包的一行简介。    

## :fire:用户信息
-   `hostname` 显示主机名。
-   `whoami` 终端登录用户的用户名。
-   `who` 显示登录的所有用户。 
-   `w` 显示当前系统状态，时间，持续时间，当前登录系统的用户列表等用户信息。 
-   `last` 最近使用过系统的用户。 
-   `last root` 上次root用户登录时间。 
-   `chmod` 更改权限。 

## :fire:进/线程信息
-   `top` 设备资源占用情况。 
-   `ps` 列出当前shell会话的进程。 
-   `ps -u root` 所有root正在运行的进程和命令。
-   `ps aux` 当前系统上所有用户的进程。



。。。。。。（待续）

  
  
  
  - 另外参见[命令行的艺术]https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md
