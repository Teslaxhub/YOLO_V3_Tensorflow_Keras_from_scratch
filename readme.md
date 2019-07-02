# 前言：

本次利用Tensorflow-Keras实现YOLO-V3模型，目的是自己动手实现YOLO-V3的重要结构，这样才能更为深入了解模型以及提升编程能力；略去了不太重要的结构，如tiny版本就没有继续实现。

重点研究了模型结构，以及细节性但较为重要的非最大值抑制、loss函数、如何生成true label等；

另外做了些测试：图像目标检测、视频实时目标检测测试。

<img src="readme_pic/YOLO_V3_Structure.png" style="width:1000px;height:100;">