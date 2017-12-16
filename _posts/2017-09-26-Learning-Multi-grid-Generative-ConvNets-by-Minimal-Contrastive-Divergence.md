---
layout: post
title: "Learning Multi-grid Generative ConvNets by Minimal Contrastive Divergence"
date: 2017-09-26 07:48:52
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ruiqi Gao, Yang Lu, Junpei Zhou, Song-Chun Zhu, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a minimal contrastive divergence method for learning energy-based generative ConvNet models of images at multiple grids (or scales) simultaneously. For each grid, we learn an energy-based probabilistic model where the energy function is defined by a bottom-up convolutional neural network (ConvNet or CNN). Learning such a model requires generating synthesized examples from the model. Within each iteration of our learning algorithm, for each observed training image, we generate synthesized images at multiple grids by initializing the finite-step MCMC sampling from a minimal 1 x 1 version of the training image. The synthesized image at each subsequent grid is obtained by a finite-step MCMC initialized from the synthesized image generated at the previous coarser grid. After obtaining the synthesized examples, the parameters of the models at multiple grids are updated separately and simultaneously based on the differences between synthesized and observed examples. We call this learning method the multi-grid minimal contrastive divergence. We show that this method can learn realistic energy-based generative ConvNet models, and it outperforms the original contrastive divergence (CD) and persistent CD.

##### Abstract (translated by Google)
本文提出了一种基于能量的多重网格（或尺度）生成ConvNet模型的最小对比散度方法。对于每个网格，我们学习一个基于能量的概率模型，其中能量函数由自下而上的卷积神经网络（ConvNet或CNN）定义。学习这样的模型需要从模型中生成合成的例子。在我们的学习算法的每次迭代中，对于每个观察到的训练图像，我们通过从训练图像的最小1×1版本初始化有限步MCMC采样来在多个网格上生成合成图像。在每个后续网格处的合成图像通过从在先粗糙网格处生成的合成图像初始化的有限步MCMC获得。在获得合成实例后，根据合成和观察实例之间的差异，分别同时更新多个网格处的模型的参数。我们称这种学习方法为多重网格最小对比分歧。我们表明，这种方法可以学习现实的基于能量的生成ConvNet模型，它优于原始的对比分歧（CD）和持久性CD。

##### URL
[https://arxiv.org/abs/1709.08868](https://arxiv.org/abs/1709.08868)

##### PDF
[https://arxiv.org/pdf/1709.08868](https://arxiv.org/pdf/1709.08868)

