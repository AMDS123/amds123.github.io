---
layout: post
title: "Multi-stage Object Detection with Group Recursive Learning"
date: 2016-08-18 02:37:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Classification Detection Relation
author: Jianan Li, Xiaodan Liang, Jianshu Li, Tingfa Xu, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Most of existing detection pipelines treat object proposals independently and predict bounding box locations and classification scores over them separately. However, the important semantic and spatial layout correlations among proposals are often ignored, which are actually useful for more accurate object detection. In this work, we propose a new EM-like group recursive learning approach to iteratively refine object proposals by incorporating such context of surrounding proposals and provide an optimal spatial configuration of object detections. In addition, we propose to incorporate the weakly-supervised object segmentation cues and region-based object detection into a multi-stage architecture in order to fully exploit the learned segmentation features for better object detection in an end-to-end way. The proposed architecture consists of three cascaded networks which respectively learn to perform weakly-supervised object segmentation, object proposal generation and recursive detection refinement. Combining the group recursive learning and the multi-stage architecture provides competitive mAPs of 78.6% and 74.9% on the PASCAL VOC2007 and VOC2012 datasets respectively, which outperforms many well-established baselines [10] [20] significantly.

##### Abstract (translated by Google)
现有的大部分检测管线都是独立处理对象提议，分别对其进行边界框位置和分类评分。然而，建议之间的重要语义和空间布局相关性往往被忽略，这对于更精确的对象检测实际上是有用的。在这项工作中，我们提出了一种新的类EM组递归学习方法，通过合并周围建议的上下文来迭代地细化对象建议，并提供对象检测的最佳空间配置。另外，为了充分利用学习到的分割特征，以端到端的方式更好地进行对象检测，我们提出将弱监督对象分割线索和基于区域的对象检测结合到一个多阶段体系结构中。所提出的架构由三个级联网络组成，分别学习执行弱监督对象分割，对象建议生成和递归检测细化。结合组递归学习和多级架构分别提供了关于PASCAL VOC2007的78.6％和74.9％的竞争地图和VOC2012数据集，其性能优于许多公认的基线[10] [20]显著。

##### URL
[https://arxiv.org/abs/1608.05159](https://arxiv.org/abs/1608.05159)

##### PDF
[https://arxiv.org/pdf/1608.05159](https://arxiv.org/pdf/1608.05159)

