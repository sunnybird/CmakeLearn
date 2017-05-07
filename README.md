# CmakeLearn
## 背景
由于 AndroidStudio 2.3 版本的 NDK 编程默认使用的 CMake 工具，作为勤奋好学的 Android 猿必须紧跟大佬的脚步啦。

## Cmake 介绍
Cmake 主要作用是根据 CMakeList.txt(跨平台通用) 生成不同操作系统平台(**nix/win) 的 Makefile 和工程文件，简化项目编译配置流程。

## Cmake 使用介绍
1. CMake [官网](https://cmake.org/) 安装 Cmake 工具
2. 项目根目录创建 CMakeLists.txt 文件
3. 执行 cmake . (后面的点表示 CMakeLists.txt 文件路径)
4. 执行 make 进行编译


## Cmake 常用实例练习
---
1. 单源码源码 [连接](./demo1/)
2. 多源码单一目录 [连接](./demo2/)
3. 多源码多目录 [连接](./demo3/)
4. 可选择配置编译 [连接](./demo4/)

---
参考资料: [CMake 入门实战](http://hahack.com/codes/cmake/)
