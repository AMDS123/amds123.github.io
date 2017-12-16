---
layout: post
title: "Semantic Autoencoder for Zero-Shot Learning"
date: 2017-04-26 20:45:53
categories: arXiv_CV
tags: arXiv_CV Embedding Classification Prediction
author: Elyor Kodirov, Tao Xiang, Shaogang Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Existing zero-shot learning (ZSL) models typically learn a projection function from a feature space to a semantic embedding space (e.g.~attribute space). However, such a projection function is only concerned with predicting the training seen class semantic representation (e.g.~attribute prediction) or classification. When applied to test data, which in the context of ZSL contains different (unseen) classes without training data, a ZSL model typically suffers from the project domain shift problem. In this work, we present a novel solution to ZSL based on learning a Semantic AutoEncoder (SAE). Taking the encoder-decoder paradigm, an encoder aims to project a visual feature vector into the semantic space as in the existing ZSL models. However, the decoder exerts an additional constraint, that is, the projection/code must be able to reconstruct the original visual feature. We show that with this additional reconstruction constraint, the learned projection function from the seen classes is able to generalise better to the new unseen classes. Importantly, the encoder and decoder are linear and symmetric which enable us to develop an extremely efficient learning algorithm. Extensive experiments on six benchmark datasets demonstrate that the proposed SAE outperforms significantly the existing ZSL models with the additional benefit of lower computational cost. Furthermore, when the SAE is applied to supervised clustering problem, it also beats the state-of-the-art.

##### Abstract (translated by Google)
现有的零点学习（ZSL）模型通常学习从特征空间到语义嵌入空间（例如〜属性空间）的投影函数。然而，这样的投影函数只涉及预测训练见过的类语义表示（例如〜属性预测）或分类。当应用于测试数据时，在ZSL上下文中包含不具有训练数据的不可见（不可见）类别时，ZSL模型通常会遇到项目域转移问题。在这项工作中，我们提出了一个基于学习语义自动编码器（SAE）的ZSL新颖的解决方案。以编码器 - 解码器范例为例，编码器旨在将视觉特征向量投影到语义空间中，如同现有的ZSL模型。然而，解码器施加了额外的约束，即投影/代码必须能够重建原始视觉特征。我们表明，有了这个额外的重建约束，从所看到的类的学习投影函数能够更好地推广到新的看不见的类。重要的是，编码器和解码器是线性和对称的，使我们能够开发一个非常有效的学习算法。对六个基准数据集进行的大量实验表明，所提出的SAE比现有的ZSL模型显着优于另外的计算成本。此外，当SAE应用于监督聚类问题时，它也击败了最先进的技术。

##### URL
[https://arxiv.org/abs/1704.08345](https://arxiv.org/abs/1704.08345)

##### PDF
[https://arxiv.org/pdf/1704.08345](https://arxiv.org/pdf/1704.08345)

