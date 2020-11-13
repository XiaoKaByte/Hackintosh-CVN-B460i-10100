<p align="center">
	<strong>Hackintosh-CVN-B460i-10100</strong><br>
  <strong>Big Sur+i3-10100+CVN B460i Gaming V20</strong>
</p>
<p align="center">
    <a href="https://github.com/xiaoka-li/Hackintosh-CVN-B460i-10100">
      <img alt="OpenCore" src="https://img.shields.io/badge/OpenCore-0.6.3-brightgreen">
    </a>
    <a href="https://github.com/xiaoka-li/Hackintosh-CVN-B460i-10100">
      <img alt="MacOS" src="https://img.shields.io/badge/MacOS-BIgSur-brightgreen"/>
    </a>
</p>

### 硬件配置清单

| 配置   | 型号                    |
| ------ | ----------------------- |
| CPU    | i3-10100                |
| 主板   | 七彩虹 B460i Gaming V20 |
| 内存   | 枭鲸 DDR4 2666Hz 8x2    |
| 硬盘   | WD SN550 M.2 250G       |
| 散热   | HP400 mini              |
| 电源   | ms450                   |
| 机箱   | 酷鱼 T40                |
| 显示器 | KOIOS K2718UD 4K 27 寸  |
| 键盘   | 黑爵 K870T              |
| 鼠标   | 罗技 K304               |

### 使用工具及版本

- **系统版本：BigSur**
- **引导版本：OpenCore 0.6.3**

### 目前系统完善状态

> 网卡型号为 INTEL AX200

- [x] 短睡眠正常
- [x] 核显驱动正常
- [x] 蓝牙驱动正常
- [x] WIFI 驱动正常
- [x] AppleId 正常
- [x] 有线网卡正常
- [x] AirPort 正常
- [ ] 长时间睡眠有问题
- [ ] HDMI没有进行测试，如果黑屏需要进行hdmi修复

### 使用注意事项

* 修改platforminfo设置里的三码
* 如果用hdmi，需要在deviceProperties里修复hidmi
* 其余根据opencore官方安装文档进行调试

### 总结
**本人小白一枚，发现没有同配置，全是跟着opencore官方安装教程进行安装调试，虽然不是100%完美，但已经满足日常使用需求，黑苹果的乐趣在于折腾！**

### 感谢
* opencore 
* OpenIntelWireless
* 黑果小兵
