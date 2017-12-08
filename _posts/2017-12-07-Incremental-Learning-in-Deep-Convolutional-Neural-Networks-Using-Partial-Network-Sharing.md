---
layout: post
title: "Incremental Learning in Deep Convolutional Neural Networks Using Partial Network Sharing"
date: 2017-12-07 17:05:54
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Transfer_Learning Classification Recognition
author: Syed Shakib Sarwar, Aayush Ankit, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural network (DCNN) based supervised learning is a widely practiced approach for large-scale image classification. However, retraining these large networks to accommodate new, previously unseen data demands high computational time and energy requirements. Also, previously seen training samples may not be available at the time of retraining. We propose an efficient training methodology and incrementally growing a DCNN to allow new classes to be learned while sharing part of the base network. Our proposed methodology is inspired by transfer learning techniques, although it does not forget previously learned classes. An updated network for learning new set of classes is formed using previously learned convolutional layers (shared from initial part of base network) with addition of few newly added convolutional kernels included in the later layers of the network. We evaluated the proposed scheme on several recognition applications. The classification accuracy achieved by our approach is comparable to the regular incremental learning approach (where networks are updated with new training samples only, without any network sharing).

##### Abstract (translated by Google)
基于深度卷积神经网络（DCNN）的监督学习是一种广泛应用于大规模图像分类的方法。然而，再培训这些大型网络以适应新的，以前看不见的数据需要很高的计算时间和能量需求。另外，以前看过的训练样本在再训练时可能不可用。我们提出了一个有效的培训方法，并逐步增加一个DCNN，以便在分享部分基础网络的同时学习新的类别。我们提出的方法学是受转移学习技术的启发，尽管它不会忘记以前学过的类。使用先前学习的卷积层（从基础网络的初始部分共享）形成用于学习新的一组类的更新的网络，并在网络的后续层中添加少量新添加的卷积核。我们评估提出的方案在几个识别应用程序。我们的方法所达到的分类精确度与常规的增量学习方法（其中网络仅用新的训练样本更新而没有任何网络共享）相当。

##### URL
[http://arxiv.org/abs/1712.02719](http://arxiv.org/abs/1712.02719)

##### PDF
[http://arxiv.org/pdf/1712.02719](http://arxiv.org/pdf/1712.02719)

