# Matrix-DynamicSpot-
功能说明】暗室场景下控制一组射灯阵列，提供聚光照明。可工作在静态模式与动态(跟踪)模式。【简介】摄像头获取需照明对象所在场景范围内图像。Xilinx ZYNQ-7000上移植的Linux运行着视频监控上位机，图像处理后识别出主灯心位置信息Sp，鼠标选定对象后(提供对象在图像中的位置Tp)。借助HDMI将图形界面显示在显示器上。由数据总线将位置信息Sp与Tp发送至ZYNQ中的FPGA设计部分，通过实现的射灯电机协调控制算法，控制外围的电机控制电路，实现将主灯或整个射灯阵列聚光照明目标对象。
