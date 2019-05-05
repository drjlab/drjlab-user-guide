# 非板载控制丢失保护

[offboard 非板载模式](../mod/offboard.md)是在飞控 (FMU) 以外运行软件，跳过 FMU 来控制飞机的飞行。

在地面站参数设置中找到 COM_OBL_ACT，设置 offboard 控制丢失后的反应：
1. 就地着陆
2. 悬停/盘旋
3. 返航 (RTL)

找到参数 COM_OBL_RC_ACT，设置一种模式，offboard 控制丢失后会自动跳转到该模式，推荐设置为[position 定点模式](../mod/position.md)。

找到参数 COM_OF_LOSS_T，设置等待时间，比如 3 秒钟，如果 offboard 连接断开后 3 秒还没有恢复，则执行着陆、返航等保险措施。

