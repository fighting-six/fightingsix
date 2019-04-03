<font face="黑体" color=gray size=72><P ALIGN="CENTER">第一章 开发环境</P></font>
&#160; &#160; &#160; &#160;基于树莓派和主机系统，介绍其执行环境（硬件环境）、运行环境（软件环境）和编程环境。
# 1. 树莓派
## 1.1硬件环境：选用型号：Raspberry 3B+
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
## 1.2 Startup code
&#160; &#160; &#160; &#160;Startup code：启动代码,是连接硬件启动阶段和程序main（）之间连接的软件。
## 1.3  操作系统：Raspbian
&#160; &#160; &#160; &#160;Raspbian是一个基于 Debian 的 Linux 发行版，专门用于 Raspberry Pi，它是Raspberry 用户的完美通用操作系统。Raspbian 采用Open box堆叠窗口管理器和 Pi 改进的 X windows 环境轻量级，并配有许多预装软件，包括 Minecraft Pi，Java，Mathematica 和 Chromium。
## 1.4  Middleware（中间件）
&#160; &#160; &#160; &#160;中间件是一种独立的系统软件或服务程序，分布式应用软件借助这种软件在不同的技术之间共享资源，中间件位于客户机/服务器的操作系统之上，管理计算机资源和网络通讯。
## 1.5 The run-time libraries(运行库)：glibc
## 1.6 编程环境
### c语言
&#160; &#160; &#160; &#160;Editor（编辑器）：vim

&#160; &#160; &#160; &#160;Compiler(编译器): gcc

&#160; &#160; &#160; &#160;Debugger(调试器): gdb

&#160; &#160; &#160; &#160;代码管理器：make

### python
&#160; &#160; &#160; &#160;树莓派系统自带2.7版本的 python 运行环境

# 2. 主机（个人计算机）
## 2.1硬件环境
| 硬件名称  |  型号或数量 |
| :------------: | :------------: |
| 处理器  | Intel i7-4710MQ CPU @2.5GHZ ×8  |
| 内存  | 7.7 GiB  |
|   磁盘|  63.3 GB |
|  图形处理器 | Intel Haswell Mobile /NV118  |
## 2.2 操作系统 Ubuntu 18.10
&#160; &#160; &#160; &#160;Ubuntu（友帮拓、优般图、乌班图）是一个以桌面应用为主的开源GNU/Linux操作系统，Ubuntu 是基于Debian GNU/Linux，支持x86、amd64（即x64）和ppc架构，由全球化的专业开发团队（Canonical Ltd）打造的。
## 2.3 Middleware（中间件）
&#160; &#160; &#160; &#160;中间件是一种独立的系统软件或服务程序，分布式应用软件借助这种软件在不同的技术之间共享资源，中间件位于客户机/服务器的操作系统之上，管理计算机资源和网络通讯.
## 2.4 The run-time libraries(运行库)：glibc
## 2.5 编程环境
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
<font face="黑体" color=gray size=72><P ALIGN="CENTER">第二章</P></font>

# 1.项目名称：魔镜
# 2.项目内容
&#160; &#160; &#160; &#160;利用树莓派和原子镜，完成显示屏一边和镜子一样反射光线显示镜像，一边与树莓派相连，动态显示天气、温湿度信息等任务。借助语音识别sdk,完成人机交互。
# 3.项目架构 
## 3.1 项目关联图
![项目关联图](https://github.com/fighting-six/fightingsix/blob/master/picture/pic1.jpg "项目关联图")
## 3.2 项目架构图
![项目架构图](https://github.com/fighting-six/fightingsix/blob/master/picture/pic2.jpg "项目架构图")


