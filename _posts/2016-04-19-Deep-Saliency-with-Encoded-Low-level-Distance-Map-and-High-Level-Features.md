---
layout: post
title: "Deep Saliency with Encoded Low level Distance Map and High Level Features"
date: 2016-04-19 10:07:16
categories: arXiv_CV
tags: arXiv_CV Salient CNN Deep_Learning Detection
author: Gayoung Lee, Yu-Wing Tai, Junmo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in saliency detection have utilized deep learning to obtain high level features to detect salient regions in a scene. These advances have demonstrated superior results over previous works that utilize hand-crafted low level features for saliency detection. In this paper, we demonstrate that hand-crafted features can provide complementary information to enhance performance of saliency detection that utilizes only high level features. Our method utilizes both high level and low level features for saliency detection under a unified deep learning framework. The high level features are extracted using the VGG-net, and the low level features are compared with other parts of an image to form a low level distance map. The low level distance map is then encoded using a convolutional neural network(CNN) with multiple 1X1 convolutional and ReLU layers. We concatenate the encoded low level distance map and the high level features, and connect them to a fully connected neural network classifier to evaluate the saliency of a query region. Our experiments show that our method can further improve the performance of state-of-the-art deep learning-based saliency detection methods.

##### Abstract (translated by Google)
最近在显着性检测方面的进展已经利用深度学习来获得高级特征来检测场景中的显着区域。与先前的利用手工制作的低级特征进行显着性检测的工作相比，这些进步已经显示出优越的结果。在本文中，我们证明手工制作的特征可以提供补充信息，以提高仅利用高级特征的显着性检测的性能。我们的方法在统一的深度学习框架下利用高级和低级特征进行显着性检测。使用VGG-net提取高层特征，将低层特征与图像的其他部分进行比较，形成低层距离图。然后使用具有多个1×1卷积和ReLU层的卷积神经网络（CNN）对低层距离图进行编码。我们连接编码后的低层距离图和高层特征，并将它们连接到全连接的神经网络分类器来评估查询区域的显着性。我们的实验表明，我们的方法可以进一步提高最先进的基于深度学习的显着性检测方法的性能。

##### URL
[https://arxiv.org/abs/1604.05495](https://arxiv.org/abs/1604.05495)

##### PDF
[https://arxiv.org/pdf/1604.05495](https://arxiv.org/pdf/1604.05495)

