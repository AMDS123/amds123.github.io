---
layout: post
title: "Deep Self-Paced Learning for Person Re-Identification"
date: 2017-10-07 01:32:38
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification Person_Re-identification CNN Optimization
author: Sanping Zhou, Jinjun Wang, Deyu Meng, Xiaomeng Xin, Yubing Li, Yihong Gong, Nanning Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (Re-ID) usually suffers from noisy samples with background clutter and mutual occlusion, which makes it extremely difficult to distinguish different individuals across the disjoint camera views. In this paper, we propose a novel deep self-paced learning (DSPL) algorithm to alleviate this problem, in which we apply a self-paced constraint and symmetric regularization to help the relative distance metric training the deep neural network, so as to learn the stable and discriminative features for person Re-ID. Firstly, we propose a soft polynomial regularizer term which can derive the adaptive weights to samples based on both the training loss and model age. As a result, the high-confidence fidelity samples will be emphasized and the low-confidence noisy samples will be suppressed at early stage of the whole training process. Such a learning regime is naturally implemented under a self-paced learning (SPL) framework, in which samples weights are adaptively updated based on both model age and sample loss using an alternative optimization method. Secondly, we introduce a symmetric regularizer term to revise the asymmetric gradient back-propagation derived by the relative distance metric, so as to simultaneously minimize the intra-class distance and maximize the inter-class distance in each triplet unit. Finally, we build a part-based deep neural network, in which the features of different body parts are first discriminately learned in the lower convolutional layers and then fused in the higher fully connected layers. Experiments on several benchmark datasets have demonstrated the superior performance of our method as compared with the state-of-the-art approaches.

##### Abstract (translated by Google)
人的重新识别（Re-ID）通常会受到背景杂乱和相互遮挡的噪音样本的影响，这使得在不相交的摄像机视图中区分不同的个体是非常困难的。在本文中，我们提出了一种新的深度自适应学习（DSPL）算法来缓解这个问题，其中我们应用了自我调节约束和对称正则化来帮助相对距离度量训练深度神经网络，从而学习人Re-ID的稳定性和判别性特征。首先，我们提出了一个软多项式正则化项，它可以根据训练损失和模型年龄推导出样本的自适应权重。因此，在整个训练过程的早期阶段，将强调高置信度的保真度样本，并降低低置信度噪声样本。这样的学习制度自然是在自主学习（SPL）框架下实施的，其中使用替代优化方法基于模型年龄和样本损失自适应更新样本权重。其次，引入对称正则化项来修正由相对距离度量导出的非对称梯度反向传播，从而同时使类内距离最小，并使每个三元组中的类间距离最大。最后，我们构建了一个基于零件的深度神经网络，其中不同身体部位的特征首先在较低的卷积层中进行区分学习，然后在较高的完全连通层中进行融合。在几个基准数据集上的实验已经证明了我们的方法与最先进的方法相比的优越性能。

##### URL
[https://arxiv.org/abs/1710.05711](https://arxiv.org/abs/1710.05711)

##### PDF
[https://arxiv.org/pdf/1710.05711](https://arxiv.org/pdf/1710.05711)

