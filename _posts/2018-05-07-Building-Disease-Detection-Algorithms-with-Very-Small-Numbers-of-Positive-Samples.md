---
layout: post
title: "Building Disease Detection Algorithms with Very Small Numbers of Positive Samples"
date: 2018-05-07 20:26:14
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Classification Deep_Learning Detection
author: Ken C. L. Wong, Alexandros Karargyris, Tanveer Syeda-Mahmood, Mehdi Moradi
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep learning can provide promising results in medical image analysis, the lack of very large annotated datasets confines its full potential. Furthermore, limited positive samples also create unbalanced datasets which limit the true positive rates of trained models. As unbalanced datasets are mostly unavoidable, it is greatly beneficial if we can extract useful knowledge from negative samples to improve classification accuracy on limited positive samples. To this end, we propose a new strategy for building medical image analysis pipelines that target disease detection. We train a discriminative segmentation model only on normal images to provide a source of knowledge to be transferred to a disease detection classifier. We show that using the feature maps of a trained segmentation network, deviations from normal anatomy can be learned by a two-class classification network on an extremely unbalanced training dataset with as little as one positive for 17 negative samples. We demonstrate that even though the segmentation network is only trained on normal cardiac computed tomography images, the resulting feature maps can be used to detect pericardial effusion and cardiac septal defects with two-class convolutional classification networks.

##### Abstract (translated by Google)
虽然深度学习可以在医学图像分析中提供有希望的结果，但缺少大量带注释的数据集将限制其全部潜力。此外，有限的正面样本也会产生不平衡的数据集，这会限制训练模型的真实阳性率。由于不平衡数据集大多是不可避免的，如果我们可以从负样本中提取有用的知识以提高有限正样本的分类准确度，这将是非常有益的。为此，我们提出了一个新的战略来构建以疾病检测为目标的医学图像分析流水线。我们仅对正常图像训练区分分割模型，以提供转移到疾病检测分类器的知识来源。我们表明，使用经过训练的分割网络的特征映射，可以通过一个极端不平衡的训练数据集上的两级分类网络来学习与正常解剖结构的偏差，对于17个否定样本，只有一个正值。我们证明，即使分割网络仅在正常心脏计算机断层扫描图像上训练，所得特征图可用于使用两级卷积分类网络来检测心包积液和心脏间隔缺损。

##### URL
[https://arxiv.org/abs/1805.02730](https://arxiv.org/abs/1805.02730)

##### PDF
[https://arxiv.org/pdf/1805.02730](https://arxiv.org/pdf/1805.02730)

