## 基本资料: 

- 姓名： 逯奇峰
- 手机： 18611862869
- 邮箱： 
    - ddcien@163.com
    - ddcien.lu@gmail.com

---
## 教育背景: 

2003/09 ~ 2007/07 电子科技大学(UESTC/成都) 电子信息工程 本科

---
## 工作经历

### 2016/09 ~ 至今 北京博源恒芯科技股份有限公司

- 职务：高級嵌入式软件工程师
- 职责：负责喷墨打印控制系统中主控板，喷头控制板，以及各类外围板卡软件研发工作。


#### 主要项目：

##### Sx00(S100/SC100/S300/S350)系统

Sx00系统是大型扫描喷墨控制系统中的主控板系统，该系统硬件使用CycloneV和Zynq7000为主控芯片, 
采用RT-Linux(PREEMPT_RT)搭配Embedded Debian作为其操作系统。

- bootloader移植, 功能开发；
- Linux内核剪裁配置；
- Embedded Debian 操作系统跟文件系统的构建(基于*debootstrap*)；
- 内核层软件开发，*datapath*管理， *运动控制*执行单元和其他外设驱动程序；
- 业务层软件架构的设计和实现；
- FX3固件开发；
- 应用层软件开发，系统状态监控和管理服务程序，使用Python开发，实现软件系统升级等维护性功能;
- 编译环境构建， 采用*vagrant*构建虚拟机镜像，保持工程师与发布构建服务器的编译环境一致性;
- 软件烧录流程的实现；


##### ETH2USB 板卡

ETH2USB板卡实现通过网络访问USB设备，功能类似*USB/IP*，支持一对多，即该板卡上可连接多个USB设备。
该板卡采用全志(Allwinner)H5处理器, 搭配*armbian*操作系统。
该项目软件部分由本人独立完成，使用Python3编写，采用python asyncio和libusb的异步传输方式实现高数据吞吐性能。 

##### 工装系统 (两代)

工装系统为公司内部项目，用于板卡生产和返修检测。

- 整体软件方案和架构设计;
- 为若干板卡编写硬件测试程序；

---

### 2014/09 ~ 2016/06 北京释码大华科技有限公司

- 职务：嵌入式部门经理
- 职责：负责嵌入式部门管理, 以及完成基于虹膜识别技术的各类设备的研发工作。


#### 主要项目: 

##### 虹膜识别核心模块

虹膜识别核心模块是一个体积小，功耗低，方便集成的硬件产品。该模块完整的封装了虹膜采集，比对，存储等功能，能够独立完成从虹膜采集到比对结果输出的一整套流程。

- 项目管理，制定开发计划，协调软件，硬件，测试等多部门，推进开发进程。
- 软件架构以及接口设计；
- 制定统一开发和测试构建环境；

--- 

### 2010/05~ 2014/04 斯玛特电子设备（北京）有限公司
职务：高级嵌入式Linux系统工程师

职责：负责ARM-Linux平台软件开发工作，以及项目管理等。

#### 主要项目:

- SignaturePAD

    - 底层软件开发，bootloader，Linux Kernel，外设驱动程序。
    - 根文件系统构建。
    - 为普通电阻式触摸屏添加压力检测功能，实现签名笔记的粗细变化。
    - 应用层，基于Cario/FreeType等开源组件, 在FrameBuffer上实现一套图形系统，实现信息和广告显示，签名录入等功能。


--- 
### 2007/07~2010/04 天津通信广播集团有限公司

职务：嵌入式软件工程师

职责：ARM7/9平台下的嵌入式软件开发，Bare-Metal/uCOS-II/FreeRTOS/Linux等。

#### 主要项目:

- POC(Push to Talk Over Cellular)手持终端

    - 底层软件开发(bootloader，Linux Kernel, 外设驱动程序)
    - 根文件系统构建。


---
## 专业技能

- Embedded software development
- Performance Evaluation and Optimization
- Debugging and problem solving
- Bare-Metal/RTOS(FreeRTOS, uCOS-II(I), RT-Thread)/Linux(Vanilla/RT)
- Linux kernel development
- ARM architecture(7/9/Cortex-M/A)
- c/python/cpp/lua/tcl/bash
- vim(neovim), git, cmake, gdb, gcc, cross compiling
- Openocd/PyOCD
- Markdown

--- 
## 自我评价

本人2007年毕业于电子科技大学，电子信息工程专业。在嵌入式领域有超过15年的工作经验。
对嵌入式软件系统的开发具有丰富经验，包括Bare-Metal, RTOS(uCOS-II/FreeRTOS/RtThread), Linux Kernel (Mainline(Vanilla)/Realtime)。
熟练掌握Linux平台下各种开发工具，gcc、git，gdb(-multiarch), (neo)vim，cmake, openocd, pyocd等。
熟悉嵌入式处理器编程模型以及常用外设，如UART/SPI/I2C/CAN/DMA等。
精通C语言，熟悉Python语言，能够快速实现评估验证和测试。
本人性格开朗，真诚，乐观，易相处；具有团队精神，学习能力强；有高度的责任感和自制力，工作积极进取，开发经验丰富，善于解决工作中出现的各种问题。

