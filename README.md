## yolov4_v5_learning_note
### the difference of v4 and v5
1、v5支持自适应瞄定框

#### yolo三个模块
#### Backbone
V5和V4都使用CSPDarknet作为Backbone，从输入图像中提取丰富的信息特征（CSPNet全称是Cross Stage Partial Networks，也就是跨阶段局部网络）

#### Neck-路径聚合网络(PANET)
