---
layout: post
title: "Automatic Vertebra Labeling in Large-Scale 3D CT using Deep Image-to-Image Network with Message Passing and Sparsity Regularization"
date: 2017-05-17 03:56:14
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge CNN Detection Relation
author: Dong Yang, Tao Xiong, Daguang Xu, Qiangui Huang, David Liu, S.Kevin Zhou, Zhoubing Xu, JinHyeong Park, Mingqing Chen, Trac D. Tran, Sang Peter Chin, Dimitris Metaxas, Dorin Comaniciu
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic localization and labeling of vertebra in 3D medical images plays an important role in many clinical tasks, including pathological diagnosis, surgical planning and postoperative assessment. However, the unusual conditions of pathological cases, such as the abnormal spine curvature, bright visual imaging artifacts caused by metal implants, and the limited field of view, increase the difficulties of accurate localization. In this paper, we propose an automatic and fast algorithm to localize and label the vertebra centroids in 3D CT volumes. First, we deploy a deep image-to-image network (DI2IN) to initialize vertebra locations, employing the convolutional encoder-decoder architecture together with multi-level feature concatenation and deep supervision. Next, the centroid probability maps from DI2IN are iteratively evolved with the message passing schemes based on the mutual relation of vertebra centroids. Finally, the localization results are refined with sparsity regularization. The proposed method is evaluated on a public dataset of 302 spine CT volumes with various pathologies. Our method outperforms other state-of-the-art methods in terms of localization accuracy. The run time is around 3 seconds on average per case. To further boost the performance, we retrain the DI2IN on additional 1000+ 3D CT volumes from different patients. To the best of our knowledge, this is the first time more than 1000 3D CT volumes with expert annotation are adopted in experiments for the anatomic landmark detection tasks. Our experimental results show that training with such a large dataset significantly improves the performance and the overall identification rate, for the first time by our knowledge, reaches 90 %.

##### Abstract (translated by Google)
三维医学图像中椎骨的自动定位和标记在许多临床任务中起着重要的作用，包括病理诊断，手术规划和术后评估。然而，由于金属种植体引起的异常脊柱弯曲，明显的视觉成像伪影，视野受限等病理情况的异常情况增加了准确定位的难度。在本文中，我们提出了一种自动，快速的算法来定位和标注三维CT体积中的椎骨质心。首先，我们部署了一个深度图像到图像网络（DI2IN）来初始化椎骨位置，采用卷积编码器 - 解码器架构以及多级特征级联和深度监督。接下来，根据椎骨质心的相互关系，DI2IN的质心概率图与消息传递方案迭代进化。最后，利用稀疏正则化对本地化结果进行了细化。所提出的方法在具有各种病症的302个脊柱CT体积的公共数据集上进行评估。我们的方法在定位精度方面胜过了其他最先进的方法。运行时间平均约为3秒。为了进一步提高性能，我们再次对来自不同患者的1000多个3D CT体积进行DI2IN再训练。就我们所知，这是第一次在解剖标志检测任务中采用1000多个具有专家注释的三维CT体积实验。我们的实验结果表明，训练这样一个庞大的数据集显着提高了性能和整体识别率，我们第一次知道，达到90％。

##### URL
[https://arxiv.org/abs/1705.05998](https://arxiv.org/abs/1705.05998)

##### PDF
[https://arxiv.org/pdf/1705.05998](https://arxiv.org/pdf/1705.05998)

