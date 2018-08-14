---
layout: post
title: "A Light CNN for Deep Face Representation with Noisy Labels"
date: 2018-08-12 02:35:58
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN Prediction Relation Recognition Face_Recognition
author: Xiang Wu, Ran He, Zhenan Sun, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
The volume of convolutional neural network (CNN) models proposed for face recognition has been continuously growing larger to better fit large amount of training data. When training data are obtained from internet, the labels are likely to be ambiguous and inaccurate. This paper presents a Light CNN framework to learn a compact embedding on the large-scale face data with massive noisy labels. First, we introduce a variation of maxout activation, called Max-Feature-Map (MFM), into each convolutional layer of CNN. Different from maxout activation that uses many feature maps to linearly approximate an arbitrary convex activation function, MFM does so via a competitive relationship. MFM can not only separate noisy and informative signals but also play the role of feature selection between two feature maps. Second, three networks are carefully designed to obtain better performance meanwhile reducing the number of parameters and computational costs. Lastly, a semantic bootstrapping method is proposed to make the prediction of the networks more consistent with noisy labels. Experimental results show that the proposed framework can utilize large-scale noisy data to learn a Light model that is efficient in computational costs and storage spaces. The learned single network with a 256-D representation achieves state-of-the-art results on various face benchmarks without fine-tuning. The code is released on https://github.com/AlfredXiangWu/LightCNN.

##### Abstract (translated by Google)
为人脸识别提出的卷积神经网络（CNN）模型的体积不断增大，以更好地适应大量的训练数据。当从互联网获得培训数据时，标签可能不明确且不准确。本文介绍了一种Light CNN框架，用于学习具有大量噪声标签的大规模人脸数据的紧凑嵌入。首先，我们将最大激活的变化（称为最大特征映射（MFM））引入CNN的每个卷积层。与使用许多特征映射线性逼近任意凸激活函数的maxout激活不同，MFM通过竞争关系来实现。 MFM不仅可以分离噪声和信息信号，还可以在两个特征映射之间起到特征选择的作用。其次，三个网络经过精心设计，以获得更好的性能，同时减少参数和计算成本。最后，提出了一种语义自举方法，使网络预测与噪声标签更加一致。实验结果表明，所提出的框架可以利用大规模噪声数据来学习有效计算成本和存储空间的Light模型。具有256-D表示的学习单网络在各种面部基准测试中实现了最先进的结果，而无需进行微调。该代码发布于https://github.com/AlfredXiangWu/LightCNN。

##### URL
[http://arxiv.org/abs/1511.02683](http://arxiv.org/abs/1511.02683)

##### PDF
[http://arxiv.org/pdf/1511.02683](http://arxiv.org/pdf/1511.02683)

