# Clion环境配置（用于学习C语言）

## 🎯 目标达成概览
- ✅ Clion下载
- ✅ Clion基础环境配置  
- ✅ Clion与github建立远程仓库
- ✅ 记录Clion环境配置笔记

## 📅 时间线记录
**总耗时**：1天（2025.10.13）
**关键里程碑**：从零开始建立完整的C语言学习环镜

---

## 🔧 详细步骤记录

### 阶段一：开发环境搭建

#### 1. Android Studio 安装    
**日期**：2025-9-25
**目标**：安装Android studio并配置好所需的JDK
**步骤**：
- 在CSDN博客上搜索“如何安装Android studio”[感谢该博主的贡献](https://blog.csdn.net/2301_80035882/article/details/142249097?spm=1001.2014.3001.5506)
- 依据博客内容提前在D盘中做好文件夹分类
- 下载最新版JDK[下载网址](https://www.oracle.com/)
- 在电脑属性中的path（路径）添加下载JDK文件路径（新建命名JAVA-HOME）
- 在命令指示符中确认是否下载好JDK
- 下载 Android Studio 最新[下载网址](https://developer.android.google.cn/studio?hl=en)
- 点开下好的exe安装包,按步骤点击选项,切换下载路径,最终"Finish"完成下载
- 配置 Android Automotive OS SDK
- 创建 Automotive 模拟器（1408p landscape）
- 验证开发环境正常运行

**遇到的问题与解决与最终结果**：
- 安装android studio必须要先安装JDK吗?→ 询问deep seek→ 是的,因为android studio核心逻辑是用Java/Kotlin语言来编写的,而JDK是Java语言的软件开发工具包,包含了编译代码所必需的工具（比如javac编译器）和运行这些程序所依赖的库（Java运行时环境）,没有它android studio就无法将代码转化为可在设备上运行的程序
- 性能优化：调整模拟器内存配置（不占用C盘内存）

