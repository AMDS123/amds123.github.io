---
layout: post
title: "Improving Generalization via Scalable Neighborhood Component Analysis"
date: 2018-08-14 14:03:47
categories: arXiv_CV
tags: arXiv_CV Embedding Classification Recognition
author: Zhirong Wu, Alexei A. Efros, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Current major approaches to visual recognition follow an end-to-end formulation that classifies an input image into one of the pre-determined set of semantic categories. Parametric softmax classifiers are a common choice for such a closed world with fixed categories, especially when big labeled data is available during training. However, this becomes problematic for open-set scenarios where new categories are encountered with very few examples for learning a generalizable parametric classifier. We adopt a non-parametric approach for visual recognition by optimizing feature embeddings instead of parametric classifiers. We use a deep neural network to learn the visual feature that preserves the neighborhood structure in the semantic space, based on the Neighborhood Component Analysis (NCA) criterion. Limited by its computational bottlenecks, we devise a mechanism to use augmented memory to scale NCA for large datasets and very deep networks. Our experiments deliver not only remarkable performance on ImageNet classification for such a simple non-parametric method, but most importantly a more generalizable feature representation for sub-category discovery and few-shot recognition.

##### Abstract (translated by Google)
当前用于视觉识别的主要方法遵循端到端的公式，其将输入图像分类为预定的一组语义类别中的一个。参数softmax分类器是具有固定类别的封闭世界的常见选择，尤其是在训练期间可获得大标记数据时。然而，对于开放式场景而言，这会成为问题，其中遇到了用于学习可推广的参​​数分类器的非常少的示例的新类别。我们通过优化特征嵌入而不是参数分类器，采用非参数方法进行视觉识别。我们使用深度神经网络来学习基于邻域分量分析（NCA）标准保留语义空间中邻域结构的视觉特征。受其计算瓶颈的限制，我们设计了一种机制，使用增强内存来扩展大型数据集和非常深的网络的NCA。我们的实验不仅为这种简单的非参数方法提供了ImageNet分类的卓越性能，而且最重要的是为子类别发现和小镜头识别提供了更具概括性的特征表示。

##### URL
[http://arxiv.org/abs/1808.04699](http://arxiv.org/abs/1808.04699)

##### PDF
[http://arxiv.org/pdf/1808.04699](http://arxiv.org/pdf/1808.04699)

