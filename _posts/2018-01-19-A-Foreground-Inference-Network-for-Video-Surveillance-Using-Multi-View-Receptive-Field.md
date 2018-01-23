---
layout: post
title: "A Foreground Inference Network for Video Surveillance Using Multi-View Receptive Field"
date: 2018-01-19 23:01:16
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Transfer_Learning Inference Classification Deep_Learning
author: Thangarajah Akilan
mathjax: true
---

* content
{:toc}

##### Abstract
Foreground (FG) pixel labelling plays a vital role in video surveillance. Recent engineering solutions have attempted to exploit the efficacy of deep learning (DL) models initially targeted for image classification to deal with FG pixel labelling. One major drawback of such strategy is the lacking delineation of visual objects when training samples are limited. To grapple with this issue, we introduce a multi-view receptive field fully convolutional neural network (MV-FCN) that harness recent seminal ideas, such as, fully convolutional structure, inception modules, and residual networking. Therefrom, we implement a system in an encoder-decoder fashion that subsumes a core and two complementary feature flow paths. The model exploits inception modules at early and late stages with three different sizes of receptive fields to capture invariance at various scales. The features learned in the encoding phase are fused with appropriate feature maps in the decoding phase through residual connections for achieving enhanced spatial representation. These multi-view receptive fields and residual feature connections are expected to yield highly generalized features for an accurate pixel-wise FG region identification. It is, then, trained with database specific exemplary segmentations to predict desired FG objects. The comparative experimental results on eleven benchmark datasets validate that the proposed model achieves very competitive performance with the prior- and state-of-the-art algorithms. We also report that how well a transfer learning approach can be useful to enhance the performance of our proposed MV-FCN.

##### Abstract (translated by Google)
前景（FG）像素标记在视频监视中起着至关重要的作用。最近的工程解决方案试图利用最初针对图像分类的深度学习（DL）模型的功效来处理FG像素标记。这种策略的一个主要缺点是当训练样本有限时，对视觉对象的缺乏描述。为了解决这个问题，我们引入了一个多视图感知域完全卷积神经网络（MV-FCN），它利用了最近的开创性思想，如完全卷积结构，初始模块和残差网络。因此，我们以编码器 - 解码器的方式实现一个系统，其中包含一个核心和两个互补的特征流路径。该模型利用三个不同大小的感受野的早期和晚期的初始模块来捕捉不同尺度的不变性。编码阶段学习到的特征通过残差连接与解码阶段的适当特征映射相融合，实现增强的空间表示。预期这些多视图接受区域和残余特征连接将产生用于精确像素化FG区域识别的高度概括的特征。然后，用数据库特定的示例性分段来训练，以预测所需的FG对象。在11个基准数据集上的比较实验结果验证了所提出的模型与先前和现有技术的算法实现了非常有竞争力的性能。我们还报告说，转让学习方法对提高我们提出的MV-FCN的性能有多大用处。

##### URL
[https://arxiv.org/abs/1801.06593](https://arxiv.org/abs/1801.06593)

##### PDF
[https://arxiv.org/pdf/1801.06593](https://arxiv.org/pdf/1801.06593)

