---
layout: post
title: "ADAM-ADMM: A Unified, Systematic Framework of Structured Weight Pruning for DNNs"
date: 2018-07-29 18:07:04
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Gradient_Descent
author: Tianyun Zhang, Kaiqi Zhang, Shaokai Ye, Jiayu Li, Jian Tang, Wujie Wen, Xue Lin, Makan Fardad, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Weight pruning methods of deep neural networks (DNNs) have been demonstrated to achieve a good model pruning ratio without loss of accuracy, thereby alleviating the significant computation/storage requirements of large-scale DNNs. Structured weight pruning methods have been proposed to overcome the limitation of irregular network structure and demonstrated actual GPU acceleration. However, the pruning ratio (degree of sparsity) and GPU acceleration are limited (to less than 50%) when accuracy needs to be maintained. 
 In this work, we overcome pruning ratio and GPU acceleration limitations by proposing a unified, systematic framework of structured weight pruning for DNNs, named ADAM-ADMM (Adaptive Moment Estimation-Alternating Direction Method of Multipliers). It is a framework that can be used to induce different types of structured sparsity, such as filter-wise, channel-wise, and shape-wise sparsity, as well non-structured sparsity. The proposed framework incorporates stochastic gradient descent with ADMM, and can be understood as a dynamic regularization method in which the regularization target is analytically updated in each iteration. A significant improvement in weight pruning ratio is achieved without loss of accuracy, along with fast convergence rate. With a small sparsity degree of 33% on the convolutional layers, we achieve 1.64% accuracy enhancement for the AlexNet (CaffeNet) model. This is obtained by mitigation of overfitting. Without loss of accuracy on the AlexNet model, we achieve 2.6 times and 3.65 times average measured speedup on two GPUs, clearly outperforming the prior work. The average speedups reach 2.77 times and 7.5 times when allowing a moderate accuracy loss of 2%. In this case the model compression for convolutional layers is 13.2 times, corresponding to 10.5 times CPU speedup. Our models and codes are released at https://github.com/KaiqiZhang/ADAM-ADMM

##### Abstract (translated by Google)
已经证明深度神经网络（DNN）的重量修剪方法在不损失精度的情况下实现良好的模型修剪比率，从而减轻了大规模DNN的显着计算/存储要求。已经提出结构化重量修剪方法来克服不规则网络结构的限制并且证明了实际的GPU加速。然而，当需要保持精度时，修剪比（稀疏程度）和GPU加速度受到限制（小于50％）。
 在这项工作中，我们通过提出DNN的结构化权重修剪的统一，系统框架，称为ADAM-ADMM（自适应矩估计 - 乘法的交替方向方法），克服了修剪比和GPU加速限制。它是一个框架，可用于诱导不同类型的结构化稀疏性，如过滤方式，通道方式和形状方式稀疏性，以及非结构化稀疏性。所提出的框架将随机梯度下降与ADMM结合，并且可以被理解为动态正则化方法，其中在每次迭代中分析地更新正则化目标。在不损失精度的情况下实现了重量修剪比的显着改善，以及快速的收敛速度。在卷积层上具有33％的小稀疏度，我们为AlexNet（CaffeNet）模型实现了1.64％的准确度增强。这是通过减轻过度拟合而获得的。在不损失AlexNet模型的准确性的情况下，我们在两个GPU上实现了2.6倍和3.65倍的平均测量加速，明显优于之前的工作。当允许2％的中等精度损失时，平均加速达到2.77倍和7.5倍。在这种情况下，卷积层的模型压缩是13.2次，相当于CPU加速的10.5倍。我们的模型和代码发布在https://github.com/KaiqiZhang/ADAM-ADMM

##### URL
[http://arxiv.org/abs/1807.11091](http://arxiv.org/abs/1807.11091)

##### PDF
[http://arxiv.org/pdf/1807.11091](http://arxiv.org/pdf/1807.11091)

