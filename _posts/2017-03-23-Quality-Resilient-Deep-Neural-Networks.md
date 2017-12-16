---
layout: post
title: "Quality Resilient Deep Neural Networks"
date: 2017-03-23 15:56:33
categories: arXiv_CV
tags: arXiv_CV Classification
author: Samuel Dodge, Lina Karam
mathjax: true
---

* content
{:toc}

##### Abstract
We study deep neural networks for classification of images with quality distortions. We first show that networks fine-tuned on distorted data greatly outperform the original networks when tested on distorted data. However, fine-tuned networks perform poorly on quality distortions that they have not been trained for. We propose a mixture of experts ensemble method that is robust to different types of distortions. The "experts" in our model are trained on a particular type of distortion. The output of the model is a weighted sum of the expert models, where the weights are determined by a separate gating network. The gating network is trained to predict optimal weights for a particular distortion type and level. During testing, the network is blind to the distortion level and type, yet can still assign appropriate weights to the expert models. We additionally investigate weight sharing methods for the mixture model and show that improved performance can be achieved with a large reduction in the number of unique network parameters.

##### Abstract (translated by Google)
我们研究深度神经网络的质量失真图像分类。我们首先表明，在对失真数据进行测试时，对失真数据进行微调的网络性能大大优于原始网络。然而，微调的网络在质量失真方面表现不佳，而他们还没有接受过培训。我们提出了一种对不同类型的扭曲具有鲁棒性的专家集成方法的混合。我们模型中的“专家”是针对特定类型的失真进行训练的。模型的输出是专家模型的加权总和，其中权重由单独的门控网络确定。门控网络被训练来预测特定失真类型和水平的最佳权重。在测试过程中，网络对失真水平和类型一目了然，但仍然可以为专家模型分配适当的权重。我们另外调查了混合模型的权重共享方法，并且显示通过大量减少独特网络参数的数量可以实现改进的性能。

##### URL
[https://arxiv.org/abs/1703.08119](https://arxiv.org/abs/1703.08119)

##### PDF
[https://arxiv.org/pdf/1703.08119](https://arxiv.org/pdf/1703.08119)

