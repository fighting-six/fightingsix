<font face="黑体" color=gray size=72><P ALIGN="CENTER">第零章 小组介绍</P></font>

# 0.1 小组名称

&#160; &#160; &#160; &#160;fighting six

# 0.2 小组成员

组长：

&#160; &#160; &#160; &#160;程超楠

组员：

&#160; &#160; &#160; &#160;李林潇 吴丹丹 韩伟 陈亚昊 许运丰

# 0.3 项目名称

&#160; &#160; &#160; &#160;Magic Mirror(魔镜)

<font face="黑体" color=gray size=72><P ALIGN="CENTER">第一章 开发环境</P></font>
&#160; &#160; &#160; &#160;基于树莓派和主机系统，介绍其执行环境（硬件环境）、运行环境（软件环境）和编程环境。
# 1.1 树莓派
## 1.1.1 硬件环境 

选用型号：Raspberry 3B+

|硬件名称| 型号或数量  |
| :------------: | :------------: |
| 处理器  | 博通BCM2837B0 SOC，集成四核ARM cortex-A53 64位@1.4GHZ cpu  |
| 内存  |   1 GB LPDDR2 SDRAM |
| 无线网络  | 802.11.b/g/n wireless LAN  |
| 以太网网口  |千兆以太网（通过USB 2.0通道，最大吞吐量300Mbps）   |
|  蓝牙 |  蓝牙 4.2 &低功耗蓝牙 |
|  视频接口 | 支持PAL和NTSC制式，支持HDMI（1.3和1.4），分辨率640×350至1920×1200  |
|  音频接口 | 3.5mm插口，HDMI（高清晰度多音频/视频接口）  |
|  USB接口 |  4 ×USB ports |
| GPIO接口  |  40 pin |
|  Micro SD卡 | 16 GB  |
| 供电接口/要求  | Micro USB(5v/2.5A标准)  |
| 工作环境温度  | 0-50℃  |
## 1.1.2 Startup code
&#160; &#160; &#160; &#160;Startup code：启动代码,是连接硬件启动阶段和程序main（）之间连接的软件。
## 1.1.3  操作系统：Raspbian
&#160; &#160; &#160; &#160;Raspbian是一个基于 Debian 的 Linux 发行版，专门用于 Raspberry Pi，它是Raspberry 用户的完美通用操作系统。Raspbian 采用Open box堆叠窗口管理器和 Pi 改进的 X windows 环境轻量级，并配有许多预装软件，包括 Minecraft Pi，Java，Mathematica 和 Chromium。
## 1.1.4  Middleware（中间件）
&#160; &#160; &#160; &#160;中间件是一种独立的系统软件或服务程序，分布式应用软件借助这种软件在不同的技术之间共享资源，中间件位于客户机/服务器的操作系统之上，管理计算机资源和网络通讯。
## 1.1.5 The run-time libraries(运行库)：glibc
## 1.1.6 编程环境
### c语言
&#160; &#160; &#160; &#160;Editor（编辑器）：vim

&#160; &#160; &#160; &#160;Compiler(编译器): gcc

&#160; &#160; &#160; &#160;Debugger(调试器): gdb

&#160; &#160; &#160; &#160;代码管理器：make

### python
&#160; &#160; &#160; &#160;树莓派系统自带2.7版本的 python 运行环境

# 1.2  主机（个人计算机）
## 1.2.1 硬件环境
| 硬件名称  |  型号或数量 |
| :------------: | :------------: |
| 处理器  | Intel i7-4710MQ CPU @2.5GHZ ×8  |
| 内存  | 7.7 GiB  |
|   磁盘|  63.3 GB |
|  图形处理器 | Intel Haswell Mobile /NV118  |
## 1.2.2 操作系统 Ubuntu 18.10
&#160; &#160; &#160; &#160;Ubuntu（友帮拓、优般图、乌班图）是一个以桌面应用为主的开源GNU/Linux操作系统，Ubuntu 是基于Debian GNU/Linux，支持x86、amd64（即x64）和ppc架构，由全球化的专业开发团队（Canonical Ltd）打造的。
## 1.2.3 Middleware（中间件）
&#160; &#160; &#160; &#160;中间件是一种独立的系统软件或服务程序，分布式应用软件借助这种软件在不同的技术之间共享资源，中间件位于客户机/服务器的操作系统之上，管理计算机资源和网络通讯.
## 1.2.4 The run-time libraries(运行库)：glibc
## 1.2.5 编程环境
### c语言
&#160; &#160; &#160; &#160;Editor（编辑器）：vim

&#160; &#160; &#160; &#160;Compiler(编译器): gcc

&#160; &#160; &#160; &#160;Debugger(调试器): gdb

&#160; &#160; &#160; &#160;代码管理器：make

&#160; &#160; &#160; &#160;IDE：codeblocks

### python
&#160; &#160; &#160; &#160;系统自带python3.5

&#160; &#160; &#160; &#160;IDE: pycharm


[========]
<font face="黑体" color=gray size=72><P ALIGN="CENTER">第二章 需求分析</P></font>

# 2.1 项目名称：魔镜
# 2.2 项目内容
&#160; &#160; &#160; &#160;利用树莓派和原子镜，完成显示屏一边和镜子一样反射光线显示镜像，一边与树莓派相连，动态显示天气、温湿度信息等任务。借助语音识别sdk,完成人机交互。
# 2.3 项目架构 
## 2.3.1 项目关联图
![项目关联图](https://github.com/fighting-six/fightingsix/blob/master/picture/pic1.jpg "项目关联图")
## 2.3.2 项目架构图
![项目架构图](https://github.com/fighting-six/fightingsix/blob/master/picture/pic2.jpg "项目架构图")
# 2.4 功能需求分析

&#160; &#160; &#160; &#160;1.  需要显示出当前的镜像

&#160; &#160; &#160; &#160;2.  系统正常运行时，需要获取实时的天气信息，并显示在镜面上

&#160; &#160; &#160; &#160;3.  系统正常运行时，需要获取当前的时钟，日历信息，并显示在镜面上

&#160; &#160; &#160; &#160;4. 系统正常运行时，需要获取当前室内的温湿度信息，并显示在镜面上

&#160; &#160; &#160; &#160;5.  用户提供语音输入时，系统需要与用户进行语音交互

# 2.5 非功能需求分析
&#160; &#160; &#160; &#160;1. 响应时间：网络通畅的情况下，语音对话响应时间不超过2s

&#160; &#160; &#160; &#160;2. 精度：不详

 &#160; &#160; &#160; &#160;3. 兼容性：系统只支持linux系统
 
&#160; &#160; &#160; &#160;4. 易用性：数据信息联网即自动更新，语音对话开启方式简单。

&#160; &#160; &#160; &#160;5. 可靠性：平均无故障工作时间应>半年

# 2.6 硬件条件

&#160; &#160; &#160; &#160;1.   树莓派 

&#160; &#160; &#160; &#160;2. 8G及以上容量内存卡

&#160; &#160; &#160; &#160;3.  原子镜

&#160; &#160; &#160; &#160;4.   显示器

&#160; &#160; &#160; &#160;5.   HDMI线

&#160; &#160; &#160; &#160;6.   体感摄像头

&#160; &#160; &#160; &#160;7.   DHT11温湿度传感器


# 2.7 软件条件

&#160; &#160; &#160; &#160;2. 百度Dueros开放平台

&#160; &#160; &#160; &#160;3.   MagicMirror

<font face="黑体" color=gray size=72><P ALIGN="CENTER">第三章 构建目标系统</P></font>



# 3.1 开发环境、源码以及编译工具


## 3.1.1 在用户目录下创建Rpi目录来存放内核源码以及编译工具
- mkdir Rpi
- cd Rpi

## 3.1.2 获取树莓派内核源码
- 从GitHub上获取树莓派的内核源码，
- git clone --depth=1 -b rpi-4.14.y https://github.com/raspberrypi/linux.git

## 3.1.3获取交叉编译工具链
- 从GitHub获取树莓派的交叉编译工具：
- git clone https://github.com/raspberrypi/tools
- 目前，在 ~/Rpi 目录下已经有了 linux.tar.bz2 以及 tools.tar.bz2 两个压缩包，解压出来即可。最终内核源码以及编译工具的目录分别为：
- ~/Rpi/linux
- ~/Rpi/tools

## 3.1.4  修改环境变量，以方便使用编译工具
- sudo vi ~/.bashrc
- 编辑用户目录下的 .bashrc，把编译工具的执行路径加入到 PATH变量中，即在文件末尾加入以下两行：
- export PATH=$PATH:$HOME/Rpi/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian-x64/bin
- export PATH=$PATH:$HOME/Rpi/tools/arm-bcm2708/arm-bcm2708-linux-gnueabi/bin
- 为使环境变量即时生效，可执行：
- source .bashrc


# 3.2 内核的修改和配置、编译

## 3.2.1  树莓派3b+的设备树文件
- 树莓派3b+的设备树文件为：
- arch/arm/boot/dts/bcm2710-rpi-3-b-plus.dts

## 3.2.2 内核的配置
- 内核进行默认的配置
- make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- bcm2709_defconfig

## 3.2.3 编译内核镜像、内核模块以及设备树
- 编译内核镜像、内核模块和设备树：
- make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- zImage modules dtbs -j8


# 3.3 替换树莓派系统的内核镜像、设备树，以及内核模块的安装

## 3.3.1 替换掉树莓派的内核镜像
- sudo scripts/mkknlimg arch/arm/boot/zImage /mnt/fat32/kernel7.img

## 3.3.2 设备树相关文件的替换
- sudo cp arch/arm/boot/dts/*.dtb /mnt/fat32/
- sudo cp arch/arm/boot/dts/overlays/*.dtb* /mnt/fat32/overlays/
- sudo cp arch/arm/boot/dts/overlays/README /mnt/fat32/overlays/

## 3.3.3 内核模块的安装
- sudo make ARCH=arm INSTALL_MOD_PATH=/mnt/ext4 modules_install


# 3.4 加载和卸载模块程序

- linux提供了module机制，能够动态的加载内核模块

## 3.4.1 hello kernel代码
- hello.c
![pic3](https://github.com/fighting-six/fightingsix/blob/master/picture/pic3.jpg)

## 3.4.2 Makefile
![pic4](https://github.com/fighting-six/fightingsix/blob/master/picture/pic4.jpg)

## 3.4.3 执行make
![pic5](https://github.com/fighting-six/fightingsix/blob/master/picture/pic5.jpg)

## 3.4.4 执行insmod加载内核模块
![pic6](https://github.com/fighting-six/fightingsix/blob/master/picture/pic6.jpg)

## 3.4.5 lsmod 可以查看到自己的模块
![pic7](https://github.com/fighting-six/fightingsix/blob/master/picture/pic7.jpg)

## 3.4.6 dmesg可以看到打印的log
![pic8](https://github.com/fighting-six/fightingsix/blob/master/picture/pic8.jpg)

## 3.4.7 执行rmmod卸载内核模块
![pic9](https://github.com/fighting-six/fightingsix/blob/master/picture/pic9.jpg)

## 3.4.8 dmesg可以看到打印的log
![pic10](https://github.com/fighting-six/fightingsix/blob/master/picture/pic10.jpg)


# 3.5 创建文件系统

## 3.5.1 Linux文件系统分类
- 日志文件系统

- 指在文件系统发生变化时，先把相关的信息写入一个被称为日志的区域，然后再把变化写入主文件系统的文件系统。在文件系统发生故障（如内核崩溃或突然停电）时，日志文件系统更容易保持一致性，并且可以较快恢复。
![11](https://github.com/fighting-six/fightingsix/blob/master/picture/11.jpg)

- 日志型文件系统有: ext3, ext4, xfs, ...


- 非日志文件系统
- 与日志文件系统相反
![12](https://github.com/fighting-six/fightingsix/blob/master/picture/12.jpg)

- 非日志型文件系统有: ext2, vfat，...




## 3.5.2 硬盘分区

- 主分区和扩展分区最多可以有四个(硬盘限制)
- 扩展分区最多只能有一个(操作系统的限制)
- 逻辑分区是由扩展分区下分隔出来的
- 作为数据存储的分区为主分区和逻辑分区能够被格式化，扩展分区无法格式化
- 对于一块硬盘来讲，在Linux系统中IDE硬盘最多有63个分区，SATA硬盘则有15个分区

- 命令名称：fdisk
- 命令所在路径：/sbin/fdisk
- 执行权限：root
- 功能描述：分区管理工具
- 语法：

- fdisk–l [-u] [device…]       显示
- fdisk[device]                设置
- 子命令：
- fdisk device
- 子命令：管理功能
- p:print, 显示已有分区；
- n:new, 创建
- d:delete, 删除
- w:write, 写入磁盘并退出
- q:quit, 放弃更新并退出
- m:获取帮助
- l:列表所分区id
- t:调整分区id
- 我们先fdisk -l /dev/sdb看看，sdb硬盘总共8G大，还没有分区
![13](https://github.com/fighting-six/fightingsix/blob/master/picture/13.jpg)

- 使用fdisk /dev/sdb开始进行分区，键入n：创建新的分区，Tip：如果输入错误字符，需要按住Ctrl+←(Backspace)方可删除
![14](https://github.com/fighting-six/fightingsix/blob/master/picture/14.jpg)

- 分配完所需分区后，此时分区表只是存放在内存中，键入w使其生效完成分区
![15](https://github.com/fighting-six/fightingsix/blob/master/picture/15.jpg)

- 查看内核是否已经识别新的分区
- cat/proc/partations
![16](https://github.com/fighting-six/fightingsix/blob/master/picture/16.jpg)

## 3.5.3 创建文件系统(格式化)

- 在Unix/Linux环境下，通常使用mkfs命令执行格式化操作，mkfs命令需要的参数有设备路径和文件系统格式等。需要注意的是：对硬盘执行格式化操作时，用户需要拥有超级用户权限。

- 命令名称：mkfs
- 命令所在路径：/sbin/mkfs
- 执行权限：root
- 功能描述：进行格式化
- 语法：
- mkfs.FS_TYPE [options] /dev/DEVICE
- mkfs –t FS_TYPE [options] /dev/DEVICE
- 选项：
- -t { ext2 | ext3 | ext4 } ：指定文件系统
- -b{ 1024 | 2048 | 4096 } ：指定数据块大小
- -L‘LABEL’ ：指定标签
- -j：相当于 –t ext3
- mkfs.ext3= mkfs –t ext3 = mke2fs –j = mke2fs –t ext3
- -I #：为数据空间中每多少个字节创建一个inode；此大小不应该小于block的大小；
- -N #：为数据空间创建个多少个inode；
- -m #: 为管理人员预留的空间占据的百分比；
- -O FEATURE [,...]：启用指定特性
- -O ^FEATURE：关闭指定特性
- 开始对上述sdb1分区进行格式化，写入文件系统
![17](https://github.com/fighting-six/fightingsix/blob/master/picture/17.jpg)

## 3.5.4 挂载使用
- 在根目录下 mkdir MYDATA，然后用mount命令执行挂载，ls能看到Ext中标准产生的目录，到此硬盘分区，格式化，挂载，一切正常。
![18](https://github.com/fighting-six/fightingsix/blob/master/picture/18.jpg)

