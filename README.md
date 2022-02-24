# 人脸检测
本仓库内代码的功能是，基于 Xilinx 的 PYNQ-Z2 架构，通过BaseOverlay以及OpenCV+Haar实现人脸检测功能。

Step 1 ：将PYNQ启动，而后进入Samba文件共享，在JupyterNotebook中创建新的文件夹；

Step 2 ：将代码拷贝到文件夹中，执行.ipynb文件即可实现；

本次项目的实践需要的设备有：OV5640摄像头以及HDMI显示器，程序基于以上两种器件，后续可以使用Webcam和HDMI_IN。

项目的实现效果较好，在FPGA+ARM异构的优势下，检测实时性较高，但对于侧脸的检测效果不佳。
