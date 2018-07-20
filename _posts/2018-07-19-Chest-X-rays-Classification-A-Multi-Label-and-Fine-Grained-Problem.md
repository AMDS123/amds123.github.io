---
layout: post
title: "Chest X-rays Classification: A Multi-Label and Fine-Grained Problem"
date: 2018-07-19 06:02:54
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Relation
author: Zongyuan Ge, Dwarikanath Mahapatra, Suman Sedai, Rajib Chakravorty
mathjax: true
---

* content
{:toc}

##### Abstract
The widely used ChestX-ray14 dataset addresses an important medical image classification problem and has the following caveats: 1) many lung pathologies are visually similar, 2) a variant of diseases including lung cancer, tuberculosis, and pneumonia are present in a single scan, i.e. multiple labels and 3) The incidence of healthy images is much larger than diseased samples, creating imbalanced data. These properties are common in medical domain. Existing literature uses stateof- the-art DensetNet/Resnet models being transfer learned where output neurons of the networks are trained for individual diseases to cater for multiple diseases labels in each image. However, most of them don't consider relationship between multiple classes. In this work we have proposed a novel error function, Multi-label Softmax Loss (MSML), to specifically address the properties of multiple labels and imbalanced data. Moreover, we have designed deep network architecture based on fine-grained classification concept that incorporates MSML. We have evaluated our proposed method on various network backbones and showed consistent performance improvements of AUC-ROC scores on the ChestX-ray14 dataset. The proposed error function provides a new method to gain improved performance across wider medical datasets.

##### Abstract (translated by Google)
广泛使用的ChestX-ray14数据集解决了一个重要的医学图像分类问题，并且具有以下注意事项：1）许多肺病变在视觉上相似，2）在单次扫描中存在包括肺癌，肺结核和肺炎在内的多种疾病变体，即多个标签和3）健康图像的发生率比患病样本大得多，从而产生不平衡的数据。这些属性在医学领域很常见。现有文献使用最先进的DensetNet / Resnet模型进行转移学习，其中网络的输出神经元被训练用于个体疾病以满足每个图像中的多种疾病标签。但是，大多数人不考虑多个类之间的关系。在这项工作中，我们提出了一种新颖的误差函数，多标签Softmax Loss（MSML），专门用于解决多个标签和不平衡数据的属性。此外，我们设计了基于细粒度分类概念的深度网络架构，该概念结合了MSML。我们已经在各种网络主干上评估了我们提出的方法，并且在ChestX-ray14数据集上显示了AUC-ROC分数的一致性能改进。提出的误差函数提供了一种新方法，以在更广泛的医学数据集中获得改进的性能。

##### URL
[https://arxiv.org/abs/1807.07247](https://arxiv.org/abs/1807.07247)

##### PDF
[https://arxiv.org/pdf/1807.07247](https://arxiv.org/pdf/1807.07247)

