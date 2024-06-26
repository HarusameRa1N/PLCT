# **荔枝派烹饪手册（误）**

## **介绍**

> **Lichee RV Dock** 是为开源开发者而设计的一款*功能集成度高*、*体积小*且*价格亲民*的 RISC-V Linux 开发板套件。

> 它不仅支持 HDMI 输出，搭配屏幕转接板更可以支持多种的屏幕显示（MIPI、RGB 和 MCU 接口）。

> 它同时具备丰富的外设，包括一个主机 USB-A 接口，2.4G Wi-Fi+BT 模块，一个模拟麦克风和扬声器插口等。

> 使用者拿到套件之后，*无需等待和焊接*，即可用套件连接显示器和 USB 设备快速上手开发各种有趣且实用的 Linux 应用，较大地加速了开发者的试研和开发工作。

> 除此之外，用户还可以利用开发板的多种显示接口，无线功能和 GPIO ，搭配板载麦克风和扬声器，快速实现各种创意。

*注：以上内容选自 [SipeedWiki](https://en.wiki.sipeed.com/hardware/zh/lichee/RV/flash.html)*


## 本文主要是面向那些对于 RISC-V 开发板感兴趣的入门玩家

一定能学会的系统烧录及启动指南，有不会的地方可以私信我 yubohui007@outlook.com

废话不多说，往下读吧！

首先，需要准备以下几样东西：

* 一块新鲜的 *LicheeRV开发板*
* 一片美味可口的 *TF内存卡*
* 用于烹饪的烧录工具（如 *balenaEtcher*）
* 系统镜像（本文使用 *SipeedWiki* 提供的 [debian镜像](https://mega.nz/folder/lx4CyZBA#PiFhY7oSVQ3gp2ZZ_AnwYA)）
* 咖啡 零食 （等待过程中使用）
* *难以磨灭的斗志与不断向前的勇气*
* *让荣光落于刀锋之上！*

准备好以上几样东西后，就可以开始愉快的烹饪啦<@~@/

1. 用工具（如 *SD card Formatter*） 对内存卡进行格式化
2. 用读卡器将内存卡插入电脑（疑似是和上一条顺序反了）
3. 使用你的烧录工具将系统镜像烧录入内存卡
4. 烧录可能会有些久，掏出你的咖啡和零食开始享用啦
5. 烧录完成后小心翼翼拔出内存卡（弄断就见鬼啦
6. 别忘记把内存卡塞进开发板里喔
7. 连接开发板至显示设备（不然的话显示器是没有画面的啦

*注：登录用户名 `root` 密码 `licheepi`*

# 之后就可以开始愉快的游玩啦！

### 部分内容参考自 *SipeedWiki* 

### 作者：zMyANIA

