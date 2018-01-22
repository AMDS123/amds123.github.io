---
layout: post
title: "BinaryRelax: A Relaxation Approach For Training Deep Neural Networks With Quantized Weights"
date: 2018-01-19 06:35:23
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Penghang Yin, Shuai Zhang, Jiancheng Lyu, Stanley Osher, Yingyong Qi, Jack Xin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose BinaryRelax, a simple two-phase algorithm, for training deep neural networks with quantized weights. The set constraint that characterizes the quantization of weights is not imposed until the late stage of training, and a sequence of pseudo quantized weights is maintained. Specifically, we relax the hard constraint into a continuous regularizer via Moreau envelope, which turns out to be the squared Euclidean distance to the set of quantized weights. The pseudo quantized weights are obtained by linearly interpolating between the float weights and their quantizations. A continuation strategy is adopted to push the weights towards the quantized state by gradually increasing the regularization parameter. In the second phase, exact quantization scheme with a small learning rate is invoked to guarantee fully quantized weights. We test BinaryRelax on the benchmark CIFAR-10 and CIFAR-100 color image datasets to demonstrate the superiority of the relaxed quantization approach and the improved accuracy over the state-of-the-art training methods. Finally, we prove the convergence of BinaryRelax under an approximate orthogonality condition.

##### Abstract (translated by Google)
我们提出了一种简单的双相算法BinaryRelax，用于训练具有量化权重的深度神经网络。表征权重量化的集合约束直到训练的后期阶段才被施加，并且维持伪量化权重的序列。具体来说，我们通过Moreau包络将硬约束放松到一个连续正规化子中，这就是量子化权重集的欧氏距离的平方。伪量化权重是通过浮点权重和它们的量化之间的线性内插获得的。通过逐渐增加正则化参数，采用延拓策略将权重推向量化状态。在第二阶段中，调用具有小学习率的精确量化方案以保证完全量化的权重。我们在基准CIFAR-10和CIFAR-100彩色图像数据集上测试BinaryRelax，以证明宽松量化方法的优越性以及相对于最先进的训练方法而言提高的准确性。最后，证明了在近似正交条件下BinaryRelax的收敛性。

##### URL
[http://arxiv.org/abs/1801.06313](http://arxiv.org/abs/1801.06313)

##### PDF
[http://arxiv.org/pdf/1801.06313](http://arxiv.org/pdf/1801.06313)

