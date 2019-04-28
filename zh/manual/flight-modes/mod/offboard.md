# offboard非板载模式

offboard 模式的思想是在飞控 (FMU) 以外运行软件，跳过 FMU 来控制飞机的飞行。

此模式存在一定危险性，开发者在使用此模式之前，必须确保充分的准备工作、测试以及[安全防护措施](../safety/offboard_loss_safety.md)。

offboard 模式需要通过 Mavlink 通信协议来实现。

## 固件设置

### 1.设置触发

可以用地面站将模式触发映射到遥控器的开关上。建议的设置方法是，当退出 offboard 模式后立即切换为[定点模式](position.md)。

也可以通过地面站发送 MAVLink 消息来触发该模式。

### 2.使能伙伴计算机

查找参数 SYS_COMPANION，将参数设置为 921600 或 57600 ，以合适的波特率激活 MAVLink 数据流。

## 硬件设置

要搭建 offboard 通信有三种方法：

### 1.电台

一个电台连接地面站计算机，一个电台连接飞控的 UART 接口。

![offboard_1](../mod/offboard_1.png)

### 2.机载处理器

载具上搭载的小型计算机通过 UART/USB 适配器来连接到飞控。根据需求不同也可以采用多种不同的方法。

![offboard_2](../mod/offboard_2.png)



### 3.wifi 和机载处理器

载具上搭载的小型计算机通过 UART/USB 适配器来连接到飞控。另外，运行 ROS(Robot Operating System) 的地面站通过 wifi 与机载计算机通信。

![offboard_3](../mod/offboard_3.png)





