---
layout: post
title: 'Learning Object Detectors from Scratch with Gated Recurrent Feature Pyramids'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: arXiv_CV 'Object Detection' 'Object Detection' 'Detection' 'Detection'
author: Zhiqiang Shen, Honghui Shi, Rogerio Feris, Liangliang Cao, Shuicheng Yan, Ding Liu, Xinchao Wang, Xiangyang Xue, Thomas S. Huang
---

* content
{:toc}

##### Abstract
In this paper, we propose gated recurrent feature pyramid for the problem of learning object detection from scratch. Our approach is motivated by the recent work of deeply supervised object detector (DSOD), but explores new network architecture that dynamically adjusts the supervision intensities of intermediate layers for various scales in object detection. The benefits of the proposed method are two-fold: First, we propose a recurrent feature-pyramid structure to squeeze rich spatial and semantic features into a single prediction layer that further reduces the number of parameters to learn (DSOD need learn 1/2, but our method need only 1/3). Thus our new model is more fit for learning from scratch, and can converge faster than DSOD (using only 50% of iterations). Second, we introduce a novel gate-controlled prediction strategy to adaptively enhance or attenuate supervision at different scales based on the input object size. As a result, our model is more suitable for detecting small objects. To the best of our knowledge, our study is the best performed model of learning object detection from scratch. Our method in the PASCAL VOC 2012 comp3 leaderboard (which compares object detectors that are trained only with PASCAL VOC data) demonstrates a significant performance jump, from previous 64% to our 77% (VOC 07++12) and 72.5% (VOC 12). We also evaluate the performance of our method on PASCAL VOC 2007, 2012 and MS COCO datasets, and find that the accuracy of our learning from scratch method can even beat a lot of the state-of-the-art detection methods which use pre-trained models from ImageNet. Code is available at: https://github.com/szq0214/GRP-DSOD .

##### Abstract (translated by Google)
在本文中，我们针对学习对象从零开始的检测问题提出了门控循环特征金字塔。我们的方法受深度监督物体探测器（DSOD）的近期工作的启发，但是探索了新的网络体系结构，动态调整物体检测中各种尺度的中间层监视强度。本文提出的方法有两方面的好处：首先，我们提出了一个经常性的特征金字塔结构，将丰富的空间和语义特征压缩到一个单一的预测层，进一步减少了学习参数的数量（DSOD需要学习1/2，但我们的方法只需要1/3）。因此，我们的新模型更适合于从头开始学习，并且可以比DSOD（仅使用50％的迭代）更快地收敛。其次，引入了一种新颖的门控预测策略，根据输入的对象大小自适应地增强或减弱不同尺度的监督。因此，我们的模型更适合检测小物体。就我们所知，我们的研究是从零开始学习对象检测的最佳模型。我们在PASCAL VOC 2012 comp3排行榜上的方法（比较仅用PASCAL VOC数据进行培训的物体探测器）显示出从之前的64％到77％（VOC 07 ++ 12）和72.5％（VOC 12 ）。我们还评估了我们的方法在PASCAL VOC 2007,2012和MS COCO数据集上的性能，发现我们从头开始学习的准确性甚至可以击败许多使用预处理方法的最先进的检测方法，来自ImageNet的训练好的模型。代码位于：https：//github.com/szq0214/GRP-DSOD。

##### URL
[http://arxiv.org/abs/1712.00886](http://arxiv.org/abs/1712.00886)

