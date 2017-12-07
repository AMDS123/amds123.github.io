---
layout: post
title: "Dynamic Zoom-in Network for Fast Object Detection in Large Images"
date: 2017-11-14 16:52:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Reinforcement_Learning Detection
author: Mingfei Gao, Ruichi Yu, Ang Li, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a generic framework that reduces the computational cost of object detection while retaining accuracy for scenarios where objects with varied sizes appear in high resolution images. Detection progresses in a coarse-to-fine manner, first on a down-sampled version of the image and then on a sequence of higher resolution regions identified as likely to improve the detection accuracy. Built upon reinforcement learning, our approach consists of a model (R-net) that uses coarse detection results to predict the potential accuracy gain for analyzing a region at a higher resolution and another model (Q-net) that sequentially selects regions to zoom in. Experiments on the Caltech Pedestrians dataset show that our approach reduces the number of processed pixels by over 50% without a drop in detection accuracy. The merits of our approach become more significant on a high resolution test set collected from YFCC100M dataset where our approach maintains high detection performance while reducing the number of processed pixels by about 70% and the detection time by over 50%.

##### Abstract (translated by Google)
我们引入了一个通用的框架，降低了对象检测的计算成本，同时保持对高分辨率图像中出现大小不同的对象的场景的精度。检测以粗到细的方式进行，首先在图像的下采样版本上，然后在被识别为可能提高检测精度的更高分辨率区域的序列上进行。建立在强化学习的基础上，我们的方法由一个模型（R-net）组成，该模型使用粗略的检测结果来预测分析较高分辨率区域的潜在精度增益，另一个模型（Q-net）对加州理工学院的行人数据集的实验表明，我们的方法减少了50％以上的处理像素的数量没有下降的检测精度。我们的方法的优点在从YFCC100M数据集收集的高分辨率测试集上变得更加重要，其中我们的方法保持高检测性能，同时将处理像素的数量减少约70％并且检测时间减少超过50％。

##### URL
[https://arxiv.org/abs/1711.05187](https://arxiv.org/abs/1711.05187)

##### PDF
[https://arxiv.org/pdf/1711.05187](https://arxiv.org/pdf/1711.05187)

