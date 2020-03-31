# LTE LINK显示屏提示信息

> **NOTE** LTE-LINK SE提示信息大致与LTE-LINK相同，将不再进行单独介绍。

## 主界面

![binding](../assets/feigong/display-information.png)

**1.云连接状态**
 
表示设备是否正常连接到云服务器(该图如带有"\"则为连接断开）。连接云服务器是保证终端与客户端通信正常的前提。

**2.视频传输状态**

显示/隐藏表示当前启动/关闭视频传输

**3.信号状态**

网络信号的强度，网络模式

**4.SD卡状态**

SD卡插入/拔出状态

**5.视频输入**

HDMI输入的视频流正常/关闭状态

**6.设备信息提示**

 设备所有的信息状态提示。
 * “Devinit”-设备初始化。 
 * “simpppdcall”-正在进行SIM卡上网拨号。 
 * “pppfailed”-拨号失败，可以等待一会重新拨号。如果持续失败，需要查看手机卡是不是欠费 或流量不足。 
 * “Waittimesync”-等待时间同步。 
 * “connectingserver”-连接服务器。 
 * “Waitappconnect”-网络通讯正常，客户端可以连接了。
 * “checkedupdate”-检测更新文件。 
 ...... 
 
**7.数据连接状态**
 
 UART输入的无人机数据正常/关闭状态（需为MAVlink1/2数据）。