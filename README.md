# UINIO-MCU-STM32L051K8U6 核心板

[**UINIO-MCU-STM32L051K8U6**](https://gitee.com/uinika/UINIO-MCU-STM32L051K8U6) 是一款基于**意法半导体** [STM32L051K8](https://www.st.com/en/microcontrollers-microprocessors/stm32l051k8.html) 系列低功耗微控制器的核心板电路设计，该款主控芯片采用 **LQFP32** 封装，基于 **ARM Cortex-M0+** 架构，片上内置有 `64 Kbytes` 的 **Flash** 存储器，以及 `8 Kbytes` 的 **RAM** 存储器。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

## 设计概要

1. 采用 `16 Pin` 规格的 **USB Type-C** 接口；
2. 已经将 **STM32L051K8** 微控制器的 **28** 个 **GPIO** 引脚资源悉数引出；
3. 预留有 **SOIC** 封装的 **W25Q** 型 Flash 存储器焊接位置（可选）；
4. 预留有 **3215** 封装 `32.768KHz` 频率贴片晶振的焊接位置（可选）；
5. 单独提供有 4 线制 **SWD** 下载接口，便于快速与 **DAP-Link** 连接调试；
6. 添加了 `Imax` 为 `750mA` 的自恢复保险丝，防止后级操作短路损毁芯片；

## 参考技术文档

[UinIO.com 电子技术实验室](http://uinio.com/) 为 UINIO-MCU-STM32L051K8U6 开源项目提供了如下一系列技术参考资料：

1. [《意法半导体 STM32F103 标准库典型实例》](http://uinio.com/Embedded/STM32F103/)
2. [《基于 HAL 与 LL 的 STM32F401 开发实践》](http://uinio.com/Embedded/STM32F401/)
3. [《ARM 调试工具 UINIO-DAP-Link 应用详解》](http://uinio.com/Project/UINIO-DAP-Link/)
4. [《BOM 交互式物料清单与 PCB 布线在线预览》](http://uinio.com/archives/BOM/UINIO-MCU-STM32L051K8U6.html)
