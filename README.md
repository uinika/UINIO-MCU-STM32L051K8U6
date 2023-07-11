# UINIO-MCU-STM32L051K8 开发板

这是一款基于**意法半导体** [STM32L051K8U6](https://www.st.com/en/microcontrollers-microprocessors/stm32l051k8.html) 低功耗微控制器的核心板电路设计，该款主控芯片采用 **LQFP32** 封装，并且内置 `64 Kbytes` 的 Flash 存储器，以及 `8 Kbytes` 的 RAM 存储器。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

- 采用 `16 Pin` 的 **USB Type-C** 接口；
- **STM32L051K8U6** 的 **28** 个 **GPIO** 引脚资源全部悉数引出；
- 添加了 `Imax` 为 `750mA` 的自恢复保险丝，防止后级操作短路损毁芯片；
- 预留有 `32.768KHz` 贴片晶振封装的位置（可选）；
- 预留 **SOIC** 封装的 **W25Q** Flash 存储器封装位置（可选）；