# AI-and-Person-ReID 简介
这个项目主要存放行人再识别相关的AI基础知识以及行人再识别相关的知识对应的视屏，图书，代码等学习资料。   
**这些资料在这个仓库中的存放路径和以下知识结构的层次相同**
# 最新消息
1. 增加了分析错误案例的脚本程序

## AI基础知识
### 机器学习
持续更新中。。。
### 深度学习
随着计算能力的提升以及训练数据集的增大，深度神经网络替代浅层神经网络，深度学习的时代也随之到来。
#### 基础知识
1. 视频：吴恩达的[深度学习](https://www.bilibili.com/video/BV1FT4y1E74V/?is_story_h5=false&p=1&share_from=ugc&share_medium=iphone&share_plat=ios&share_session_id=F591A1C5-5F72-4145-969E-5EFBA14B4F83&share_source=WEIXIN&share_tag=s_i&timestamp=1665238192&unique_k=Z9oCPZP)课程及其[课后作业](https://github.com/Kulbear/deep-learning-coursera). 这门课程非常适合初级选手，吴老师讲的通俗易懂，课后作业可以结合具体的AI任务让你自己动手实现一些神经网络。
2. 图书：[Deep Learning](https://github.com/janishar/mit-deep-learning-book-pdf). 这本书可以配合吴老师的视屏课看，也可以当作工具书。
#### 经典模型
1. ResNet
2. Transformer（及其相关的自监督学习）
#### 常用的Loss Function
1. Cross-Entropy Loss （分类任务）
2. Triplet Loss （度量学习）
3. Focal Loss (解决类别不平衡)
#### Trick
建议读这些Trick对应的论文了解这些方法提出的动机能够帮助你更好的理解它们，这些论文一般通俗易懂。不建议看博客的总结！！！
1. Bacth Normalization
2. Layer Normalization

#### 优化器
1. SGD
2. Adam系列

## 行人再识别
### 计算机视觉基础
国科大研究生计算机视觉课PPT
### 基于图片的行人再识别
行人再识别为跨摄像头的目标行人关联。行人再识别本质是检索问题，围绕表示和检索进行了一系列研究。
#### 表示
在实际的场景中ReID的表示学习会遇到以下几个问题：
##### 换装
##### 遮挡
##### 朝向变化
##### 光照变化
##### 背景杂乱
##### 姿态变化
##### 域泛化
#### 检索：重排序
重排序在初次检索结果的基础上，完善查询图对检索结果Top-K的进行二次检索。完善查询图时主要利用查询图片的近邻图片增强查询图。重排序模型一般分为使用深度学习模型和机器学习模型两种方法。
### 基于视屏的行人再识别

持续更新
