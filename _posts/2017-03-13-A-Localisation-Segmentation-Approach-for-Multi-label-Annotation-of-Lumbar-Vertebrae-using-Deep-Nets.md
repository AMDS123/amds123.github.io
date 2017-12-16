---
layout: post
title: "A Localisation-Segmentation Approach for Multi-label Annotation of Lumbar Vertebrae using Deep Nets"
date: 2017-03-13 11:55:16
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Relation
author: Anjany Sekuboyina, Alexander Valentinitsch, Jan S. Kirschke, Bjoern H. Menze
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-class segmentation of vertebrae is a non-trivial task mainly due to the high correlation in the appearance of adjacent vertebrae. Hence, such a task calls for the consideration of both global and local context. Based on this motivation, we propose a two-staged approach that, given a computed tomography dataset of the spine, segments the five lumbar vertebrae and simultaneously labels them. The first stage employs a multi-layered perceptron performing non-linear regression for locating the lumbar region using the global context. The second stage, comprised of a fully-convolutional deep network, exploits the local context in the localised lumbar region to segment and label the lumbar vertebrae in one go. Aided with practical data augmentation for training, our approach is highly generalisable, capable of successfully segmenting both healthy and abnormal vertebrae (fractured and scoliotic spines). We consistently achieve an average Dice coefficient of over 90 percent on a publicly available dataset of the xVertSeg segmentation challenge of MICCAI 2016. This is particularly noteworthy because the xVertSeg dataset is beset with severe deformities in the form of vertebral fractures and scoliosis.

##### Abstract (translated by Google)
椎骨的多级分割是非平凡的任务，主要是由于相邻椎骨的外观高度相关。因此，这样的任务需要全球和当地的考虑。基于这个动机，我们提出了一个两阶段的方法，给出一个计算机断层扫描数据集的脊椎，分割五个腰椎，同时标签。第一阶段采用多层感知器执行非线性回归以使用全局上下文来定位腰部区域。第二阶段由完全卷积的深度网络组成，利用局部腰部的局部环境对腰椎进行一次分割和标记。在实际的数据增强训练的帮助下，我们的方法具有高度的一般性，能够成功分割健康和异常的椎骨（骨折和脊柱侧凸）。在MICCAI 2016的xVertSeg分割挑战的公开数据集中，我们始终获得超过90％的平均Dice系数。这一点尤其值得注意，因为xVertSeg数据集严重畸形形式为椎骨骨折和脊柱侧凸。

##### URL
[https://arxiv.org/abs/1703.04347](https://arxiv.org/abs/1703.04347)

##### PDF
[https://arxiv.org/pdf/1703.04347](https://arxiv.org/pdf/1703.04347)

