# 100ASK_STM32MP157_PRO开发板
<iframe src="//player.bilibili.com/player.html?aid=65976587&bvid=BV1w4411B7a4&cid=114456591&page=1" scrolling="no" border="0" framespacing="0" allowfullscreen="true" width="800" height="600" frameborder="no"> </iframe>

## sdk完整包下载

### 下载说明

​	我们使用推荐使用免费的p2p 微力同步下载，下载的人越多，速度越快，同样我们有更新您也可以实时获取到最新内容。


* 资源获取方式VesySync使用的是密钥，百度网盘使用的分享链接和密码

| 版本| 微力同步资料光盘密钥                                    | 百度网盘资料光盘下载链接 | 更新状态|
|------| ------------------------------------------------------- | ------------------------ |----|
|V1 | B3ALD5T547FJZAPHTFGQ6HNQTQ3QDALMDLK62DLWQOCRLNAJ254VZVE |                          | 长期更新|

  

#### VesySync方式下载

* 软件使用说明  http://www.verysync.com/manual/users/ui.html

#### 百度网盘方式下载

* 百度网盘下载使用说明 

  

### 开发资源包

​	100ASK_STM32MP157_PRO开发板配套资源包涉及用户手册，芯片手册，硬件原理图，应用编程示例和文档以及配套的系统源码等，系统源码我们统一使用repo + git来统一进行管理，方便用户可以实时获取我们最新的源码资料等信息，对于文件系统我们专门适配到buildroot 2020 lts版本，用于初学者进行学习研究，同时提供yocto系统，用以发布环境。

#### 开发资源包目录结构

> 如下列表介绍了资料光盘内各个目录都包含了哪些文件。

|目录名称 | 目录内容简介 |
| --- | ---- |
| 00_UserManual 	|**手册**：目录内包含开发板使用的用户手册文档和一些笔记。|
| 01_Tools       | **工具**：目录内包含157开发所需工具，包含ubuntu虚拟机镜像，stm32mp157烧写工具，m4开发IDE等。 |
| 02_Images          |**系统固件**：目录内包含stm32mp157开发板预编译的系统镜像文件，有yocto生成的系统镜像buildroot生成的镜像和yocto镜像。|
| 03_Examples    |**例程**：目录内包含适合于stm32mp157开发板应用开发例程和手册说明，以及其它相应例程文件/资料。|
| 04_Lib           |**库**：暂为空。|
| 05_Hardware           |**原理图**：包含stm32mp157开发板底板原理图 位图 以及其它模块或芯片的原理图文件等。|
| 06_Datashee      |**数据手册**：包含cpu开发手册和核心板底板的外围芯片手册资料。|
| 07_Bsp_sdk            |**BSP包**：包含stm32mp157开发板编译整个系统所需的源码压缩包，含有 uboot kernel rootfs等。|
| 08_Reference material  |**ARM,ST参考资料**：包含学习嵌入式开发所需的一些列资料，有ubuntu教程，LinuxC教程，arm官方参考资料，ST官方参考资料。|
| 09_NoOS ·|**裸机程序**：包含stm32mp157开发板的裸机程序源码和相应教程（暂为空）。|


#### 更新日志

* 2020-07.23 发布预览版本。



## sdk资源包内容详细说明

### STM32MP1开发板手册文档

> 介绍STM32MP157 CPU配套开发手册位置以及内容简单说明。

* 100ask_ stmm32mp157_pro开发板用户手册

| 文档名称 | 文档内容简介 | 文档所在位置 |
| -------- | ------------ | ------------ |
|          |              |              |
|          |              |              |

* 100ask_ stmm32mp157_pro开发板学员笔记

  

### 预编译系统镜像包

> 介绍开发板除默认出厂自带系统以外的其它系统镜像文件所在位置以及系统镜像的特征。

* Buildroot预编译系统镜像

| 系统镜像名称 | 版本 | 系统镜像简介 | 镜像文件所在位置 |
| ------------ | ---- | ------------ | ---------------- |
|              |      |              |                  |
|              |      |              |                  |




* Yocto预编译系统镜像

| 系统镜像名称 | 版本 | 系统镜像简介 | 镜像文件所在位置 |
| ------------ | ---- | ------------ | ---------------- |
|              |      |              |                  |
|              |      |              |                  |




* 其它发行版系统镜像

| 系统镜像名称 | 版本 | 系统镜像简介 | 镜像文件所在位置 |
| ------------ | ---- | ------------ | ---------------- |
|              |      |              |                  |
|              |      |              |                  |

### 更新工具

> 介绍烧写/更新系统工具的所在位置，以及如何使用更新工具教程参考资料所在位置。

* stm32cubeprog

| 工具完整名称 | 所在位置 | 使用说明 |
| ------------ | -------- | -------- |
|              |          |          |
|              |          |          |



### 构建工具链

> 介绍开发板系统配套的交叉编译工具所在位置和特征，以及区别。

* 交叉编译工具链


| 工具链名称 | 工具链特征 | 工具链版本|
| ---------- | ---------- |---------- |
|            | buildroot |  |
|            | yocto |  |
|            | linaro |  |



### 系统源码

> 介绍配套的系统源码版本以及特征。

* Bootloader

| 版本 | 源文件所在位置 | git仓库地址 |
| ---- | -------------- | ----------- |
| uboot 2020.02      |                |             |
|      |                |             |
|      |                |             |


* LinuxKernel

| 版本 | 源文件所在位置 | git仓库地址 |
| ---- | -------------- | ----------- |
|  5.4 LTS      |                |             |

* rootfs


| 版本 | 源文件所在位置 | git仓库地址 |
| ---- | -------------- | ----------- |
|  Buildroot 2020.02 LTS     |                |             |
|  Ycoto zeus        |                |             |
|  Busybox        |                |             |





### 应用程序示例

| 示例名称 | 示例简述  | 示例所在位置|
| ---------- | ---------- |--------|
| Qtgui                    | 基于qt 5.12 LTS                  |





### M4协处理器






### 开发板芯片手册

> 介绍100ASK_STM32MP157_PRO开发板除CPU以外其它芯片的参考资料，包含芯片手册。

* stm32mp157 MPU相关

| 手册名称 | 手册作用 | 手册位置                    |
| -------- | -------- | --------------------------- |
|          |          | 06_Datasheet\Core_board\CPU |
|          |          | 06_Datasheet\Core_board\CPU |

* Wifi&Bluetooth

| 手册名称 | 手册作用 | 手册位置                                                     |
| -------- | -------- | ------------------------------------------------------------ |
|          |          | 06_Datasheet\Base_board\100ask_stm32mp157_pro底板_规格书\WIFI&Bluetooth |
|          |          |                                                              |

* Audio

| 手册名称 | 手册作用 | 手册位置                                                     |
| -------- | -------- | ------------------------------------------------------------ |
|          |          | 06_Datasheet\Base_board\100ask_stm32mp157_pro底板_规格书\Audio |


* Rs485

| 手册名称 | 手册作用 | 手册位置 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |

* Can

| 手册名称 | 手册作用 | 手册位置 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |

* Emmc

| 手册名称 | 手册作用 | 手册位置 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |

* Sdram

| 手册名称 | 手册作用 | 手册位置 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |



### 硬件文档

> 介绍100ASK_STM32MP157_PRO开发板配套的硬件资料版本以及文档内容作用简单说明。

* 核心板

| 文档名称 | 文档作用 | 文档位置 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |

* 底板

| 文档名称 | 文档作用 | 文档位置 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |

* 扩展模块

| 文档名称 | 文档作用 | 文档位置 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |

