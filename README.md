# DrjLab文档中心
该仓库包含了 [DrjLab.com](http://www.drjlab.com) 相关产品的[帮助文档](http://help.drjlab.com)。本文档基于[Gitbook](https://gitbook.com)进行维护，网页托管到[Github Pages](http://help.drjlab.com)上。您可以通过：

 - 下面链接[help.drjlab.com](http://help.drjlab.com)阅读帮助文档
 - 也可以将仓库代码克隆到本地进行编译

## 关于我们
[DrjLab](https://www.drjlab.com)是无人机飞控系统及应用解决方案提供商。团队成立于2017年3月，我们的目标是把PX4做出DJI的感觉。

- [DrjLab NextPilot 全新高性能**飞控系统**](http://help.drjlab.com/zh)

> NextPilot是基于PX4FMU V5，我们的目标是**把PX4做出DJI的感觉**。NextPilot可集成厘米级精度的RTK模块、智能电调和高清图传。开发者可使用DroneCode定制专属应用，实时获取飞行器状态信息，并且控制飞行器、 云台和相机。NextPilot配备CAN、API等丰富的硬件接口，可连接第三方传感器或其他设备， 让你针对各种行业应用对飞行平台进行灵活定制。

- [DrjLab Lightning **数图传一体**通讯模块](http://help.drjlab.com/zh)

> Lightning将**遥控、数传、图传等三链合一**的无人机通信模块，整套系统由**天空端**和**地面端**组成，其中地面端集成了**遥控器**。Lightning采用先进的无线链路动态适应技术，以空前强大的功能和可靠性树立了无线影像传输的全新标准，无论用于FPV飞行还是电视直播，都能得心应手，让你获得亲临现场的体验。

## 本地编辑
```
# 安装gitbook
npm install -g gitbook-cli
# 下载本文档
git clone https://github.com/drjlab/drjlab-user-guide --recursive
# 编译文档
cd drjlab-user-guide
gitbook instll # 安装gitbook插件
gitbook build  # 或者gitbook serve
```
