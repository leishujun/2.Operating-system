# Operating-system
# __操作系统__  
通用目的的软件程序  
硬件驱动  
进程管理  
网络管理  
内存管理  
安全管理  
文件管理  

## 分类  
服务器OS：RHEL, CentOS,Windows Server,AIX  

桌面OS：Windows 10,Windows 7,Mac OS，Fedora 

移动设备OS：Andriod,IOS,YunOS


# __开发接口标准__

### __ABI__  
&ensp;&ensp;&ensp;&ensp;Application  binary  interface，应用程序核和操作系统之间的底层接口，涉及到 strace这个命令，系统调用

### __API__   
&ensp;&ensp;&ensp;&ensp;Application programming interface，源代码和库之间的接口。开发关心这个多些，运维遇到想甩锅给你的开发学学还是有必要。涉及到的命令是 ltrace，库调用

### __POSIX__  
&ensp;&ensp;&ensp;&ensp;Portable Operating System Interface X 是凑数的

&ensp;&ensp;&ensp;&ensp;IEEE在操作系统上一系列API标准

### __运行程序格式__  

&ensp;&ensp;&ensp;&ensp;Windows：.exe,dll（dynamic link library）,lib

&ensp;&ensp;&ensp;&ensp;Linux：ELF,so（share object），a  


# __Linux内核__  
涉及命令  
uname -r   
lsb_release(6版本)  


## __3.10.0-693.el7__  
3是指主版本号,系统变动大才会修改这个  
10是指次版本号,一般有新功能这个才会变  
0是指出现一些bug,纠正后这个就会变  
693是指打包修订次数  
el7这个是红帽厂商写的些东西,不清楚什么用途

# __开源协议__  

## GPL最严格,MIT最宽松  
