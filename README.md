# Hackintosh-4590
---
### 硬件概况
- **OpenCore版本：** 0.7.8
- **macOS版本：** macOS 11.6 BigSur

### 硬件概况
- **主板：** 技嘉B85-D3V
- **CPU：** Intel Xeon E3-1246 v3 (4C8T)
- **核显：** Intel P4600 (HD4600)
- **内存：** 32G DDR3 1600Mhz (4x8G)
- **有线网卡：** Rtl8168
- **无线网卡:** Dell DW1560 (BCM94352Z)
  - 也可使用 Apple BCM943224PCIEBT2

### BIOS设置
- **关闭CSM** 仅使用纯UEFI启动
- **关闭SecurityBoot** 禁用安全启动
- **启用VT-x** 启用虚拟化功能
- **关闭VT-d** 禁用虚拟化直通
- **显存预分配大小** 设置为64M

### 运行状态
- **CPU变频、睿频** ✅
- **核显加速(Metal H264 HEVC)** ✅
- **无线Wifi** ✅
- **蓝牙Bluetooth** ✅
- **USB定制** ✅
- **双向隔空投送Airdrop** ✅
- **接力Handoff** 
- **板载HDMI** 1080p✅ 4K✅
- **板载DVI** ✅
- **HDMI+DVI双屏** ✅
- **锁定屏幕待机** ✅
- **完美睡眠** ❌

### 注意
- 务必使用`Opencore Configurator`重新生成机型平台序列号