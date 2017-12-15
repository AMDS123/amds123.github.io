---
layout: post
title: "Particular object retrieval with integral max-pooling of CNN activations"
date: 2016-02-24 15:14:34
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Recognition
author: Giorgos Tolias, Ronan Sicre, Hervé Jégou
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, image representation built upon Convolutional Neural Network (CNN) has been shown to provide effective descriptors for image search, outperforming pre-CNN features as short-vector representations. Yet such models are not compatible with geometry-aware re-ranking methods and still outperformed, on some particular object retrieval benchmarks, by traditional image search systems relying on precise descriptor matching, geometric re-ranking, or query expansion. This work revisits both retrieval stages, namely initial search and re-ranking, by employing the same primitive information derived from the CNN. We build compact feature vectors that encode several image regions without the need to feed multiple inputs to the network. Furthermore, we extend integral images to handle max-pooling on convolutional layer activations, allowing us to efficiently localize matching objects. The resulting bounding box is finally used for image re-ranking. As a result, this paper significantly improves existing CNN-based recognition pipeline: We report for the first time results competing with traditional methods on the challenging Oxford5k and Paris6k datasets.

##### Abstract (translated by Google)
近来，基于卷积神经网络（CNN）的图像表示已被证明为图像搜索提供了有效的描述符，比CNN前的特征作为短矢量表示更好。然而，这样的模型与几何意识重排方法不兼容，并且依赖于精确的描述符匹配，几何重排序或查询扩展的传统图像搜索系统在一些特定的对象检索基准上仍然表现优异。这项工作重新审视两个检索阶段，即初始搜索和重新排序，采用从CNN派生的相同的原始信息。我们构建了紧凑的特征向量，可以编码多个图像区域，而无需向网络输入多个输入。此外，我们扩展积分图像，以处理卷积层激活的最大池，使我们能够有效地定位匹配对象。最终的边界框最终用于图像重新排序。因此，本文对现有的基于CNN的识别流程进行了重大的改进：我们首次报告了在具有挑战性的Oxford5k和Paris6k数据集上与传统方法竞争的结果。

##### URL
[https://arxiv.org/abs/1511.05879](https://arxiv.org/abs/1511.05879)

##### PDF
[https://arxiv.org/pdf/1511.05879](https://arxiv.org/pdf/1511.05879)

