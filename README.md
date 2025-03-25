# 基于 OpenGL 的交互式角色动画系统

![OpenGL](https://img.shields.io/badge/OpenGL-3.3+-blue) ![GLUT](https://img.shields.io/badge/GLUT-3.7+-orange) ![License](https://img.shields.io/badge/License-MIT-green)

## 项目概述
基于 OpenGL/GLUT 框架实现的 2D 角色动画控制系统，通过 WASD 键盘交互实现多方向运动控制，包含完整的动画状态机和纹理渲染系统。

## 功能特性
- **四向运动控制**：WASD 键盘操作
- **帧动画系统**：3 帧循环动画（48ms/帧）
- **方向感知**：自动切换左右朝向
- **纹理管理**：支持 PNG 透明通道
- **跨平台**：Windows/Linux/macOS 兼容

## 快速开始
### 环境要求
- C 编译器（gcc/clang）
- OpenGL 3.3+
- GLUT 库

### 安装依赖
```bash
# Ubuntu
sudo apt install freeglut3-dev

# macOS
brew install freeglut
```

### 编译运行
```bash
gcc main.c -o demo -lglut -lGL -lGLU
./demo
```

## 素材来源
### 纹理资源
- **原创作者**：Instagram @wushengbengjidashi
- **授权类型**：非独占性商业使用授权
- **授权日期**：2024-12-07
- **使用要求**：二次发布须保留本声明

### 代码授权
MIT License - 可自由修改和分发代码

---

# Interactive Character Animation System Based on OpenGL

![OpenGL](https://img.shields.io/badge/OpenGL-3.3+-blue) ![GLUT](https://img.shields.io/badge/GLUT-3.7+-orange) ![License](https://img.shields.io/badge/License-MIT-green)

## Project Overview
A 2D character animation control system based on the OpenGL/GLUT framework. It supports multi-directional movement using WASD keyboard interactions and features a complete animation state machine and texture rendering system.

## Features
- **Four-direction movement control**: WASD keyboard operation
- **Frame animation system**: 3-frame loop animation (48ms/frame)
- **Directional awareness**: Automatically switches left and right orientations
- **Texture management**: Supports PNG transparency
- **Cross-platform compatibility**: Works on Windows, Linux, and macOS

## Quick Start
### Requirements
- C compiler (gcc/clang)
- OpenGL 3.3+
- GLUT library

### Install Dependencies
```bash
# Ubuntu
sudo apt install freeglut3-dev

# macOS
brew install freeglut
```

### Compile and Run
```bash
gcc main.c -o demo -lglut -lGL -lGLU
./demo
```

## Assets
### Texture Resources
- **Original Author**: Instagram @wushengbengjidashi
- **License Type**: Non-exclusive commercial use license
- **License Date**: 2024-12-07
- **Usage Requirements**: Redistribution must retain this statement

### Code License
MIT License - Free to modify and distribute


