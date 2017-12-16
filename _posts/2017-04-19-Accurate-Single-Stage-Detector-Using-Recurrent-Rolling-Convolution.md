---
layout: post
title: "Accurate Single Stage Detector Using Recurrent Rolling Convolution"
date: 2017-04-19 15:31:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Jimmy Ren, Xiaohao Chen, Jianbo Liu, Wenxiu Sun, Jiahao Pang, Qiong Yan, Yu-Wing Tai, Li Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the recent successful methods in accurate object detection and localization used some variants of R-CNN style two stage Convolutional Neural Networks (CNN) where plausible regions were proposed in the first stage then followed by a second stage for decision refinement. Despite the simplicity of training and the efficiency in deployment, the single stage detection methods have not been as competitive when evaluated in benchmarks consider mAP for high IoU thresholds. In this paper, we proposed a novel single stage end-to-end trainable object detection network to overcome this limitation. We achieved this by introducing Recurrent Rolling Convolution (RRC) architecture over multi-scale feature maps to construct object classifiers and bounding box regressors which are "deep in context". We evaluated our method in the challenging KITTI dataset which measures methods under IoU threshold of 0.7. We showed that with RRC, a single reduced VGG-16 based model already significantly outperformed all the previously published results. At the time this paper was written our models ranked the first in KITTI car detection (the hard level), the first in cyclist detection and the second in pedestrian detection. These results were not reached by the previous single stage methods. The code is publicly available.

##### Abstract (translated by Google)
目前大多数成功的精确目标检测和定位方法都采用了R-CNN型两阶段卷积神经网络（CNN）的一些变体，其中第一阶段提出了可信区域，然后是决策细化的第二阶段。尽管培训简单和部署效率高，但单个阶段检测方法在评估基准时认为mAP的IoU门槛较高时，还没有具有竞争性。在本文中，我们提出了一种新型的单端端到端可训练物体检测网络来克服这个局限性。我们通过在多尺度特征映射中引入回滚滚动卷积（RRC）体系结构来实现这一目标，以构建“深层语境”中的对象分类器和边界框回归器。我们在具有挑战性的KITTI数据集中评估了我们的方法，该数据集在IoU阈值0.7下测量方法。我们表明，在RRC的基础上，一个简化的基于VGG-16的模型已经显着地胜过了之前发表的所有结果。在撰写本文时，我们的车型在KITTI汽车检测（硬度级别）中排名第一，在骑行者检测中排名第一，在行人检测中排在第二位。以前的单阶段方法没有达到这些结果。该代码是公开的。

##### URL
[https://arxiv.org/abs/1704.05776](https://arxiv.org/abs/1704.05776)

##### PDF
[https://arxiv.org/pdf/1704.05776](https://arxiv.org/pdf/1704.05776)

