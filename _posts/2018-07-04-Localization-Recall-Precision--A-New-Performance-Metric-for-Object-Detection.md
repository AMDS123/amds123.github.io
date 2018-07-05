---
layout: post
title: "Localization Recall Precision : A New Performance Metric for Object Detection"
date: 2018-07-04 17:47:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Kemal Oksuz, Baris Can Cam, Emre Akbas, Sinan Kalkan
mathjax: true
---

* content
{:toc}

##### Abstract
Average precision (AP), the area under the recall-precision (RP) curve, is the standard performance measure for object detection. Despite its wide acceptance, it has a number of shortcomings, the most important of which are (i) the inability to distinguish very different RP curves, and (ii) the lack of directly measuring bounding box localization accuracy. In this paper, we propose 'Localization Recall Precision (LRP) Error', a new metric which we specifically designed for object detection. LRP Error is composed of three components related to localization, false negative (FN) rate and false positive (FP) rate. Based on LRP, we introduce the 'Optimal LRP', the minimum achievable LRP error representing the best achievable configuration of the detector in terms of recall-precision and the tightness of the boxes. In contrast to AP, which considers precisions over the entire recall domain, Optimal LRP determines the 'best' confidence score threshold for a class, which balances the trade-off between localization and recall-precision. In our experiments, we show that, for state-of-the-art object (SOTA) detectors, Optimal LRP provides richer and more discriminative information than AP. We also demonstrate that the best confidence score thresholds vary significantly among classes and detectors. Moreover, we present LRP results of a simple online video object detector which uses a SOTA still image object detector and show that the class-specific optimized thresholds increase the accuracy against the common approach of using a general threshold for all classes. We provide the source code that can compute LRP for the PASCAL VOC and MSCOCO datasets in https://github.com/cancam/LRP. Our source code can easily be adapted to other datasets as well.

##### Abstract (translated by Google)
平均精度（AP）是召回精度（RP）曲线下的面积，是物体检测的标准性能指标。尽管它被广泛接受，但它有许多缺点，其中最重要的是（i）无法区分非常不同的RP曲线，以及（ii）缺乏直接测量边界框定位精度。在本文中，我们提出了“本地化召回精度（LRP）误差”，这是我们专门为物体检测设计的一种新指标。 LRP错误由与定位，假阴性（FN）率和假阳性（FP）率相关的三个组成部分组成。基于LRP，我们引入了“最佳LRP”，最小可达到的LRP误差代表了探测器在召回精度和箱子紧密度方面可实现的最佳配置。与考虑整个召回域精确度的AP相比，最佳LRP确定了一个类的“最佳”置信度得分阈值，这平衡了本地化和召回精度之间的权衡。在我们的实验中，我们表明，对于最先进的物体（SOTA）探测器，Optimal LRP提供比AP更丰富和更具辨别力的信息。我们还证明了最佳置信度得分阈值在类和检测器之间差异很大。此外，我们提出了一个简单的在线视频对象检测器的LRP结果，该检测器使用SOTA静止图像对象检测器，并显示特定于类的优化阈值提高了使用所有类的一般阈值的常用方法的准确性。我们提供了可以在https://github.com/cancam/LRP中为PASCAL VOC和MSCOCO数据集计算LRP的源代码。我们的源代码也可以轻松地适应其他数据集。

##### URL
[http://arxiv.org/abs/1807.01696](http://arxiv.org/abs/1807.01696)

##### PDF
[http://arxiv.org/pdf/1807.01696](http://arxiv.org/pdf/1807.01696)

