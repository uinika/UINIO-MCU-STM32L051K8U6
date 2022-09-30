# UINIO-EVB-STM32L051K8 评估板

基于 [STM32L051K8](https://www.st.com/en/microcontrollers-microprocessors/stm32l051k8.html) 微控制器的评估板，花了 3 天的业余时间完成绘制，虽然布局和走线不够优雅，但是能够满足正常的开发评估。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

- 提供有外部贴片晶振；
- 采用 **USB Type-C** 接口；
- 添加了 `Imax` 为 `750mA` 的自恢复保险丝，防止后级操作短路损毁芯片；
- **28** 个 **GPIO** 引脚全部引出；
- 自带 SOIC 封装的 **W25Q** Flash 存储器芯片；
