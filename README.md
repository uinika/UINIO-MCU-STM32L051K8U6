# UINIO-MCU-STM32L051K8U6 核心板

[**UINIO-MCU-STM32L051K8U6**](https://gitee.com/uinika/UINIO-MCU-STM32L051K8U6) 是一款基于**意法半导体** [STM32L051K8](https://www.st.com/en/microcontrollers-microprocessors/stm32l051k8.html) 系列低功耗微控制器的核心板电路设计，该款主控芯片采用 **LQFP32** 封装，基于 **ARM Cortex-M0+** 架构，片上内置有 `64 Kbytes` 的 **Flash** 存储器，以及 `8 Kbytes` 的 **RAM** 存储器。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

1. 采用 `16 Pin` 规格的 **USB Type-C** 接口；
2. 已经将 **STM32L051K8** 微控制器的 **28** 个 **GPIO** 引脚资源悉数引出；
3. 预留有 **SOIC** 封装的 **W25Q** 型 Flash 存储器焊接位置（可选）；
4. 预留有 **3215** 封装 `32.768KHz` 频率贴片晶振的焊接位置（可选）；
5. 单独提供有 4 线制 **SWD** 下载接口，便于快速与 **DAP-Link** 连接调试；
6. 添加了 `Imax` 为 `750mA` 的自恢复保险丝，防止后级操作短路损毁芯片；
