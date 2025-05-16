---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 📌 **游荣强，技术总监/CTO，21年技术研发与管理经验。**
- 1、精于0到1团队建设，系统架构设计，研发流程管理，产研一体化对接，交付实施推进。
- 2、PMP，PgMP，CSPM-4，ESG高级分析师等项目认证。 
- 3、中国标准化协会项目管理专家组成员。 
- 4、多年军工设备研发经验，熟知GJB9001C，GJB5000B，CMMI等各种标准化体系 
- 5、精通各种CPU/NPU/GPU硬件架构、运行原理，指令流水线等。对实时系统底层理解透彻。具备从祼机到多任务内核开发能力 
- 6、精通汇编语言和C/C++语言，熟练使用各种编程语言(C#、Go、VBA、Python、Java/JS、PHP等) 
- 7、精通各种嵌入式RTOS原理、应用开发、驱动架构，包括uC/OS、FreeRTOS、RT-Thread、VxWorks、Linux等。 
- 8、熟悉各种数据库应用,SQL、MongoDB、SQLite、Redis等。 
- 9、熟悉各种系列MCU/DSP硬件架构,CortexM，MIPS，PPC，Cortex-A，RISCV，ZYNQ等。 

<span class='anchor' id='education'></span>
# 📖 学历

- *2025 - 2027*, **硕士**, **复旦大学**, 项目管理 (PreMEM).

- *2000 - 2004*, **学士**, **南京航空航天大学**, 自动化.

<span class='anchor' id='job'></span>
# 💻 工作

- *2025.02 - 至今*, **研发总监**, 南京某航天所配套公司.
  - 团队建设：从0开始组建平台、终端、终端硬件研发团队，优化项目管理体系，规范团队开发流程
  - 产研交付：单机产品研发，包括各类传感器、控制器、执行器等，现场交付实施管理

- *2022.09 - 2025.02*, **研发总监**, 南京某新能源科技有限公司.
  - 团队建设：从0开始组建约30人的平台、终端、终端硬件研发团队，优化项目管理体系，规范团队开发流程
  - 终端系统架构：负责产品规划，EMS能源管理终端，以及各类表计智慧能源单元，相关单元硬件系统架构设计，技术攻关
  - 平台系统架构：负责综合能源、综合管理、双碳平台、管理平台，以及各类微服务架构的电力应用架构，对接终端的平台一体化经济分析体系架构
  - 负责各类设备/能源终端的服务端系统，为各类能源开发提供完备服务
  - 负责产品管理及各类系统，确保终端产品稳定性，MES系统，优化各类终端现场安装调试流程，技术攻关相关节点
  - 提交多项发明专利(已授权)

- *2021.08 - 2022.08*, **技术总监**, 南京某打印技术有限公司.
  - 负责打印设备研发技术总监。负责打印设备研发，包括新一代硬件系统，Cortex-A7主控芯片，Cortex-M4时钟控制芯片，以及EPGA实现的图像数据传输部分组成
  - 负责编写Bootloager和基础RT-Thread应用程序，以及各类芯片驱动，包括Linux平台下的定位打印系统
  - 负责芯片驱动和FPGA通信接口，通过IO接口级联FPGA从而节省硬件，提高系统效率，降低维护成本
  - 在任提交打印相关专利一项

- *2019.12 - 2021.08*, **研发总监**, 南京某通信科技有限公司.
  - 负责DTU/FTU项目，FreeRTOS/Linux应用系统设计，产品系统架构设计，硬件选型等
  - 负责103/104协议XCP/OCPP协议应用设计
  - 负责实现DTU模块化平台，包括PCLinux

- *2018.08 - 2019.12*, **项目经理/总监**, 南京某通信股份有限公司.
  - 负责15人团队派驻OPPO，智能手表底层系统，BTIBLT底层模块开发
  - 使用C语言，RT-Thread操作系统，多级bootloader开发，硬件驱动开发，BTBLE应用开发
  - 负责团队为某平头哥RISC-V架构芯片做FFT/DFT等数学算法优化，使用RISC-V纯汇编语言
  - 负责团队为FFMPEG在RISC-V芯片的汇编级优化移植

<span class='anchor' id='skills'></span>
# 🛠️ 专业技能

- **系统架构**: 精通CPU硬件架构设计原理、指令流水线等，实时系统底层和高层具备扎实功底
- **编程语言**: 精通汇编和C/C++语言，熟练使用各类编程语言(C#、Go、VBA、Python、Java/JS、PHP等)
- **操作系统**: 精通各类嵌入式RTOS原理及应用开发，如uC/OS、FreeRTOS、RT-Thread、VxWorks、Linux等
- **数据库**: 熟悉各类数据库应用，SQL、MongoDB、SQLite、Redis等
- **硬件平台**: 熟悉各类系列MCU/DSP硬件架构，CortexM、MIPS、PPC、Cortex-A、RISCV、ZYNQ等
- **英语水平**: CET4

<span class='anchor' id='projects'></span>
# 📋 项目经历

- *2019.09 - 2019.11*, **RISC-V通信算法实现**
  - 为平头哥RISC-V系列CPU提供通信算法支持，使用纯汇编语言实现
  - 完成基础算法200多行汇编实现，总共3万多行汇编代码
  - 实现200多个数学计算函数，以及4万多行C语言验证系统

- *2019.05 - 2019.08*, **ZynqUltraScale+平台**
  - 使用vivado/petaLinux为客户定制开发FreeRTOS和Linux下的驱动程序
  - 实现相关设备驱动，包括UART/CAN/I2C/SPI等接口
  - 实现双路1080P视频H264编解码，双路音频MP3格式编解码

- *2018.08 - 2018.12*, **AMI平台**
  - 使用ASpeed公司AST1250/2300硬件BMC平台，基于MDS架构Linux平台
  - 对公司相关产品项目BMC模块功能进行开发和维护
  - 负责Cortex内核A2F500的BMC系统开发和维护

- *2018.07 - 2018.08*, **vxworks下的yaffs文件系统**
  - 实现vxWorks下NAND文件系统，使用yaffs direct接口
  - 将vxworks的nand与vxb对接，实现应用程序操作文件的POSIX相关接口

- *2018.01 - 2018.06*, **Cortex-M3平台BMC系统开发与维护**
  - 负责Cortex-M3平台BMC系统在多个项目中的维护和开发

- *2017.05 - 2018.01*, **嵌入式产品通用web配置系统**
  - 开发公司产品通用的web配置化界面系统
  - 实现vxworks和linux系统的统一配置
  - 使用php+lighttpd+sqlite和goahead+ini方式实现配置存储

- *2015.12 - 2016.06*, **AK双路视频录制系统**
  - 基于66AK双CPU板，对多路视频音频进行H264、MP3编解码
  - 通过rapidIO高速总线连接SSD存储系统
  - 实现双路1080P视频文件录制回放

- *2014.12 - 2015.04*, **CT图像处理**
  - 实现微光镜头采集数据并进行医学相关算法处理
  - 在Linux平台下使用QT实现，C++开发
  - 完成视频数据采集、图像处理、图像显示、图像录制等功能

- *2011.03 - 2011.05*, **BSP项目**
  - 负责ARM平台vxworks BSP移植和裁剪
  - 包括philips ARM平台和samsung ARM平台的相关应用

- *2007.08 - 2009.04*, **CDMA手机中的Phonebook**
  - 负责Motorola系列CDMA手机中的phonebook settings模块开发和维护

- *2004.07 - 2007.08*, **嵌入式系统工程师/项目经理**
  - 负责AD BlackfinDSP平台硬件设计、系统架构
  - 负责Philips LPC ARM平台硬件设计、驱动、系统架构
  - 负责通信终端、uC/OS系统平台开发
  - 负责vxworks产品平台架构、驱动、应用开发
  - 负责项目管理和团队组建

- *2006.04 - 2006.09*, **DSP数据采集处理项目**
  - 使用ADI DSP设计的数据采集处理系统
  - 作为独立模块应用在公司相关产品中

- *2006.02 - 2006.05*, **分板测试平台**
  - 基于ARM平台实现分板产品的分板测试
  - 在测试过程中发现多个严重问题，提高了产品的可靠性

<span class='anchor' id='academic'></span>
# 📖 学术

- [论文：探讨电气的自动化在电气工程中融合应用](http://xueshu.qikan.com.cn/preview/1/85/792350)
- **专著：《电力物联网：智能感知技术与应用》，副主编**

<span class='anchor' id='certification'></span>
# 📌 专业认证

- **PMP项目管理认证**
- **PgMP项目集管理认证**
- **数据分析师高级工程师证书**
- **ESG高级分析师**
- **CSPM-4中国标准项目管理认证（最高级）**
- **中国标准化协会项目管理专业专家库成员**

<span class='anchor' id='contact'></span>
# 📞 联系方式

- **电话**: 17715266546
- **邮箱**: gllier@163.com
- **所在地**: 南京
