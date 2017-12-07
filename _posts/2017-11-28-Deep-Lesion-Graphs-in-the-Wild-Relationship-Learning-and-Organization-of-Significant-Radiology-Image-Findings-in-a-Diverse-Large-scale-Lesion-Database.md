---
layout: post
title: "Deep Lesion Graphs in the Wild: Relationship Learning and Organization of Significant Radiology Image Findings in a Diverse Large-scale Lesion Database"
date: 2017-11-28 20:06:10
categories: arXiv_CV
tags: arXiv_CV GAN
author: Ke Yan, Xiaosong Wang, Le Lu, Ling Zhang, Adam Harrison, Mohammadhad Bagheri, Ronald Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Radiologists in their daily work routinely find and annotate significant abnormalities on a large number of radiology images. Such abnormalities, or lesions, have collected over years and stored in hospitals' picture archiving and communication systems. However, they are basically unsorted and lack semantic annotations like type and location. In this paper, we aim to organize and explore them by learning a deep feature representation for each lesion. A large-scale and comprehensive dataset, DeepLesion, is introduced for this task. DeepLesion contains bounding boxes and size measurements of over 32K lesions. To model their similarity relationship, we leverage multiple supervision information including types, self-supervised location coordinates and sizes. They require little manual annotation effort but describe useful attributes of the lesions. Then, a triplet network is utilized to learn lesion embeddings with a sequential sampling strategy to depict their hierarchical similarity structure. Experiments show promising qualitative and quantitative results on lesion retrieval, clustering, and classification. The learned embeddings can be further employed to build a lesion graph for various clinically useful applications. We propose algorithms for intra-patient lesion matching and missing annotation mining. Experimental results validate their effectiveness.

##### Abstract (translated by Google)
放射科医师在日常工作中经常发现和注释大量放射学图像上的显着异常。这些异常或病变经过多年的收集并存储在医院的图像存档和通信系统中。但是，它们基本上是未排序的，缺少类型和位置等语义注释。在本文中，我们的目标是通过学习每个病变的深度特征表示来组织和探索它们。这个任务引入了一个大规模，全面的数据集DeepLesion。 DeepLesion包含32K以上病灶的边框和尺寸测量。为了建立相似关系的模型，我们利用了多种监督信息，包括类型，自我监督的位置坐标和大小。他们只需要很少的手动注释工作，但描述了病变的有用属性。然后，利用三重​​网络，利用顺序采样策略来学习病变嵌入，以描绘其分层相似性结构。实验显示在病变检索，聚类和分类方面有前景的定性和定量结果。学习到的嵌入可以进一步用于建立各种临床有用的应用程序的病变图。我们提出了用于患者病变匹配和缺少注释挖掘的算法。实验结果验证了它们的有效性。

##### URL
[https://arxiv.org/abs/1711.10535](https://arxiv.org/abs/1711.10535)

##### PDF
[https://arxiv.org/pdf/1711.10535](https://arxiv.org/pdf/1711.10535)

