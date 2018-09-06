---
layout: post
title: "BinaryRelax: A Relaxation Approach For Training Deep Neural Networks With Quantized Weights"
date: 2018-09-05 00:01:37
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Penghang Yin, Shuai Zhang, Jiancheng Lyu, Stanley Osher, Yingyong Qi, Jack Xin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose BinaryRelax, a simple two-phase algorithm, for training deep neural networks with quantized weights. The set constraint that characterizes the quantization of weights is not imposed until the late stage of training, and a sequence of \emph{pseudo} quantized weights is maintained. Specifically, we relax the hard constraint into a continuous regularizer via Moreau envelope, which turns out to be the squared Euclidean distance to the set of quantized weights. The pseudo quantized weights are obtained by linearly interpolating between the float weights and their quantizations. A continuation strategy is adopted to push the weights towards the quantized state by gradually increasing the regularization parameter. In the second phase, exact quantization scheme with a small learning rate is invoked to guarantee fully quantized weights. We test BinaryRelax on the benchmark CIFAR and ImageNet color image datasets to demonstrate the superiority of the relaxed quantization approach and the improved accuracy over the state-of-the-art training methods. Finally, we prove the convergence of BinaryRelax under an approximate orthogonality condition.

##### Abstract (translated by Google)
我们提出BinaryRelax，一种简单的两阶段算法，用于训练具有量化权重的深度神经网络。表征权重量化的集合约束直到训练的后期才被施加，并且保持一系列\ emph {伪}量化权重。具体来说，我们通过Moreau包络将硬约束放宽为连续正则化器，结果证明是与量化权重集的平方欧几里德距离。通过在浮动权重和它们的量化之间进行线性内插来获得伪量化权重。采用连续策略通过逐渐增加正则化参数将权重推向量化状态。在第二阶段，调用具有小学习速率的精确量化方案以保证完全量化的权重。我们在基准CIFAR和ImageNet彩色图像数据集上测试BinaryRelax，以展示宽松量化方法的优越性以及与最先进的训练方法相比提高的准确性。最后，我们证明了BinaryRelax在近似正交条件下的收敛性。

##### URL
[http://arxiv.org/abs/1801.06313](http://arxiv.org/abs/1801.06313)

##### PDF
[http://arxiv.org/pdf/1801.06313](http://arxiv.org/pdf/1801.06313)

