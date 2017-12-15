---
layout: post
title: "Deep Image Retrieval: Learning global representations for image search"
date: 2016-07-28 10:44:17
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval
author: Albert Gordo, Jon Almazan, Jerome Revaud, Diane Larlus
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach for instance-level image retrieval. It produces a global and compact fixed-length representation for each image by aggregating many region-wise descriptors. In contrast to previous works employing pre-trained deep networks as a black box to produce features, our method leverages a deep architecture trained for the specific task of image retrieval. Our contribution is twofold: (i) we leverage a ranking framework to learn convolution and projection weights that are used to build the region features; and (ii) we employ a region proposal network to learn which regions should be pooled to form the final global descriptor. We show that using clean training data is key to the success of our approach. To that aim, we use a large scale but noisy landmark dataset and develop an automatic cleaning approach. The proposed architecture produces a global image representation in a single forward pass. Our approach significantly outperforms previous approaches based on global descriptors on standard datasets. It even surpasses most prior works based on costly local descriptor indexing and spatial verification. Additional material is available at www.xrce.xerox.com/Deep-Image-Retrieval.

##### Abstract (translated by Google)
我们提出了一种新颖的实例级图像检索方法。它通过聚合许多区域明确的描述符为每个图像产生一个全局和紧凑的固定长度表示。与之前使用预先训练的深度网络作为黑盒来产生特征的作品相比，我们的方法利用了针对特定图像检索任务训练的深层结构。我们的贡献是双重的：（i）我们利用排序框架来学习用于构建地区特征的卷积和投影权重; （ii）我们使用区域提案网络来了解哪些区域应该被汇集起来形成最终的全局描述符。我们表明，使用清洁的培训数据是我们的方法成功的关键。为了达到这个目的，我们使用了一个大规模，但嘈杂的地标数据集，并开发了一种自动清洁方法。所提出的架构在单个正向通道中产生全局图像表示。我们的方法明显优于基于标准数据集上全局描述符的先前方法。它甚至超过了大部分基于昂贵的局部描述符索引和空间验证的作品。其他材料可从www.xrce.xerox.com/Deep-Image-Retrieval获得。

##### URL
[https://arxiv.org/abs/1604.01325](https://arxiv.org/abs/1604.01325)

##### PDF
[https://arxiv.org/pdf/1604.01325](https://arxiv.org/pdf/1604.01325)

