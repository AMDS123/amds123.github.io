---
layout: post
title: "Blended Coarse Gradient Descent for Full Quantization of Deep Neural Networks"
date: 2018-08-15 18:13:12
categories: arXiv_CV
tags: arXiv_CV Inference Classification Gradient_Descent
author: Penghang Yin, Shuai Zhang, Jiancheng Lyu, Stanley Osher, Yingyong Qi, Jack Xin
mathjax: true
---

* content
{:toc}

##### Abstract
Quantized deep neural networks (QDNNs) are attractive due to their much lower memory storage and faster inference speed than their regular full precision counterparts. To maintain the same performance level especially at low bit-widths, QDNNs must be retrained. Their training involves piecewise constant activation functions and discrete weights, hence mathematical challenges arise. We introduce the notion of coarse derivative and propose the blended coarse gradient descent (BCGD) algorithm, for training fully quantized neural networks. Coarse gradient is generally not a gradient of any function but an artificial descent direction. The weight update of BCGD goes by coarse gradient correction of a weighted average of the full precision weights and their quantization (the so-called blending), which yields sufficient descent in the objective value and thus accelerates the training. Our experiments demonstrate that this simple blending technique is very effective for quantization at extremely low bit-width such as binarization. In full quantization of ResNet-18 for ImageNet classification task, BCGD gives 64.36% top-1 accuracy with binary weights across all layers and 4-bit adaptive activation. If the weights in the first and last layers are kept in full precision, this number increases to 65.46%. As theoretical justification, we provide the convergence analysis of coarse gradient descent for a two-layer neural network model with Gaussian input data, and prove that the expected coarse gradient correlates positively with the underlying true gradient.

##### Abstract (translated by Google)
量化深度神经网络（QDNN）由于其比常规全精度对应物更低的存储容量和更快的推理速度而具有吸引力。为了保持相同的性能水平，特别是在低位宽时，必须重新训练QDNN。他们的训练涉及分段恒定激活函数和离散权重，因此产生了数学挑战。我们引入粗导数的概念，并提出混合粗梯度下降（BCGD）算法，用于训练全量子化神经网络。粗梯度通常不是任何函数的梯度，而是人工下降方向。 BCGD的权重更新通过粗略梯度校正全精度权重的加权平均值及其量化（所谓的混合），其产生目标值的充分下降并因此加速训练。我们的实验证明，这种简单的混合技术对于极低位宽（例如二值化）的量化非常有效。在用于ImageNet分类任务的ResNet-18的完全量化中，BCGD提供64.36％的前1精度，所有层的二进制权重和4位自​​适应激活。如果第一层和最后一层中的权重保持完全精确，则该数字增加到65.46％。作为理论证明，我们提供了具有高斯输入数据的双层神经网络模型的粗梯度下降的收敛性分析，并证明了预期的粗梯度与下面的真实梯度正相关。

##### URL
[http://arxiv.org/abs/1808.05240](http://arxiv.org/abs/1808.05240)

##### PDF
[http://arxiv.org/pdf/1808.05240](http://arxiv.org/pdf/1808.05240)

