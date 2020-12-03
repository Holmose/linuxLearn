## <font color=gray>1. Linux操作系统简介</font>
Linux系统是基于Unix以网络为核心的设计思想，是一个性能稳定的多用户操作系统，Linux能运行各种工具软件、应用程序及网络协议，它支持安装在32位和64位CPU硬件上。

Linux即Linus's unix，在1991年的10月5日，还在读大学的Linus Torvalds写出了Linux内核。

Linux操作系统应用领域越来越广泛，尤其是近年来Linux在服务器领域飞速的发展，主要得益于Linux操作系统具备的如下优点：
1. 开源、免费
2. 系统迭代更新
3. 系统性能稳定
4. 安全性高
5. 内核小
6. 应用领域广泛
---
## <font color=gray>2. Linux操作系统发行版本</font>
Linux操作系统主流发行版本包括：Red Hat Linux、CentOS、Ubuntu、SUSE Linux、Fedora Linux等，具体发行版本区别如下：

#### <font color=darkgray>2.1.1 Red Hat Linux</font>
Red Hat Linux 1994年创立，是最早的Linux发行版本之一，同时也是最著 名的Linux版本，Red Hat Linux已经创造了自己的品牌，也是读者经常听 到的“红帽操作系统”。

2018年10月份IBM正式宣布以340亿美元收购红帽。

#### <font color=darkgray>2.1.2 CentOS</font>
社区企业版操作系统（Community Enterprise Operating System， CentOS）是Linux发行版之一，它是来自于Red Hat Enterprise Linux依照 开放源代码所编译而成。由于出自同样的源代码，因此有些要求高度稳定 性的服务器以CentOS替代商业版的Red Hat Enterprise Linux使用。

CentOS于Red Hat Linux不同之处在于CentOS并不包含封闭的源代码软 件，可以开源免费使用，得到运维人员、企业、程序员的青睐，CentOS发 行版操作系统是目前企业使用最多的系统之一，

2014年7月7日，正式发布centos 7
2019年9月25号，正式发布了Centos8的新版本。

#### <font color=darkgray>2.1.3 Ubuntu</font>
Ubuntu是一个以桌面应用为主的Linux操作系统，其名称来自非洲南部祖鲁语或豪萨语的“ubuntu”一词（译为吾帮托或乌班图），意思是“人性”、“我的存在是因为大家的存在”，是非洲传统的一种价值观。

Ubuntu基于Debian发行版和GNOME桌面环境，Ubuntu发行版操作系统的目标在于为一般用户提供一个最新的、同时稳定的以开放自由软件构建而成的操作系统，目前Ubuntu具有庞大的社区力量，用户可以方便地从社区获得帮助。

#### <font color=darkgray>2.1.4 SUSE Linux</font>
SUSE(发音 /ˈsuːsə/)，SUSE Linux 出自德国，SuSE Linux AG公司发行维护的Linux发行版，是属于此公司的注册商标2003年11月4日，Novell表示将会对SUSE提出收购。收购的工作于2004年1月完成。

#### <font color=darkgray>2.1.5 Fedora Linux</font>
Fedora是一个知名的Linux发行版，是一款由全球社区爱好者构建的面向日常应用的快速、稳定、强大的操作系统。

它允许任何人自由地使用、修改和重发布，无论现在还是将来。它由一个强大的社群开发，这个社群的成员以自己的不懈努力，提供并维护自由、开放源码的软件和开放的标准。

Fedora 约每六个月会发布新版本，美国当地时间2015年11月3日，北京时间2015年11月4日，Fedora Project 宣布 Fedora 23 正式对外发布，2017年6月发布Fedora 26版本。

### <font color=darkgray>2.2 Linux内核命名规则</font>
Linux内核是Linux操作系统的核心，一个完整的Linux发行版包括进程管理、内存管理、文件系统、系统管理、网络操作等部分。

Linux内核版本命名在不同的时期有其不同的命名规范，其中在2.X版本中，X如果为奇数表示开发版、X如果为偶数表示稳定版，从2.6.X以及3.X，内核版本命名就没有严格的约定规范。

从Linux内核1994年发布1.0发布到目前主流3.X版本，5.X也是稳定版本。

#### <font color=gray>查看Linux操作系统内核</font>
```
uname -a
Linux VM-0-10-centos 3.10.0-1127.19.1.el7.x86_64 #1 SMP Tue Aug 25 17:23:54 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

```
也可以去官网下载内核：www.kernel.org：

其中Mainline表示主线开发版本，Stable表示稳定版本，稳定版本主要由mainline测试通过而发布。

Longterm表示长期支持版，会持续更新及Bug修复，如果长期版本被标记为EOL（End of Life），则表示不再提供更新。

## <font color=gray>3. Linux系统安装</font>
**在安装CentOS操作系统时，如果没有多余的计算机裸机设备**，可以基于Windows主机上安装Vmwareworkstation工具，该工具的用途可以在真实机上模拟一个新的计算机完整的资源设备，包括：CPU、内存、硬盘、网卡、DVD光驱、USB接口、声卡，进而可以安装CentOS7.4系统

**如果有多余的计算机裸机设备或者企业服务器**，可以将CentOS系统直接安装在多余的设备上，安装之前需要下载CentOS7.x操作系统镜像文件(International Organization for Standardization,ISO 9660标准)，通过刻录工具，将ISO镜像文件刻录至DVD光盘或者U盘里，通过DVD或者U盘启动然后安装系统。

### <font color=gray>3.1 安装环境准备</font>
```
VMware workstation 14.0

CentOS 7.x x86_64
```
### <font color=gray>3.2 Vmware 14.0下载</font>
```
链接：https://pan.baidu.com/s/1sei8jlgRtVnLvP2whupIVQ

提取码：flqn
```
### <font color=gray>3.3 CentOS 7.4镜像下载</font>
在各大镜像站下载：
```
http://mirrors.163.com

https://opsx.alibaba.com

#直接选择centos/7/isos/x86_64/,会指向最新的版本，如果要想下载以前的版本，可以到其他目录下下载readme，根据其中的地址，进行下载。
```
其他发行版，可以在这里选择：
```
http://vault.centos.org/
```
* Vmware安装好后，执行运行，单击“创建新的虚拟机” 

  ![1](..\images\day1\1.png)

* 新建虚拟机向导，选择自定义（高级）（C）选项

  ![2](..\images\day1\2.png)

* 直接下一步

  ![3](..\images\day1\3.png)

* 安装客户机操作系统，选择“稍后安装操作系统（S） 

  ![4](..\images\day1\4.png)

* 选择客户机操作系统

  由于我们即将安装CentOS7.4操作系统，所以需要勾选“Linux（L）”， 

  同时版本（V）选择“CentOS 7 64位” 

  ![5](..\images\day1\5.png)

* 自定义虚拟机名字，以及选择虚拟机存放位置

  ![6](..\images\day1\6.png)

* 选择给虚拟机分配几个cpu，这个要根据物理机的cpu设备情况来分 配，选择默认就可以了

  ![7](..\images\day1\7.png)

* 虚拟机内存设置，默认为1024MB ，如果物理机内存不够，则可以设置 为512M

  ![8](..\images\day1\8.png)

* 网络选择桥接模式

  ![9](..\images\day1\9.png)

* I/O控制器选择默认

  ![10](..\images\day1\10.png)

* 磁盘类型选择默认

  ![11](..\images\day1\11.png)

* 创建新的虚拟机，所以选择创建新的磁盘

  ![12](..\images\day1\12.png)

* 磁盘大小分配20G，选择将虚拟磁盘划分为多个文件，便于拷贝，迁移

  ![13](..\images\day1\13.png)

  ps:如果硬盘容量小于2TB，系统默认会使用MBR模式来安装，若需强制使用GPT分区，可以在安装时，先选择install centos 7 ，然后按tab 键，在quiet后面空格输入：inst.gpt

* 直接下一步

  ![14](..\images\day1\14.png)

* 点击完成

  ![15](..\images\day1\15.png)

* 点击CD/DVD，选择使用ISO镜像文件

  ![16](..\images\day1\16.png)

  ![17](..\images\day1\17.png)

  

* 然后点击启动此虚拟机，即可开始安装

  ![18](..\images\day1\18.png)

* 用上下键选择第一个，直接回车，开始安装

  ![19](..\images\day1\19.png)

  ![20](..\images\day1\20.png)

  ![21](..\images\day1\21.png)

  ![22](..\images\day1\22.png)

  ![23](..\images\day1\23.png)

  ![24](..\images\day1\24.png)

  ![25](..\images\day1\25.png)
  
  ![26](..\images\day1\26.png)
  
  ![27](..\images\day1\27.png)
  
  ![28](..\images\day1\28.png)
  
  ![29](..\images\day1\29.png)
  
  ![30](..\images\day1\30.png)
  
  ![31](..\images\day1\31.png)
  
  ![32](..\images\day1\32.png)
  
  ![33](..\images\day1\33.png)
  
  ![34](..\images\day1\34.png)
  
  ![35](..\images\day1\35.png)
  
  ![36](..\images\day1\36.png)
  
  ![37](..\images\day1\37.png)
  
  ![38](..\images\day1\38.png)


* 安装完成，重启服务器之后，现在可以通过远程工具连接。



## <font color=gray>4. xshell连接及配置</font>

#### <font color=darkgray>4.1 三种连接xhsell的方式</font>

1. 第一种：终端直接使用ssh命令连接

   ```bash
   [c:\~]$ ssh 192.168.75.133
   #回车之后，输入用户名和密码
   ```

2. 第二种：在标签上方直接输入用户及主机IP连接

3. 第三种：写入常用列表（推荐）

   ![43](..\images\day1\43.png)

* 填写名称和ip地址 

   ![44](..\images\day1\44.png)
* 连接
   ![45](..\images\day1\45.png)
   ![46](..\images\day1\46.png)
   ![47](..\images\day1\47.png)
   ![48](..\images\day1\48.png)
   
#### <font color=darkgray>4.2 关闭selinux/firewalld</font>

```bash
# 查看selinux状态
getenforce
# 临时关闭selinux
setenforce 0
# 永久关闭selinux
vi /etc/selinux/config
SELINUX=disabled
# 查看防火墙状态
systemctl status firewalld
# 临时关闭防火墙：
systemctl stop firewalld
# 永久关闭防火墙：
systemctl disable firewalld
```

#### <font color=darkgray>4.3 拓展命令</font>

```bash
# 安装网络工具包
yum install net-tools -y
# 查看IP地址
ip a
# 配置网卡
vim /etc/sysconfig/network-scripts/ifcfg-ens33
# 重启网络服务
systemctl restart network
# 查看系统版本
cat /etc/redhat-release
# 释放内存
echo 1 > /proc/sys/vm/drop_caches
# 查看文件后10行
tail file

```

## <font color=gray>5. 快照</font>

* 配置完成Linux后进行快照

  ![39](..\images\day1\39.png)

* 为快照取一个名称，并输入描述

  ![40](..\images\day1\40.png)

* 进入快照管理器可查看所有快照

![41](..\images\day1\41.png)

![42](..\images\day1\42.png)