# 前言：

+ 本次利用Tensorflow-Keras实现YOLO-V3模型，目的是自己动手实现YOLO-V3的重要结构，这样才能更为深入了解模型以及提升编程能力；略去了不太重要的结构，如tiny版本就没有继续实现。
+ 重点研究了模型结构，在[levio](https://blog.csdn.net/leviopku/article/details/82660381)作图的基础上增加了各层的参数设置，以图将模型展示的更加清晰明了；
+ 实现了较为细节也很重要的非最大值抑制、loss函数、如何生成true label等；
+ 另外做了些测试：图像目标检测、视频实时目标检测测试。
+ 详细代码步骤见：https://github.com/Teslaxhub/YOLO_V3_Tensorflow_Keras_from_scratch   含测试样例。
+ 转图请留言并注明出处，谢谢。

个人博客：https://blog.csdn.net/aaa_aaa1sdf/article/details/94484328
Github:https://github.com/Teslaxhub/YOLO_V3_Tensorflow_Keras_from_scratch

<img src="readme_pic/YOLO_V3_Structure.png" style="width:1000px;height:100;">