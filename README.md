# 计算机图形学-课程设计  
选题：Identification of dental models  
### 1. 开发环境VS 2017 + Vtk 8.2.0 + Qt 5.13.2:   
环境配置参考 https://blog.csdn.net/wilsonass/article/details/89192007  
（1）安装Visual Studio 2017  
（2）安装Qt 5.13.2，VS中安装Qt扩展插件  
（3）安装Cmake  
（4）编译安装Vtk，用Cmake选择路径，Configue和Generate，用VS打开之后再重新生成
### 2. code: 
（1）CMakeLists.txt, build编译安装  
（2）main.cpp是对Qt界面类Widget的实例化  
（3）Widget.ui是用Qt图形化界面编程的生成文件，并且自动生成ui_widget.h头文件  
（4）Widget.h中设置相应的8个按钮的button slot函数  
（5）Widget.cpp中是具体实现，包括牙齿模型/去除牙龈/连通分量提取/包围盒/FDI牙位标记法/牙齿缺失情况/牙齿数量/轴向8个按钮  
（6）tooth.h是用于牙齿编号和缺失识别的牙齿类相关头文件
### 3. pre.pptx, demo.avi, report.pdf

