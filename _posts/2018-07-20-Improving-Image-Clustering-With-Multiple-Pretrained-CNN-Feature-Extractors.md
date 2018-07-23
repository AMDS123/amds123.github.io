---
layout: post
title: "Improving Image Clustering With Multiple Pretrained CNN Feature Extractors"
date: 2018-07-20 09:46:55
categories: arXiv_CV
tags: arXiv_CV CNN
author: Joris Gu&#xe9;rin, Byron Boots
mathjax: true
---

* content
{:toc}

##### Abstract
For many image clustering problems, replacing raw image data with features extracted by a pretrained convolutional neural network (CNN), leads to better clustering performance. However, the specific features extracted, and, by extension, the selected CNN architecture, can have a major impact on the clustering results. In practice, this crucial design choice is often decided arbitrarily due to the impossibility of using cross-validation with unsupervised learning problems. However, information contained in the different pretrained CNN architectures may be complementary, even when pretrained on the same data. To improve clustering performance, we rephrase the image clustering problem as a multi-view clustering (MVC) problem that considers multiple different pretrained feature extractors as different "views" of the same data. We then propose a multi-input neural network architecture that is trained end-to-end to solve the MVC problem effectively. Our experimental results, conducted on three different natural image datasets, show that: 1. using multiple pretrained CNNs jointly as feature extractors improves image clustering; 2. using an end-to-end approach improves MVC; and 3. combining both produces state-of-the-art results for the problem of image clustering.

##### Abstract (translated by Google)
对于许多图像聚类问题，用由预训练卷积神经网络（CNN）提取的特征替换原始图像数据，导致更好的聚类性能。但是，通过扩展，所选择的CNN架构提取的特定功能可能对群集结果产生重大影响。在实践中，这种关键的设计选择通常是任意决定的，因为不可能使用交叉验证和无监督的学习问题。然而，即使在相同数据上预训练时，包含在不同预训练CNN架构中的信息也可以是互补的。为了提高聚类性能，我们将图像聚类问题重新定义为多视图聚类（MVC）问题，该问题将多个不同的预训练特征提取器视为相同数据的不同“视图”。然后，我们提出了一种多输入神经网络架构，该架构经过端到端的训练，可以有效地解决MVC问题。我们在三个不同的自然图像数据集上进行的实验结果表明：1。联合使用多个预训练的CNN作为特征提取器改进了图像聚类; 2.使用端到端方法改进MVC;结合两者产生了图像聚类问题的最新结果。

##### URL
[http://arxiv.org/abs/1807.07760](http://arxiv.org/abs/1807.07760)

##### PDF
[http://arxiv.org/pdf/1807.07760](http://arxiv.org/pdf/1807.07760)

