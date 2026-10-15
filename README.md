# piper-robotics-learning
Learning notes and practical projects for the AgileX Piper robotic arm, including trajectory recording, playback, and Xbox controller teleoperation.
# Piper Robotics Learning

松灵 Piper 六轴机械臂学习与实践项目，记录机械臂操作、轨迹控制、遥操作及相关技术的学习过程。

本仓库作为个人机械臂项目的总索引，集中整理不同功能模块的实践记录，并链接到各自独立的项目仓库。

## 项目列表

### 1. 连续轨迹录制与播放

**仓库地址：** [piper-trajectory-recording-playback](https://github.com/Charles8279/piper-trajectory-recording-playback)

记录 Piper 机械臂连续运动轨迹的录制与回放实践，重点整理轨迹 CSV 文件的保存、管理与调用方式。

主要内容：
- 连续轨迹录制与播放实践
- 多组轨迹文件的保存与管理
- 指定轨迹文件进行回放
- 实践记录与问题整理

### 2. Xbox 手柄遥操作

**仓库地址：** [piper-gamepad-teleoperation](https://github.com/Charles8279/piper-gamepad-teleoperation)

记录使用 Xbox 手柄遥操作 Piper 机械臂的实践过程，重点关注按键控制、安全操作规范、仿真练习与真机操作。

主要内容：
- Xbox 手柄按键与机械臂动作的对应关系
- 仿真环境下的按键熟悉与操作练习
- 真实机械臂的遥操作实践
- 速度参数设置与仿真、真机一致性检查
- 常见问题与测试记录

**安全注意事项：** 遥操作前必须确认速度设置符合当前设备与程序的安全要求，并核对仿真环境和真实环境的参数。未经确认，不得随意调整速度参数。真机操作前还应确认急停方式可用、工作范围安全。

## 官方参考项目

本系列实践参考松灵机器人官方项目：

- [Agilex-College 官方仓库](https://github.com/agilexrobotics/Agilex-College)

官方仓库提供机械臂相关示例与教程。本项目主要整理个人学习笔记、操作经验和实践总结，具体实现请参考官方项目及相应使用条款。

## 后续计划

- [ ] 整理机械臂基础控制与运动学知识
- [ ] 完善轨迹录制、保存与回放记录
- [ ] 补充 Xbox 手柄按键说明及操作流程
- [ ] 整理仿真环境与真实机械臂的操作差异
- [ ] 持续记录机械臂实践中的问题与解决方法

## 说明

本仓库为个人学习与实践项目索引，非松灵机器人官方项目。各子项目的具体内容、代码来源及使用范围以对应仓库的说明和适用的版权条款为准。
