# cs231n training camp 

## 课程资料
1. [课程主页](http://cs231n.stanford.edu/)  
2. [英文笔记](http://cs231n.github.io/)  
3. [中文笔记](https://zhuanlan.zhihu.com/p/21930884)  
4. [课程视频](https://www.bilibili.com/video/av17204303/)  
5. [作业链接](https://github.com/sharedeeply/cs231n-assignment)  
6. [环境配置](https://github.com/sharedeeply/DeepLearning-StartKit)  
7. [作业参考](https://github.com/sharedeeply/cs231n-assignment)
8. [AWS 云服务器配置](https://github.com/L1aoXingyu/code-of-learn-deep-learning-with-pytorch/blob/master/aws.md)   
**注: 云服务器并不是强制要求的，而且国外的服务器会比较卡，考虑到阿里云等国内的服务器比较贵，所以推荐大家使用本地的电脑**


#### 🔥🔥一些重要的资源：

1. [廖雪峰python3教程](https://www.liaoxuefeng.com/article/001432619295115c918a094d8954bd493037b03d27bf9a9000)
2. [深度学习的学习路线](https://github.com/L1aoXingyu/Roadmap-of-DL-and-ML/blob/master/README_cn.md)和[开源深度学习课程](http://www.deeplearningweekly.com/blog/open-source-deep-learning-curriculum/)
3. [mxnet/gluon 教程](https://zh.gluon.ai/)
4. [我的知乎专栏](https://zhuanlan.zhihu.com/c_94953554)和[pytorch教程](https://github.com/L1aoXingyu/code-of-learn-deep-learning-with-pytorch)
5. [官方pytorch教程](https://pytorch.org/tutorials/)和一个比较好的[教程](https://github.com/yunjey/pytorch-tutorial)
6. [tensorflow教程](https://github.com/aymericdamien/TensorFlow-Examples)

上面是本次训练营经常需要用到的网页，所以顶置便于大家查询

## 前言
对于算法工程师，不同的人的认知角度都是不同的，我们通过下面三个知乎的高票回答帮助大家了解算法工程师到底需要做什么样的事，工业界需要什么样的能力

[从今年校招来看，机器学习等算法岗位应届生超多，竞争激烈，未来 3-5 年机器学习相关就业会达到饱和吗?](https://www.zhihu.com/question/66406672/answer/317489657)

[秋招的 AI 岗位竞争激烈吗?](https://www.zhihu.com/question/286925266/answer/491117602)

[论算法工程师首先是个工程师之深度学习在排序应用踩坑总结](https://zhuanlan.zhihu.com/p/44315278)

## 学习安排
### Week 1
1. 计算机视觉综述  
**slides:** [lecture01](http://cs231n.stanford.edu/slides/2018/cs231n_2018_lecture01.pdf)
- 观看视频 p1 和 p2 热身，了解计算机视觉概述以及历史背景
- 观看 p3 了解整门课程的大纲

2. 学习数据驱动的方法和 KNN 算法和线性分类器[上]  
**slides:** [lecture02](http://cs231n.stanford.edu/slides/2018/cs231n_2018_lecture02.pdf) 
- 观看视频 p4 p5 和 p6
- 学习 [图像分类笔记上下](https://zhuanlan.zhihu.com/p/20894041?refer=intelligentunit) 和 [线性分类笔记上](https://zhuanlan.zhihu.com/p/20918580?refer=intelligentunit)

**作业:**   
1. [阅读 python 和 numpy 教程](https://zhuanlan.zhihu.com/p/20878530?refer=intelligentunit)和[代码](https://github.com/sharedeeply/cs231n-camp/blob/master/python_tutorial/python_numpy_tutorial.ipynb)写一个矩阵的类，实现矩阵乘法，只能使用 python 的类(class)和列表(list), 代码截图提交
2. 完成assignment1 中的 `knn.ipynb`



### Week2
1. 学习线性分类器[中下], 损失函数和优化器  
   **slides:** [lecture03](http://cs231n.stanford.edu/slides/2018/cs231n_2018_lecture03.pdf)
- 观看视频 p7 和 p8
- 学习[线性分类笔记中下](https://zhuanlan.zhihu.com/p/20945670?refer=intelligentunit) 和[最优化笔记](https://zhuanlan.zhihu.com/p/21360434?refer=intelligentunit)

**作业:**
1. 简述knn和线性分类器的优劣，文字上传

2. 完成assignment1 中 `svm.ipynb` 


### Week3
1. 神经网络初步  
**slides:** [lecture04](http://cs231n.stanford.edu/slides/2018/cs231n_2018_lecture04.pdf)

- 观看视频 p9 和 p10
- 学习[反向传播算法的笔记](https://zhuanlan.zhihu.com/p/21407711?refer=intelligentunit)和反向传播算法的[数学补充](http://cs231n.stanford.edu/handouts/derivatives.pdf)和[例子](http://cs231n.stanford.edu/handouts/linear-backprop.pdf) 
可选项：[反向传播算法的博客](http://colah.github.io/posts/2015-08-Backprop/)

**作业:**  
1. 理解推导反向传播算法，截图打卡

### Week4
1. 完成 assignment1 中 `softmax.ipynb`, `two_layer_net.ipynb` 和 `features.ipynb`
作业量比较大，希望大家坚持完成

### Week5
1. 学习完成第一个 Kaggle 比赛，[rossmann store sales](https://www.kaggle.com/c/cs3244-rossmann-store-sales)

**作业:**
1. 修改模板代码中的网络结构，提交kaggle成绩，截图


### Week5
1. 卷积神经网络
**slides:** [lecture05](http://cs231n.stanford.edu/slides/2018/cs231n_2018_lecture05.pdf)

- 观看视频 p11 和 p12
- 学习[卷积神经网络笔记](https://zhuanlan.zhihu.com/p/22038289?refer=intelligentunit)



