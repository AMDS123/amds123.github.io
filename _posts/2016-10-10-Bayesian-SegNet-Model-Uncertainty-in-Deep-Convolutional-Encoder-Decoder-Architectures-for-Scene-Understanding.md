---
layout: post
title: "Bayesian SegNet: Model Uncertainty in Deep Convolutional Encoder-Decoder Architectures for Scene Understanding"
date: 2016-10-10 22:04:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Deep_Learning
author: Alex Kendall, Vijay Badrinarayanan, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep learning framework for probabilistic pixel-wise semantic segmentation, which we term Bayesian SegNet. Semantic segmentation is an important tool for visual scene understanding and a meaningful measure of uncertainty is essential for decision making. Our contribution is a practical system which is able to predict pixel-wise class labels with a measure of model uncertainty. We achieve this by Monte Carlo sampling with dropout at test time to generate a posterior distribution of pixel class labels. In addition, we show that modelling uncertainty improves segmentation performance by 2-3% across a number of state of the art architectures such as SegNet, FCN and Dilation Network, with no additional parametrisation. We also observe a significant improvement in performance for smaller datasets where modelling uncertainty is more effective. We benchmark Bayesian SegNet on the indoor SUN Scene Understanding and outdoor CamVid driving scenes datasets.

##### Abstract (translated by Google)
我们提出了一个概率像素语义分割的深度学习框架，我们称为贝叶斯SegNet。语义分割是视觉场景理解的重要工具，有意义的不确定性度量对于决策制定至关重要。我们的贡献是一个实际的系统，能够预测像素级类标签与模型的不确定性的措施。我们通过在测试时间丢弃的蒙特卡罗采样来实现这一点，以生成像素类标签的后验分布。此外，我们还展示了建模的不确定性提高了SegNet，FCN和Dilation Network等众多先进架构的分段性能2-3％，而不需要额外的参数设置。对于建模不确定性更有效的较小数据集，我们还观察到性能的显着改善。我们在室内SUN场景理解和户外CamVid驾驶场景数据集上测试贝叶斯SegNet。

##### URL
[https://arxiv.org/abs/1511.02680](https://arxiv.org/abs/1511.02680)

##### PDF
[https://arxiv.org/pdf/1511.02680](https://arxiv.org/pdf/1511.02680)

