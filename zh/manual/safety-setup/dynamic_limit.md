# 动力学限制

可在地面站参数设置中设定以下参数，对飞机的角速度、水平速度等进行限制。

角运动限制

1. MC_ACRO_P_MAX，特技模式下最大俯仰角速率
2. MC_ACRO_R_MAX，特技模式下最大滚转角速率
3. MC_ACRO_Y_MAX，特技模式下最大偏航角速率
4. MC_PITCHRATE_MAX，最大俯仰角速率
5. MC_ROLLRATE_MAX，最大滚转角速率
6. MC_YAWRATE_MAX，最大偏航角速率
7. MC_YAWRAUTO_MAX，自动模式下（例如任务模式）最大偏航角速率
8. MPC_MAN_TILT_MAX，手动模式或姿态增稳模式下，最大的机体倾斜角
9. MPC_MAN_Y_MAX，手动模式下最大偏航角速率
10. MPC_TILTMAX_AIR，飞行中最大的机体倾斜角
11. MPC_TILTMAX_LND，着陆阶段最大的机体倾斜角


线运动限制

1. MPC_ACC_DOWN_MAX，垂直方向，向下的最大加速度
2. MPC_ACC_UP_MAX，垂直方向，向上的最大加速度
3. MPC_Z_VEL_MAX_DN，垂直方向，向下的最大速度
4. MPC_Z_VEL_MAX_UP，垂直方向，向上的最大速度
5. MPC_ACC_HOR_MAX，自动模式下的最大水平加速度，以及，手动模式下减速过程的最大加速度
6. MPC_JERK_MAX，手动模式下，刹车的最大加加速度（加速度的微分）
7. MPC_VEL_MANUAL，手动模式下，水平方向的最大速度
8. MPC_XY_CRUISE，任务模式下，水平方向的最大速度
9. MPC_XY_VEL_MAX，水平方向的最大速度




