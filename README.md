本项目用于记录 ZYNQ_CORE_484 和 ZYNQ_CORE_400  板卡的相关信息 。

包括硬件介绍 ，开发例程等等 。

Github :  https://github.com/Digital-Blocks-design/ZYNQ_CORE

Gitee加速访问 ：https://gitee.com/gongwenhong/ZYNQ_CORE

【注】Gitee和Github同步更新 。



### 1，硬件介绍 

点击链接，访问板卡用户手册 ：
ZYNQ_CORE_484 ：[板卡用户手册](./ZYNQ_CORE_484/User_Manual_CN.md) 
ZYNQ_CORE_400 ：[板卡用户手册](./ZYNQ_CORE_400/User_Manual_CN.md) 

ZYNQ_CORE_484 和 ZYNQ_CORE_400的 板卡的主要差异为主芯片型号不同 ，具体差异详见如下文档：[板卡差异说明](./板卡差异说明.md) 




### 2，USB_JTAG编程工具

该编程工具用于对该核心板上的仿真器电路进行编程 。

编程工具的位置源仓库地址如下 ： [USB_JTAG编程工具](https://github.com/Digital-Blocks-design/open_jtag_smt3/tree/master/tools/USB_JTAG%E7%BC%96%E7%A8%8B%E6%96%87%E4%BB%B6) 

该文件夹下有两个版本的编程文件，版本号分别为 **V1.0** 和 **V1.1** 。

![编程文件](image/%E7%BC%96%E7%A8%8B%E6%96%87%E4%BB%B6.png)

 **V1.0** 和 **V1.1** 的区别为用户自定义的仿真器编号定义不同 。

 **V1.0** ：用户需输入至少8个ASSCLL字符串 ，用作仿真器序列号 。

 **V1.1** ：用户需输入至少2个ASSCLL字符串 ，程序会计算当前日期的时间，并自动填充到仿真器序列号中 。

编程工具的具体使用方法，请参考如下链接文档： [USB_JTAG编程工具使用说明](https://github.com/Digital-Blocks-design/open_jtag_smt3/blob/master/tools/USB_JTAG%E7%BC%96%E7%A8%8B%E6%96%87%E4%BB%B6/readme.md) 

