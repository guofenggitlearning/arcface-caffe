# arcface-caffe

1、在caffe中实现arcface中的损失函数，参考cosinface的实现。

2、其它层的实现请参考：https://github.com/xialuxi/AMSoftmax

3、原理请参考：https://github.com/xialuxi/insightface

4、增加Combined Margin Loss 参考insightface的实现

5、增加mtcnn人脸检测python代码，根据c++代码改写，效果没有任何损失，模型与原始代码请参考：https://github.com/blankWorld/MTCNN-Accelerate-Onet

6、实际训练的时候，caffe的收敛速度慢而且困难，而mxnet的速度则比较快，具体原因还不清楚。

7、增加 insightface的gpu实现代码


