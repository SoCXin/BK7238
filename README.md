# [BK7238](https://doc.soc.xin/BK7238)

* [bekencorp](http://www.bekencorp.com/)：[RISC-V](https://doc.soc.xin/architecture/riscv)
* [L2R2](https://github.com/SoCXin/Level)：160 MHz

## [简介](https://doc.soc.xin/BK7238)

[BK7238](http://www.bekencorp.com/index/goods/detail/cid/42.html) 是一款高度集成的单芯片Wi-Fi802.11n和低功耗蓝牙(BLE)5.2组合解决方案，专为低功耗和小空间应用设计的。

### 关键特性

* 160 MHz
* 288KB SRAM + 1MB/2MB SiP FLASH
* 802.11b/g/n 1x1协议，支持20/40 MHz带宽和STBC
* 支持BLE v5.1，-90dB灵敏度和20dBm输出功率
* QFN40(5x5mm)/QFN32(4x4mm)/QFN20(3x3mm)
* 工作温度范围 -40 至 +105°C

#### Wi-Fi

* IEEE 802.11 b/g/n 1x1，支持 20 MHz
* 输出功率功率高达 +19 dBm
* 接收器灵敏度 -99 dBm


#### BLE

* BLE 5.2 1 Mbps、2 Mbps 和远距离（125 kbps 和 500 kbps）
* 蓝牙测向：到达角 (AoA) 和出发角 (AoD)
* 支持多达16根天线的天线阵列，实现室内精准定位
* 集成蓝牙 LE/WLAN 共存 (PTA)


#### 功耗

* 2.7-3.6V VBAT
* 主动模式 RX：30 毫安
* 正常待机模式：300 μA
* 低电压待机模式：75 μA
* 关断模式：0.5 μA

外设

* GPIO：QFN32中有19个，QFN20中有9个
* 1个SPI
* 2个UART：1个支持闪存下载
* 1个I2C
* 1个具有6个通道的通用DMA控制器(GDMA)
* 6个32位PWM
* 10位SARADC，最多6个通道
* 6个通用32位定时器/计数器
* 1个看门狗定时器
* 1个实时计数器(RTC)
* 1个温度传感器
* 1个真随机数生成器(TRNG)


### [收录资源](https://github.com/SoCXin/BK7238)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

### [选型建议](https://github.com/SoCXin)

[BK7238](https://github.com/SoCXin/BK7238)

### [www.SoC.xin](http://www.SoC.Xin)
