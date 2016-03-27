问题
==============
windows下安装rsync时候
运行rsync命令后，在command line下提示：
Could not create directory '/home/Paul/.ssh'.

而我的.ssh文件夹是在

C:\Users\Paul\.ssh


解决
--------

增加环境变量：
```
HOME: C:\Users\Paul
```
搞定了