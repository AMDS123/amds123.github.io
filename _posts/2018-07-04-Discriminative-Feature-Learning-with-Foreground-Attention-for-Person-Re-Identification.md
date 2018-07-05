---
layout: post
title: "Discriminative Feature Learning with Foreground Attention for Person Re-Identification"
date: 2018-07-04 06:18:17
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification
author: Sanping Zhou, Jinjun Wang, Deyu Meng, Yudong Liang, Yihong Gong, Nanning Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of person re-identification (Re-ID) seriously depends on the camera environment, where the large cross-view appearance variations caused by mutual occlusions and background clutters have severely decreased the identification accuracy. Therefore, it is very essential to learn a feature representation that can adaptively emphasize the foreground of each input image. In this paper, we propose a simple yet effective deep neural network to solve the person Re-ID problem, which attempts to learn a discriminative feature representation by addressing the foreground of input images. Specifically, a novel foreground attentive neural network (FANN) is first built to strengthen the positive influence of foreground while weaken the side effect of background, in which an encoder and decoder subnetwork is carefully designed to drive the whole neural network to put its attention on the foreground of input images. Then, a novel symmetric triplet loss function is designed to enhance the feature learning capability by jointly minimizing the intra-class distance and maximizing the inter-class distance in each triplet unit. Training the deep neural network in an end-to-end fashion, a discriminative feature representation can be finally learned to find out the matched reference to the probe among various candidates in the gallery. Comprehensive experiments on several public benchmark datasets are conducted to evaluate the performance, which have shown clear improvements of our method as compared with the state-of-the-art approaches.

##### Abstract (translated by Google)
人员重新识别（Re-ID）的性能严重依赖于相机环境，其中由相互遮挡和背景杂乱引起的大的交叉视图外观变化严重降低了识别准确性。因此，学习能够自适应地强调每个输入图像的前景的特征表示是非常必要的。在本文中，我们提出了一个简单而有效的深度神经网络来解决人Re-ID问题，该问题试图通过解决输入图像的前景来学习判别特征表示。具体来说，首先建立一个新颖的前景细胞神经网络（FANN），以加强前景的积极影响，同时削弱背景的副作用，其中编码器和解码器子网被精心设计，以驱动整个神经网络引起注意输入图像的前景。然后，设计一种新颖的对称三重态损失函数，通过联合最小化类内距离并最大化每个三元组中的类间距离来增强特征学习能力。以端到端的方式训练深度神经网络，可以最终学习辨别特征表示，以找出画廊中各种候选者之间对探针的匹配参考。对几个公共基准数据集进行了全面的实验，以评估性能，与最先进的方法相比，我们的方法有了明显的改进。

##### URL
[http://arxiv.org/abs/1807.01455](http://arxiv.org/abs/1807.01455)

##### PDF
[http://arxiv.org/pdf/1807.01455](http://arxiv.org/pdf/1807.01455)

