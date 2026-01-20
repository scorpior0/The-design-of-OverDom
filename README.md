OverDom —— 🦂bot
=

适用于游戏《[screeps](https://screeps.com/)》的全自动 ai。

注意：  
Notes:  

本项目尚未完成，后续可能会进行大范围的代码更改。  
This project is under developing. Large rework is in progress.  

本项目仅分享全局设计方案以及部分代码模块，无法直接运行。  
The purpose of this project is sharing my design pattern (in Chinese) and partial codes, which cannot run.

简介 Introduction
-
本项目采用【收集需求→统一解算】思路构建，creep 出生、物流调度、工作分配都分别收集所有需求后采用综合性能最佳的算法求解，避免固定角色和盲目分配。所有行动统一视为 Task（任务），采用【任务链+定时事件】作为全局统一的执行机制。

**OverDom** is a fully automated Task-Driven AI of [screeps](https://screeps.com/).   


教程 Guide
-
[目录](https://zhuanlan.zhihu.com/p/104412058) (知乎)


交互 Interactivation
-

设计 Design Pattern
-

代码 Scripts Sample
-