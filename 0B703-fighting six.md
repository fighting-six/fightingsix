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


    mkdir Rpi
    cd Rpi

## 3.1.2 获取树莓派内核源码
- 从GitHub上获取树莓派的内核源码，


    git clone --depth=1 -b rpi-4.14.y https://github.com/raspberrypi/linux.git

## 3.1.3获取交叉编译工具链
- 从GitHub获取树莓派的交叉编译工具：
git clone https://github.com/raspberrypi/tools
- 目前，在 ~/Rpi 目录下已经有了 linux.tar.bz2 以及 tools.tar.bz2 两个压缩包，解压出来即可。最终内核源码以及编译工具的目录分别为：
 ~/Rpi/linux
 ~/Rpi/tools

## 3.1.4  修改环境变量，以方便使用编译工具


    sudo vi ~/.bashrc
- 编辑用户目录下的 .bashrc，把编译工具的执行路径加入到 PATH变量中，即在文件末尾加入以下两行：


    
    export PATH=$PATH:$HOME/Rpi/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian-x64/bin
    export PATH=$PATH:$HOME/Rpi/tools/arm-bcm2708/arm-bcm2708-linux-gnueabi/bin
- 为使环境变量即时生效，可执行：


    source .bashrc


# 3.2 内核的修改和配置、编译

## 3.2.1  树莓派3b+的设备树文件
- 树莓派3b+的设备树文件为：
arch/arm/boot/dts/bcm2710-rpi-3-b-plus.dts

## 3.2.2 内核的配置
- 内核进行默认的配置
	

     make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- bcm2709_defconfig
    
## 3.2.3 编译内核镜像、内核模块以及设备树
- 编译内核镜像、内核模块和设备树：


    make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- zImage modules dtbs -j8


# 3.3 替换树莓派系统的内核镜像、设备树，以及内核模块的安装

## 3.3.1 替换掉树莓派的内核镜像


    sudo scripts/mkknlimg arch/arm/boot/zImage /mnt/fat32/kernel7.img

## 3.3.2 设备树相关文件的替换


    sudo cp arch/arm/boot/dts/*.dtb /mnt/fat32/
    sudo cp arch/arm/boot/dts/overlays/*.dtb* /mnt/fat32/overlays/
    sudo cp arch/arm/boot/dts/overlays/README /mnt/fat32/overlays/

## 3.3.3 内核模块的安装


    sudo make ARCH=arm INSTALL_MOD_PATH=/mnt/ext4 modules_install


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
	 mkfs.FS_TYPE [options] /dev/DEVICE
	 mkfs –t FS_TYPE [options] /dev/DEVICE
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

<font face="黑体" color=gray size=72><P ALIGN="CENTER">第四章 魔镜实验流程

## 4.1实现的功能
 中文显示，天气及天气预报的显示，新闻显示，问候语显示，课程表显示，语音模块



## 4.2各部分具体实现过程

### 4.2.1安装编译平台
 Electron是MagicMirror²的应用程序包，支持Raspberry Pi 2/3的自动安装。
 
 在树莓派上执行以下命令以安装MagicMirror²：
 
 bash -c "$(curl -sL https://raw.githubusercontent.com/MichMich/MagicMirror/master/installers/raspberry.sh)"
 
 即可完成MagicMirror²平台的安装。
 
 可以通过以下命令来完成平台版本的更新：
 
 git pull && npm install


### 4.2.2魔镜屏幕设置常亮
 
 魔镜的显示需要屏幕常亮，不然的话会自动待机息屏，让我们禁用屏幕保护程序：
 
 在终端输入：
 
 sudo nano/etc/xdg/lxsession/LXDE-pi/autostart
 
 并将以下内容添加到文件的底部
 
 @xset s noblank
 
 @xset s off
 
 @xset -dpms
 
 保存并退出。

### 4.2.3语言设置为中文
 
 打开config.js文件，并将将language改成“zh-cn”；

![M_01](https://github.com/fighting-six/fightingsix/blob/master/picture/M_01.png "M_01")
 
 再运行时，就会显示中文。

### 4.2.4显示天气及天气预报
 打开config.js文件，进入后面的网址https://home.openweathermap.org ，来调用天气的API.
 
![M_02](https://github.com/fighting-six/fightingsix/blob/master/picture/M_02.png "M_02")
 
 在该网址上注册后，会得到一个API密钥，

![M_03](https://github.com/fighting-six/fightingsix/blob/master/picture/M_03.png "M_03")

 将这个一串数字，替换掉文档中的 YOUR_OPENWEATHER_API_KEY

![M_04](https://github.com/fighting-six/fightingsix/blob/master/picture/M_04.png "M_04")

此时天气会显示出来NewYork的天气，可以通过location的代码文件，修改里面的城市和location ID,来改为本地天气，如图所示：

![M_05](https://github.com/fighting-six/fightingsix/blob/master/picture/M_05.png "M_05")

### 4.2.5加载底部新闻

模块自带新闻，可以修改RSS 订阅源改为国内的新闻。

![M_06](https://github.com/fighting-six/fightingsix/blob/master/picture/M_06.png "M_06")

可以修改为Engadget中国版并保存：

![M_07](https://github.com/fighting-six/fightingsix/blob/master/picture/M_07.png "M_07")


### 4.2.6问候语设置

为了安装中文问候语，先安装中文输入法：

终端输入：sudo apt-get install scim-pinyin

安装完成后需要重启才能生效

Ctrl+空格 切换中英文。

打开compliments.js文件，位置位于/home/pi/MagicMirror/modules/default/compliments

在相应的位置加上自己想要的问候语。

![M_08](https://github.com/fighting-six/fightingsix/blob/master/picture/M_08.png "M_08")


### 4.2.7小地球图标添加

在终端里输入以下代码：

cd ~/MagicMirror/modules

git clone https://github.com/mykle1/MMM-EARTH.git

cd ~/MagicMirror/modules/MMM-EARTH

npm install

然后再config里面modules模块里添加下面一段代码

{

module: "MMM-EARTH",

position: "bottom_center",

config: {

mode: "Natural",

rotateInterval: 15000,

MaxWidth: "50%",

MaxHeight: "50%",

}

},

运行，即可显示出地球图标。


### 4.2.8添加课程表

在终端依次键入以下代码

cd ~/MagicMirror/modules

gitclone https://github.com/pinsdorf/MMM-WeeklySchedule.git

cd ~/MagicMirror/modules/MMM-WeeklySchedule

npm install

然后再config里面modules模块里添加下面一段代码

{

module: "MMM-WeeklySchedule",

position: "top_left",

header: "Household chores",

config: {

schedule: {

timeslots: [ "Feed thefish", "Set the table", "Take out the trash","Hoover living room" ],

lessons: {

mon: ["Bart", "Marge","Homer", "Lisa" ],

tue: ["Lisa", "Bart", "Marge", "Homer" ],

wed: ["Homer", "Lisa", "Bart", "Marge" ],

thu: [ "Marge","Homer", "Lisa", "Bart" ],

fri: ["Bart", "Marge","Homer", "Lisa" ]

}

},

updateInterval: 1 * 60 * 60 * 1000,// every hour

showNextDayAfter: undefined

}

},

其中，updateInterval 为内容更新频率，1×60×60×1000ms=1h， timeslot和lessons中引号里面为字符串，可以为各种形式，通过修改该部分可以显示课程表。

![M_09](https://github.com/fighting-six/fightingsix/blob/master/picture/M_09.png "M_09")

## 4.3语音模块

### 4.3.1硬件环境搭建

#### 4.3.1.1麦克风配置

1)	使用 lsusb 命令，查看是否连接上 USB 麦克风

![M_10](https://github.com/fighting-six/fightingsix/blob/master/picture/M_10.png "M_10")

2)	安装 arecord： sudo apt-get install arecord

3)	使用 arecord 进行录音测试：

sudo arecord -D "plughw:1,0" -d 5 -r 16000 -c 1 -t wav -f S16_LE test.wav

- D ：选择设备， 外部设备是 plughw:1,0，内部设备是 plughw:0,0， 树莓派本身并没有录音模块，所以没有内部设备。
- d :  录音时间（s），-d 5 的意思就是录制时间为 5 秒，如果不加这个参数就是一直录音直到 ctrl+c 停止
- r : 频率，
- c : 音轨
- t : 文件类型
- f : 格式

录音结束后，文件保存在当前目录。可以通过“ls”命令查看。

#### 4.3.1.2音箱配置

默认的情况下，树莓派是通过 HDMI 输出音频。而音箱需要用到耳机孔输出，这时需要修改树莓派的配置。

1)	sudo raspi-config

2)	Advanced Options

![M_11](https://github.com/fighting-six/fightingsix/blob/master/picture/M_11.png "M_11")

3)	Audio

![M_12](https://github.com/fighting-six/fightingsix/blob/master/picture/M_12.png "M_12")

4)	Force 3.5mm (‘headphone’) jack

![M_13](https://github.com/fighting-six/fightingsix/blob/master/picture/M_13.png "M_13")

确定后可以将树莓派音频输出强制设置为 3.5mm 音频输出接口 （ 3.5mm (‘headphone’) jack ）了。

5)	树莓派上播放音频，在初始化条件下声音比较小，这时可以通过安装
alsamixer 来调节音量。

- 安装：sudo apt-get alsamixer
- 调节：alsamixer(通过键盘的↑、↓进行调节) 播放：aplay test.wav
- 播放：aplay test.wav

### 4.3.2 DuerOS 平台设置

1)	打开 DuerOS 开放平台：https://dueros.baidu.com/open，点击 “登录”，用百度账号进行登录；

2)	登录成功后，点击 “开发者认证”，填写相关信息。并上传身份证照片，要求必须是“身份证原件的照片”，复印件和扫描件都不可以。点击已阅读相关协议，点击提交认证。两个工作日内，即可通过认证。 

![M_14](https://github.com/fighting-six/fightingsix/blob/master/picture/M_14.png "M_14")

3)       点击右上角“控制台”，选择“设备控制台”，点击“配置新设备”

![M_15](https://github.com/fighting-six/fightingsix/blob/master/picture/M_15.png "M_15")

4)	依次选择“音箱”—“Linux”—填写创建的产品名称并申请 client_id— 云服务配置—完成。

5)	将鼠标放在已创建的场景上，可以进行编辑、删除、查看 client_id 等操作。

![M_16](https://github.com/fighting-six/fightingsix/blob/master/picture/M_16.png "M_16")

### 4.3.3 DuerOS Python SDK 的安装

#### 4.3.3.1安装依赖环境

- sudo apt-get updat
- sudo apt-get install python-dateutil
- sudo apt-get install gir1.2-gstreamer-1.0
- sudo apt-get install python-pyaudio
- sudo apt-get install libatlas-base-dev
- sudo apt-get install python-dev
- sudo pip install tornado
- sudo pip install hyper

hyper 库用来支持 http2.0 client, pyaudio 用来支持录音，tornado 用来完成oauth 认证。

#### 4.3.3.2下载并安装编译好的 openssl 和 Python

要更新 openssl 才能支持 python sdk 的使用。

- openssl 安装包：https://eyun.baidu.com/s/3jJmdsbW 密码：EyA4
- python2.7.14 安装包：https://eyun.baidu.com/s/3c3SSVao 密码：0sDM
- sudo tar -zxvf openssl1.1.tar.gz -C /usr
- sudo tar -zxvf python2.7.14.tar.gz -C /usr/local/
- sudo rm -rf /usr/bin/python
- sudo ln -s /usr/local/python2.7.14/bin/python /usr/bin/python


#### 4.3.3.3下载 Python SDK 和参考示例代码

- git clone https://github.com/MyDuerOS/DuerOS-Python-Client.git
- cd DuerOS-Python-Client
- git checkout raspberry-dev

#### 4.3.3.4授权

./auth.sh

直接运行使用默认的 client_id 和 client_secret，也可以替换成个人在 DuerOS
开放平台申请的 client_id 和 client_secret，进而实现在控制台自定义的配置属性。
(修改 app/auth.py 文件)

![M_17](https://github.com/fighting-six/fightingsix/blob/master/picture/M_17.png "M_17")

修改 client_id 和 client_screct 后，需要在开放平台中“安全设置”的“授权回调页"，设置成 http://127.0.0.1:3000/authresponse

![M_18](https://github.com/fighting-six/fightingsix/blob/master/picture/M_18.png "M_18")

![M_19](https://github.com/fighting-six/fightingsix/blob/master/picture/M_19.png "M_19")

#### 4.3.3.5两种触发识别

1)	唤醒加识别（“小度小度”唤醒）

./wakeup_trigger_start.sh

2)	enter 按键触发识别

./enter_trigger_start.sh

### 4.3.4添加或删除 DuerOS 的技能

#### 4.3.4.1	在设备控制台添加或关闭技能

在设备控制台—“编辑”场景—云服务配置中，可以进行默认 BOT 技能的添加和关闭

![M_23](https://github.com/fighting-six/fightingsix/blob/master/picture/M_23.png "M_23")

#### 4.3.4.2	小度之家添加和删除技能

用户可以使用百度 UNIT 平台设计自定义 BOT 技能，技能发布上线后，
DuerOS 平台可以通过 DuerOS 小度之家 APP 中的技能商店安装技能，实现更多功能和自定义功能。通过小度之家添加和删除技能的方法如下：

1)	点击技能商店，选择分类，点击内容资源（智能家居的技能都需要相关设备和绑定相关账号，这里只是进行示例操作，所以没有选择智能家居的技能）；

![M_20](https://github.com/fighting-six/fightingsix/blob/master/picture/M_20.png "M_20")


2)	选择技能“精彩演讲”，点击启用；

![M_21](https://github.com/fighting-six/fightingsix/blob/master/picture/M_21.png "M_21")

3)	通过“小度小度”唤醒树莓派的 DuerOS，说“打开精彩演讲”，树莓派开始播放 TED 演讲，技能可以正常使用；

4)	点击“我的”，可以查看 DuerOS 已有技能，并删除不想要的技能。

![M_22](https://github.com/fighting-six/fightingsix/blob/master/picture/M_22.png "M_22")





