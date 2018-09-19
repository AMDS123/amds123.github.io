---
layout: post
title: "Incremental Learning in Deep Convolutional Neural Networks Using Partial Network Sharing"
date: 2018-09-17 18:10:52
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
基于深度卷积神经网络（DCNN）的监督学习是用于大规模图像分类的广泛实践的方法。然而，重新训练这些大型网络以适应新的，先前未见过的数据需要高计算时间和能量需求。此外，在再培训时可能无法获得先前看到的训练样本。我们提出了一种有效的培训方法，并逐步增加DCNN，以便在共享部分基础网络的同时学习新课程。我们提出的方法受到转移学习技术的启发，尽管它不会忘记以前学过的课程。使用先前学习的卷积层（从基础网络的初始部分共享）以及在网络的后面层中包括的少量新添加的卷积核来形成用于学习新类集的更新网络。我们在几个识别应用中评估了所提出的方案。我们的方法实现的分类准确性与常规增量学习方法相当（其中网络仅使用新的训练样本进行更新，无需任何网络共享）。

##### URL
[http://arxiv.org/abs/1712.02719](http://arxiv.org/abs/1712.02719)

##### PDF
[http://arxiv.org/pdf/1712.02719](http://arxiv.org/pdf/1712.02719)

