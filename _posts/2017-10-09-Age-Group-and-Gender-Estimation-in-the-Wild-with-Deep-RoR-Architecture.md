---
layout: post
title: "Age Group and Gender Estimation in the Wild with Deep RoR Architecture"
date: 2017-10-09 08:27:13
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Classification
author: Ke Zhang, Ce Gao, Liru Guo, Miao Sun, Xingfang Yuan, Tony X. Han, Zhenbing Zhao, Baogang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically predicting age group and gender from face images acquired in unconstrained conditions is an important and challenging task in many real-world applications. Nevertheless, the conventional methods with manually-designed features on in-the-wild benchmarks are unsatisfactory because of incompetency to tackle large variations in unconstrained images. This difficulty is alleviated to some degree through Convolutional Neural Networks (CNN) for its powerful feature representation. In this paper, we propose a new CNN based method for age group and gender estimation leveraging Residual Networks of Residual Networks (RoR), which exhibits better optimization ability for age group and gender classification than other CNN architectures.Moreover, two modest mechanisms based on observation of the characteristics of age group are presented to further improve the performance of age estimation.In order to further improve the performance and alleviate over-fitting problem, RoR model is pre-trained on ImageNet firstly, and then it is fune-tuned on the IMDB-WIKI-101 data set for further learning the features of face images, finally, it is used to fine-tune on Adience data set. Our experiments illustrate the effectiveness of RoR method for age and gender estimation in the wild, where it achieves better performance than other CNN methods. Finally, the RoR-152+IMDB-WIKI-101 with two mechanisms achieves new state-of-the-art results on Adience benchmark.

##### Abstract (translated by Google)
从无约束条件下获取的人脸图像中自动预测年龄组和性别是许多实际应用中的重要和具有挑战性的任务。尽管如此，传统的手工设计特征在野外基准的方法是不能令人满意的，因为无法解决无约束图像的大变化。通过卷积神经网络（CNN）的强大的特征表示，这一难度得到了一定的缓解。在本文中，我们提出了一种新的基于CNN的年龄段和性别估计方法，利用残差网络残差网络（RoR），该方法比其他CNN架构具有更好的年龄段和性别分类优化能力。另外，为了进一步提高性能，减少过度拟合问题，本文首先对ImageNet进行了RoR模型的预训练，然后对其进行了优化IMDB-WIKI-101数据集用于进一步学习人脸图像的特征，最后用于对Adience数据集进行微调。我们的实验说明了RoR方法在野外进行年龄和性别估计的有效性，其比其他CNN方法具有更好的性能。最后，具有两种机制的RoR-152 + IMDB-WIKI-101在Adience基准测试中获得了最新的最新成果。

##### URL
[https://arxiv.org/abs/1710.02985](https://arxiv.org/abs/1710.02985)

##### PDF
[https://arxiv.org/pdf/1710.02985](https://arxiv.org/pdf/1710.02985)

