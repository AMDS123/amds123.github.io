---
layout: post
title: "Learning a Variational Network for Reconstruction of Accelerated MRI Data"
date: 2017-04-03 06:49:46
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Gradient_Descent
author: Kerstin Hammernik, Teresa Klatzer, Erich Kobler, Michael P Recht, Daniel K Sodickson, Thomas Pock, Florian Knoll
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: To allow fast and high-quality reconstruction of clinical accelerated multi-coil MR data by learning a variational network that combines the mathematical structure of variational models with deep learning. Theory and Methods: Generalized compressed sensing reconstruction formulated as a variational model is embedded in an unrolled gradient descent scheme. All parameters of this formulation, including the prior model defined by filter kernels and activation functions as well as the data term weights, are learned during an offline training procedure. The learned model can then be applied online to previously unseen data. Results: The variational network approach is evaluated on a clinical knee imaging protocol. The variational network reconstructions outperform standard reconstruction algorithms in terms of image quality and residual artifacts for all tested acceleration factors and sampling patterns. Conclusion: Variational network reconstructions preserve the natural appearance of MR images as well as pathologies that were not included in the training data set. Due to its high computational performance, i.e., reconstruction time of 193 ms on a single graphics card, and the omission of parameter tuning once the network is trained, this new approach to image reconstruction can easily be integrated into clinical workflow.

##### Abstract (translated by Google)
目的：通过学习将变分模型的数学结构与深度学习相结合的变分网络，实现临床加速多线圈MR数据的快速和高质量重建。理论和方法：将广义压缩感知重构公式化为一个变分模型嵌入到一个展开的梯度下降方案中。在离线训练过程中学习此公式的所有参数（包括由滤波器内核定义的先验模型和激活函数以及数据项权重）。然后可以将学习的模型在线应用于先前未见的数据。结果：在临床膝关节成像协议上评估变分网络方法。对于所有测试的加速因子和采样模式，变换网络重建在图像质量和残留伪像方面优于标准重建算法。结论：变分网络重建保留了MR图像的自然外观以及未包含在训练数据集中的病理。由于其高计算性能，即在单个显卡上重建时间为193ms，并且一旦网络被训练就省略了参数调整，这种新的图像重建方法可以很容易地集成到临床工作流程中。

##### URL
[https://arxiv.org/abs/1704.00447](https://arxiv.org/abs/1704.00447)

##### PDF
[https://arxiv.org/pdf/1704.00447](https://arxiv.org/pdf/1704.00447)

