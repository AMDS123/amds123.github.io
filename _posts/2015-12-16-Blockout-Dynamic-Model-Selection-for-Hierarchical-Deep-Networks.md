---
layout: post
title: "Blockout: Dynamic Model Selection for Hierarchical Deep Networks"
date: 2015-12-16 16:58:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization Image_Classification Classification
author: Calvin Murdock, Zhen Li, Howard Zhou, Tom Duerig
mathjax: true
---

* content
{:toc}

##### Abstract
Most deep architectures for image classification--even those that are trained to classify a large number of diverse categories--learn shared image representations with a single model. Intuitively, however, categories that are more similar should share more information than those that are very different. While hierarchical deep networks address this problem by learning separate features for subsets of related categories, current implementations require simplified models using fixed architectures specified via heuristic clustering methods. Instead, we propose Blockout, a method for regularization and model selection that simultaneously learns both the model architecture and parameters. A generalization of Dropout, our approach gives a novel parametrization of hierarchical architectures that allows for structure learning via back-propagation. To demonstrate its utility, we evaluate Blockout on the CIFAR and ImageNet datasets, demonstrating improved classification accuracy, better regularization performance, faster training, and the clear emergence of hierarchical network structures.

##### Abstract (translated by Google)
大多数深度图像分类体系结构 - 即使是那些经过训练以分类大量不同类别的体系结构 - 都可以通过单一模型学习共享图像表示。然而直觉上，更类似的类别应该比那些非常不同的类别分享更多的信息。虽然分层深度网络通过学习相关类别的子集的单独特征来解决这个问题，但是当前的实现需要使用通过启发式聚类方法指定的固定体系结构的简化模型。相反，我们提出阻塞，一种正则化和模型选择的方法，同时学习模型的体系结构和参数。 Dropout的推广，我们的方法提供了一个新的层次体系结构的参数化，允许结构学习通过反向传播。为了展示它的实用性，我们在CIFAR和ImageNet数据集上评估了Blockout，证明了改进的分类准确性，更好的正则化性能，更快的训练以及层次网络结构的明显出现。

##### URL
[https://arxiv.org/abs/1512.05246](https://arxiv.org/abs/1512.05246)

##### PDF
[https://arxiv.org/pdf/1512.05246](https://arxiv.org/pdf/1512.05246)

