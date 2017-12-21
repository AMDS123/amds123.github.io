---
layout: post
title: "Block-diagonal Hessian-free Optimization for Training Neural Networks"
date: 2017-12-20 02:52:35
categories: arXiv_AI
tags: arXiv_AI CNN Optimization RNN Deep_Learning Gradient_Descent
author: Huishuai Zhang, Caiming Xiong, James Bradbury, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Second-order methods for neural network optimization have several advantages over methods based on first-order gradient descent, including better scaling to large mini-batch sizes and fewer updates needed for convergence. But they are rarely applied to deep learning in practice because of high computational cost and the need for model-dependent algorithmic variations. We introduce a variant of the Hessian-free method that leverages a block-diagonal approximation of the generalized Gauss-Newton matrix. Our method computes the curvature approximation matrix only for pairs of parameters from the same layer or block of the neural network and performs conjugate gradient updates independently for each block. Experiments on deep autoencoders, deep convolutional networks, and multilayer LSTMs demonstrate better convergence and generalization compared to the original Hessian-free approach and the Adam method.

##### Abstract (translated by Google)
用于神经网络优化的二阶方法相对于基于一阶梯度下降的方法具有几个优点，包括更好地缩放到大批量小批量和更少收敛所需的更新。但是由于高计算成本和模型相关算法变化的需要，它们很少应用于实践中的深度学习。我们介绍一种利用广义高斯 - 牛顿矩阵的块对角线近似的无Hessian方法的变体。我们的方法仅计算来自神经网络的相同层或块的参数对的曲率近似矩阵，并且针对每个块独立地执行共轭梯度更新。深度自编码器，深度卷积网络和多层LSTMs的实验表明，与原始的无Hessian方法和Adam方法相比，它更好地收敛和泛化。

##### URL
[http://arxiv.org/abs/1712.07296](http://arxiv.org/abs/1712.07296)

##### PDF
[http://arxiv.org/pdf/1712.07296](http://arxiv.org/pdf/1712.07296)

