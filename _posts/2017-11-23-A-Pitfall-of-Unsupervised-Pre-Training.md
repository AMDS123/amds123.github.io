---
layout: post
title: "A Pitfall of Unsupervised Pre-Training"
date: 2017-11-23 14:54:18
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Relation
author: Michele Alberti, Mathias Seuret, Rolf Ingold, Marcus Liwicki
mathjax: true
---

* content
{:toc}

##### Abstract
The point of this paper is to question typical assumptions in deep learning and suggest alternatives. A particular contribution is to prove that even if a Stacked Convolutional Auto-Encoder is good at reconstructing pictures, it is not necessarily good at discriminating their classes. When using Auto-Encoders, intuitively one assumes that features which are good for reconstruction will also lead to high classification accuracy. Indeed, it became research practice and is a suggested strategy by introductory books. However, we prove that this is not always the case. We thoroughly investigate the quality of features produced by Stacked Convolutional Auto-Encoders when trained to reconstruct their input. In particular, we analyze the relation between the reconstruction and classification capabilities of the network, if we were to use the same features for both tasks. Experimental results suggest that in fact, there is no correlation between the reconstruction score and the quality of features for a classification task. This means, more formally, that the sub-dimension representation space learned from the Stacked Convolutional Auto-Encoder (while being trained for input reconstruction) is not necessarily better separable than the initial input space. Furthermore, we show that the reconstruction error is not a good metric to assess the quality of features, because it is biased by the decoder quality. We do not question the usefulness of pre-training, but we conclude that aiming for the lowest reconstruction error is not necessarily a good idea if afterwards one performs a classification task.

##### Abstract (translated by Google)
本文的重点在于对深度学习中的典型假设提出质疑，并提出替代方案。一个特别的贡献就是要证明，即使叠层卷积自动编码器擅长重构图像，它也不一定擅长区分它们的类别。当使用自动编码器时，直观地假定有利于重构的特征也将导致高的分类准确度。事实上，它变成了研究实践，并且是介绍性书籍的建议策略。但是，我们证明这并非总是如此。我们彻底研究了堆叠式卷积自动编码器在训练重构输入时产生的特征的质量。具体而言，我们分析了网络的重构和分类能力之间的关系，如果我们要为这两个任务使用相同的特征。实验结果表明，实际上，分类任务的重建分数与特征质量之间没有相关性。这意味着更正式地说，从叠层卷积自动编码器（在被输入重构训练时）学习的子维表示空间不一定比初始输入空间更好地分离。此外，我们表明，重建误差不是衡量特征质量的一个很好的指标，因为它受解码器质量的影响。我们不质疑预训练的有用性，但是我们得出结论：如果以后要执行分类任务，那么针对最低重构误差不一定是个好主意。

##### URL
[https://arxiv.org/abs/1712.01655](https://arxiv.org/abs/1712.01655)

##### PDF
[https://arxiv.org/pdf/1712.01655](https://arxiv.org/pdf/1712.01655)

