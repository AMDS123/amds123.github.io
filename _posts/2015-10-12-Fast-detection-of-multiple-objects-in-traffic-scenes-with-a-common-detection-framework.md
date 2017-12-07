---
layout: post
title: "Fast detection of multiple objects in traffic scenes with a common detection framework"
date: 2015-10-12 02:30:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Recognition
author: Qichang Hu, Sakrapee Paisitkriangkrai, Chunhua Shen, Anton van den Hengel, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
Traffic scene perception (TSP) aims to real-time extract accurate on-road environment information, which in- volves three phases: detection of objects of interest, recognition of detected objects, and tracking of objects in motion. Since recognition and tracking often rely on the results from detection, the ability to detect objects of interest effectively plays a crucial role in TSP. In this paper, we focus on three important classes of objects: traffic signs, cars, and cyclists. We propose to detect all the three important objects in a single learning based detection framework. The proposed framework consists of a dense feature extractor and detectors of three important classes. Once the dense features have been extracted, these features are shared with all detectors. The advantage of using one common framework is that the detection speed is much faster, since all dense features need only to be evaluated once in the testing phase. In contrast, most previous works have designed specific detectors using different features for each of these objects. To enhance the feature robustness to noises and image deformations, we introduce spatially pooled features as a part of aggregated channel features. In order to further improve the generalization performance, we propose an object subcategorization method as a means of capturing intra-class variation of objects. We experimentally demonstrate the effectiveness and efficiency of the proposed framework in three detection applications: traffic sign detection, car detection, and cyclist detection. The proposed framework achieves the competitive performance with state-of- the-art approaches on several benchmark datasets.

##### Abstract (translated by Google)
交通场景感知（TSP）旨在实时提取准确的道路环境信息，包括三个阶段：感兴趣对象的检测，被检测对象的识别以及运动中对象的跟踪。由于识别和跟踪通常依赖于检测结果，因此在TSP中有效检测感兴趣对象的能力起着至关重要的作用。在本文中，我们将重点放在三类重要的物体上：交通标志，汽车和骑自行车。我们建议在单个基于学习的检测框架中检测所有三个重要的对象。所提出的框架由密集特征提取器和三个重要类别的检测器组成。一旦密集的特征被提取出来，这些特征就与所有的探测器共享。使用一个通用框架的优点是检测速度要快得多，因为所有的密集特征只需要在测试阶段评估一次即可。相比之下，大多数以前的作品都为这些物体设计了不同的特征。为了增强对噪声和图像变形的特征鲁棒性，我们引入空间合并特征作为聚合信道特征的一部分。为了进一步提高泛化性能，本文提出了一种对象子类别化方法作为捕捉对象类内变异的手段。我们通过实验证明了所提出的框架在三种检测应用中的有效性和效率：交通标志检测，汽车检测和骑车者检测。所提出的框架通过几个基准数据集上的最先进的方法实现了竞争性的表现。

##### URL
[https://arxiv.org/abs/1510.03125](https://arxiv.org/abs/1510.03125)

##### PDF
[https://arxiv.org/pdf/1510.03125](https://arxiv.org/pdf/1510.03125)

