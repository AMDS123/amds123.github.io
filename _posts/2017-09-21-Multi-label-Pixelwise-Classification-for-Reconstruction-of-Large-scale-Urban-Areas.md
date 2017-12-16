---
layout: post
title: "Multi-label Pixelwise Classification for Reconstruction of Large-scale Urban Areas"
date: 2017-09-21 15:13:09
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Yuanlie He (Member, IEEE)Sudhir Mudur (Fellow, IEEE), Charalambos Poullis (Member, IEEE)
mathjax: true
---

* content
{:toc}

##### Abstract
Object classification is one of the many holy grails in computer vision and as such has resulted in a very large number of algorithms being proposed already. Specifically in recent years there has been considerable progress in this area primarily due to the increased efficiency and accessibility of deep learning techniques. In fact, for single-label object classification [i.e. only one object present in the image] the state-of-the-art techniques employ deep neural networks and are reporting very close to human-like performance. There are specialized applications in which single-label object-level classification will not suffice; for example in cases where the image contains multiple intertwined objects of different labels. In this paper, we address the complex problem of multi-label pixelwise classification. We present our distinct solution based on a convolutional neural network (CNN) for performing multi-label pixelwise classification and its application to large-scale urban reconstruction. A supervised learning approach is followed for training a 13-layer CNN using both LiDAR and satellite images. An empirical study has been conducted to determine the hyperparameters which result in the optimal performance of the CNN. Scale invariance is introduced by training the network on five different scales of the input and labeled data. This results in six pixelwise classifications for each different scale. An SVM is then trained to map the six pixelwise classifications into a single-label. Lastly, we refine boundary pixel labels using graph-cuts for maximum a-posteriori (MAP) estimation with Markov Random Field (MRF) priors. The resulting pixelwise classification is then used to accurately extract and reconstruct the buildings in large-scale urban areas. The proposed approach has been extensively tested and the results are reported.

##### Abstract (translated by Google)
对象分类是计算机视觉领域众多的圣杯之一，因此已经提出了大量的算法。特别是近年来，在这方面取得了长足的进步，主要是由于深度学习技术的效率和可及性的提高。事实上，对于单标签对象分类[即只有一个物体存在于图像中]最先进的技术采用深度神经网络，报告非常接近人类的表现。有专门的应用程序，其中单标签对象级别的分类是不够的;例如在图像包含多个不同标签的交织物体的情况下。在本文中，我们解决复杂的多标签像素分类问题。我们提出了基于卷积神经网络（CNN）的独特解决方案，用于执行多标签像素分类及其在大规模城市重建中的应用。使用LiDAR和卫星图像对13层CNN进行了监督学习。已经进行了一项实证研究，以确定导致CNN的最佳性能的超参数。通过在输入和标记的数据的五个不同尺度上训练网络来引入尺度不变性。这导致每个不同比例的六个按像素分类。随后训练SVM将六个像素级分类映射到单个标签。最后，我们使用马尔可夫随机场（MRF）先验的最大后验（MAP）估计，使用图形切割改进边界像素标签。然后使用由此产生的像素级分类来精确提取和重建大型城市地区的建筑物。所提出的方法已经过广泛的测试，并且报告了结果。

##### URL
[https://arxiv.org/abs/1709.07368](https://arxiv.org/abs/1709.07368)

##### PDF
[https://arxiv.org/pdf/1709.07368](https://arxiv.org/pdf/1709.07368)

