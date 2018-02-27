---
layout: post
title: "Sensitivity and Generalization in Neural Networks: an Empirical Study"
date: 2018-02-23 23:11:07
categories: arXiv_AI
tags: arXiv_AI Survey Image_Classification Classification
author: Roman Novak, Yasaman Bahri, Daniel A. Abolafia, Jeffrey Pennington, Jascha Sohl-Dickstein
mathjax: true
---

* content
{:toc}

##### Abstract
In practice it is often found that large over-parameterized neural networks generalize better than their smaller counterparts, an observation that appears to conflict with classical notions of function complexity, which typically favor smaller models. In this work, we investigate this tension between complexity and generalization through an extensive empirical exploration of two natural metrics of complexity related to sensitivity to input perturbations. Our experiments survey thousands of models with various fully-connected architectures, optimizers, and other hyper-parameters, as well as four different image classification datasets. 
 We find that trained neural networks are more robust to input perturbations in the vicinity of the training data manifold, as measured by the norm of the input-output Jacobian of the network, and that it correlates well with generalization. We further establish that factors associated with poor generalization $-$ such as full-batch training or using random labels $-$ correspond to lower robustness, while factors associated with good generalization $-$ such as data augmentation and ReLU non-linearities $-$ give rise to more robust functions. Finally, we demonstrate how the input-output Jacobian norm can be predictive of generalization at the level of individual test points.

##### Abstract (translated by Google)
在实践中，经常发现大型超参数化神经网络比其小型对等体更好地推广，这一观察结果似乎与经典的函数复杂性概念相冲突，这一概念通常支持较小的模型。在这项工作中，我们通过对与输入扰动敏感度有关的复杂性的两个自然度量进行了广泛的实证研究，调查了复杂度与泛化之间的这种张力。我们的实验使用各种完全连接的体系结构，优化器和其他超参数以及四个不同的图像分类数据集对数千个模型进行了调查。
 我们发现，经过训练的神经网络对训练数据流形附近的输入扰动更加鲁棒，正如网络输入输出雅可比行列式所测量的那样，并且它与广义相关性很好。我们进一步确定与不良泛化$  -  $相关的因素，如全批次培训或使用随机标签$  -  $对应较低的健壮性，而与良好泛化相关的因素$  -  $如数据增强和ReLU非线性$  - $引起更强大的功能。最后，我们演示输入输出雅可比行列式如何在单个测试点的层次上预测泛化。

##### URL
[http://arxiv.org/abs/1802.08760](http://arxiv.org/abs/1802.08760)

##### PDF
[http://arxiv.org/pdf/1802.08760](http://arxiv.org/pdf/1802.08760)

