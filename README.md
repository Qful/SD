# [PCIe HUB](https://github.com/qful/PCIeHUB) 
[![sites](qful/qful.png)](http://www.qful.net)
####  qitas@qitas.cn
## [简介](https://github.com/qful/PCIeHUB) 

- 自适应接口，可以在一个硬件载体上自适应延伸
- EXT板卡总线，将多个串行设备通过一条硬件链路连接到外部再分线，实现外部线缆的数量最小化，同时支持各种无线连接。
- 管理服务器，所有的设备显示呈现通过浏览器，而作为服务端可以直接连接需要的外设和硬件，实现最大程度的免驱。


### [工程目录](https://github.com/qful)

- [文档](docs/)
- [资源](src/)
- [工程](project/)


### 实施方案

#### [CH368总线接口芯片](http://www.wch.cn/products/CH368.html) 

CH368是PCI-Express总线的接口芯片，支持I/O端口映射、存储器映射、扩展ROM以及中断。CH368将高速PCIE总线转换为简便易用的类似于ISA总线的32位或者8位主动并行接口，用于制作低成本的基于PCIE总线的计算机板卡，以及将原先基于ISA总线或者PCI总线的板卡升级到PCIE总线上。

PCIE总线与其它主流总线相比，速度更快，实时性更好，可控性更佳，所以CH368适用于高速实时的I/O控制卡、通讯接口卡、数据采集卡等。


### [单元组件](https://github.com/qful)

- [type-c组件](https://github.com/qful/entypec)


### [Q资源依赖](https://github.com/qful)

- [Q软件](https://github.com/OS-Q)
- [Q硬件](https://github.com/sochub)
- [Q智慧](https://github.com/tfzoo)
- [Q品质](https://github.com/qitas)