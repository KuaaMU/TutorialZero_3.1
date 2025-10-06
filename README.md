# TutorialZero_3.1

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![Language](https://img.shields.io/badge/language-C%2B%2B-orange.svg)

基于EasyX图形库和C++开发的《提瓦特幸存者》游戏，参考学习B站UP主[Voidmatrix](https://space.bilibili.com/25864506)的教程制作。

## 项目介绍

这是一款2D动作游戏，玩家控制角色在提瓦特大陆上生存，躲避敌人的攻击。游戏包含角色移动、动画播放、敌人AI等基本游戏功能。

## 功能特性

- 角色控制（方向键移动）
- 角色动画播放（左右方向）
- 敌人生成系统
- 敌人追踪AI
- 碰撞检测（待完善）
- 帧率控制（144Hz）

## 开发环境

- Windows操作系统
- Visual Studio
- EasyX图形库
- C++语言

## 项目结构

```
TutorialZero_3.1/
├── README.md
├── 源.cpp              # 主程序文件
└── img/               # 游戏资源图片目录
    ├── background.png
    ├── shadow_player.png
    ├── shadow_enemy.png
    ├── player动画帧图片
    └── enemy动画帧图片
```

## 核心类说明

- `Player`：玩家角色类，处理玩家输入、移动和渲染
- `Enemy`：敌人角色类，实现敌人AI和移动逻辑
- `Animation`：动画播放类，管理精灵帧动画
- `Bullet`：子弹类（预留功能）

## 学习说明

本项目为初学者学习游戏开发的练习项目，通过实践掌握：
- C++面向对象编程
- 游戏循环机制
- 图形渲染基础
- 简单游戏AI实现
- 动画系统设计

## 许可证

本项目仅供学习交流使用。