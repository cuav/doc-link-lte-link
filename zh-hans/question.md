# 常见问题
---------
**1.服务器是在哪？** 

目前服务器只部署在国内，国外尚未部署服务器。

**2.支持的4G运营商？** 

支持中国移动、电信、联通三大运营商。香港、台湾、澳门的运营商大部分都支持。至于国外使用， 需要确认当地的4G/3G/2G运营商的频段与规格参数表里面的网络频率对应上才可以正常使用。 
 
**3.港澳台以及国外可以使用吗？**

 答：港澳台可以正常使用；国外暂不建议使用（可能存在频段兼容或法律许可问题）。
 
**4.支持的飞控？**

支持所有Mavlink1/2协议的飞控，如V5+、V5nano、Pixhack、Pixhawk等。注意飞控间的数 据口线序。不支持自定义协议的飞控数据。 
  
**5.关于延时？**

关于LTE LINK/LTE LINK SE视频延时约为250ms（网络理想环境下）,实时飞控数据延时40ms-60ms。具体由网络而定。关于AIR LINK实时飞行数据延时约为40ms.

**5.4G网络的通信高度？ **

具体4G网络通讯最大高度根据当地的基站覆盖范围而决定。在我们所在的测试地点，LTE设备在 0-1000米可以数据通讯，建议在500m（离地高度）以下高度使用。

**6.客户端获取不到飞控数据？**

 * 电脑防火墙可能进行了网络通信的拦截，需要查看网络防火墙。或使用了VPN服务，需要关闭。 
 * 检查云端与设备连接：查看LTE LINK/LTE LINK显示屏云端连接状态显示/AIR LINK云端状态灯状态。

**7.LTE LINK SE/LTE LINK显示屏显示的信息是什么意思？**

[显示屏信息详解](quick-start-lte-link.md#显示屏提示信息详解)

**8.状态灯是什么意思？**

[状态灯详解](quick-start-air-link.md#状态指示灯详解)

**9.支持多台无人机操作？** 

答：非攻地面站基于QGroundControl地面站，目前无法进行实时的多机操作。仅仅实现切换式的多机操作。如果要达到实时多机操作效果，可以使用非攻透传，然后自行选择支持实时多机的地 面站软件进行操作。

**9.支持5G网络？** 

LTE LINK支持网络扩展，可以通过扩展5G网卡的形式支持5G。
LTE LINK SE和AIR LINK暂不支持5G。