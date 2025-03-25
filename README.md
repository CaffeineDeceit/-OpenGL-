# 基于OpenGL的交互式角色动画系统

![OpenGL](https://img.shields.io/badge/OpenGL-3.3+-blue) ![GLUT](https://img.shields.io/badge/GLUT-3.7+-orange) ![License](https://img.shields.io/badge/License-MIT-green)

## 项目概述
基于OpenGL/GLUT框架实现的2D角色动画控制系统，通过WASD键盘交互实现多方向运动控制，包含完整的动画状态机和纹理渲染系统。

## 功能特性
- **四向运动控制**：WASD键盘操作
- **帧动画系统**：3帧循环动画（48ms/帧）
- **方向感知**：自动切换左右朝向
- **纹理管理**：支持PNG透明通道
- **跨平台**：Windows/Linux/macOS兼容

## 快速开始
### 环境要求
- C编译器（gcc/clang）
- OpenGL 3.3+
- GLUT库

### 安装依赖
```bash
# Ubuntu
sudo apt install freeglut3-dev
# macOS
brew install freeglut

## 编译运行
gcc main.c -o demo -lglut -lGL -lGLU
./demo

## 素材来源
### 纹理资源
原创作者：Instagram@wushengbengjidashi

- **授权类型**：非独占性商业使用授权

- **授权日期**：2024-12-07

- **使用要求**：二次发布须保留本声明

### 代码授权
MIT License - 可自由修改和分发代码
