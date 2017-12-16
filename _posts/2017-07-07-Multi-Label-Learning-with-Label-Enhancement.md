---
layout: post
title: "Multi-Label Learning with Label Enhancement"
date: 2017-07-07 08:36:50
categories: arXiv_CV
tags: arXiv_CV
author: Ruifeng Shao, Xin Geng, Ning Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label learning deals with training instances associated with multiple labels. Many common multi-label algorithms are to treat each label in a crisp manner, being either relevant or irrelevant to an instance, and such label can be called logical label. In contrast, we assume that there is a vector of numerical label behind each multi-label instance, and the numerical label can be treated as the indicator to judge whether the corresponding label is relevant or irrelevant to the instance. The approach we are proposing transforms multilabel problem into regression problem about numerical labels which can reflect the hidden label importance. In order to explore the numerical label, one way is to extend the label space to a Euclidean space by mining the hidden label importance from the training instances. Such process of transforming logical labels into numerical labels is called Label Enhancement. Besides, we give three assumptions for numerical label of multi-label instance in this paper. Based on this, we propose an effective multi-label learning framework called MLL-LE, i.e., Multi-Label Learning with Label Enhancement, which incorporates the regression loss and the three assumptions into a unified framework. Extensive experiments validate the effectiveness of MLL-LE framework.

##### Abstract (translated by Google)
多标签学习处理与多个标签关联的训练实例。许多常见的多标签算法都是以一种清晰的方式处理每个标签，与一个实例相关或不相关，这样的标签可以称为逻辑标签。相比之下，我们假设每个多标签实例后面都有一个数字标签向量，数字标签可以作为判断相应标签与实例相关还是不相关的指标。我们提出的方法将多标签问题转化为可以反映隐藏标签重要性的数字标签的回归问题。为了探索数字标签，一种方法是通过挖掘训练实例中的隐藏标签重要性将标签空间扩展到欧几里得空间。将逻辑标签转换为数字标签的过程称为标签增强。另外，本文给出了多标签实例数值标签的三个假设。在此基础上，提出了一个有效的MLL-LE多标签学习框架，即带有标签增强的多标签学习，它将回归损失和三个假设合并到一个统一的框架中。大量的实验验证了MLL-LE框架的有效性。

##### URL
[https://arxiv.org/abs/1706.08323](https://arxiv.org/abs/1706.08323)

##### PDF
[https://arxiv.org/pdf/1706.08323](https://arxiv.org/pdf/1706.08323)

