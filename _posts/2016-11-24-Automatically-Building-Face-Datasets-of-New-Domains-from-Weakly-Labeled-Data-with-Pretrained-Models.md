---
layout: post
title: "Automatically Building Face Datasets of New Domains from Weakly Labeled Data with Pretrained Models"
date: 2016-11-24 09:11:21
categories: arXiv_CV
tags: arXiv_CV Face Recognition Face_Recognition
author: Shengyong Ding, Junyu Wu, Wei Xu, Hongyang Chao
mathjax: true
---

* content
{:toc}

##### Abstract
Training data are critical in face recognition systems. However, labeling a large scale face data for a particular domain is very tedious. In this paper, we propose a method to automatically and incrementally construct datasets from massive weakly labeled data of the target domain which are readily available on the Internet under the help of a pretrained face model. More specifically, given a large scale weakly labeled dataset in which each face image is associated with a label, i.e. the name of an identity, we create a graph for each identity with edges linking matched faces verified by the existing model under a tight threshold. Then we use the maximal subgraph as the cleaned data for that identity. With the cleaned dataset, we update the existing face model and use the new model to filter the original dataset to get a larger cleaned dataset. We collect a large weakly labeled dataset containing 530,560 Asian face images of 7,962 identities from the Internet, which will be published for the study of face recognition. By running the filtering process, we obtain a cleaned datasets (99.7+% purity) of size 223,767 (recall 70.9%). On our testing dataset of Asian faces, the model trained by the cleaned dataset achieves recognition rate 93.1%, which obviously outperforms the model trained by the public dataset CASIA whose recognition rate is 85.9%.

##### Abstract (translated by Google)
培训数据在人脸识别系统中至关重要。但是，标记特定域的大规模人脸数据是非常繁琐的。在本文中，我们提出了一种自动和增量构建数据集的方法，从互联网上容易获得的目标域的大量弱标记数据在预训练人脸模型的帮助下。更具体地说，给定大标度弱标记的数据集，其中每个人脸图像与标签（即标识的名称）相关联，我们为每个标识创建一个图，其中边界链接在严格阈值下由现有模型验证的匹配人脸。然后我们使用最大子图作为该身份的清理数据。使用已清理的数据集，我们更新现有的人脸模型，并使用新模型过滤原始数据集以获得更大的清理数据集。我们从互联网上收集了一个包含530,560个亚洲人脸图像的大型弱标记数据集，共有7,962个身份，将被发布用于人脸识别的研究。通过运行过滤程序，我们获得了大小为223,767（回忆率70.9％）的清洁数据集（99.7 +％纯度）。在我们的亚洲人脸测试数据集中，被清理的数据集训练的模型的识别率达到93.1％，明显优于公认数据集CASIA训练的识别率为85.9％的模型。

##### URL
[https://arxiv.org/abs/1611.08107](https://arxiv.org/abs/1611.08107)

##### PDF
[https://arxiv.org/pdf/1611.08107](https://arxiv.org/pdf/1611.08107)

