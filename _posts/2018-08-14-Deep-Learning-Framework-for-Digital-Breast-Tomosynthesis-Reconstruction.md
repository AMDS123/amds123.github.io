---
layout: post
title: "Deep Learning Framework for Digital Breast Tomosynthesis Reconstruction"
date: 2018-08-14 11:41:32
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Deep_Learning
author: Nikita Moriakov, Koen Michielsen, Jonas Adler, Ritse Mann, Ioannis Sechopoulos, Jonas Teuwen
mathjax: true
---

* content
{:toc}

##### Abstract
Digital breast tomosynthesis is rapidly replacing digital mammography as the basic x-ray technique for evaluation of the breasts. However, the sparse sampling and limited angular range gives rise to different artifacts, which manufacturers try to solve in several ways. In this study we propose an extension of the Learned Primal-Dual algorithm for digital breast tomosynthesis. The Learned Primal-Dual algorithm is a deep neural network consisting of several `reconstruction blocks', which take in raw sinogram data as the initial input, perform a forward and a backward pass by taking projections and back-projections, and use a convolutional neural network to produce an intermediate reconstruction result which is then improved further by the successive reconstruction block. We extend the architecture by providing breast thickness measurements as a mask to the neural network and allow it to learn how to use this thickness mask. We have trained the algorithm on digital phantoms and the corresponding noise-free/noisy projections, and then tested the algorithm on digital phantoms for varying level of noise. Reconstruction performance of the algorithms was compared visually, using MSE loss and Structural Similarity Index. Results indicate that the proposed algorithm outperforms the baseline iterative reconstruction algorithm in terms of reconstruction quality for both breast edges and internal structures and is robust to noise.

##### Abstract (translated by Google)
数字乳房断层合成正在迅速取代数字乳房X射线摄影术，作为评估乳房的基本X射线技术。然而，稀疏采样和有限的角度范围产生了不同的伪像，制造商试图以多种方式解决这些伪影。在这项研究中，我们提出了用于数字乳房断层合成的Learned Primal-Dual算法的扩展。 Learned Primal-Dual算法是一个由几个“重建块”组成的深度神经网络，它将原始正弦图数据作为初始输入，通过采用投影和反投影执行前向和后向传递，并使用卷积神经网络产生中间重建结果，然后通过连续重建块进一步改进。我们通过提供乳房厚度测量作为神经网络的掩模来扩展架构，并允许它学习如何使用这个厚度掩模。我们已经在数字模型和相应的无噪声/噪声投影上训练了算法，然后在数字模型上测试了不同噪声水平的算法。使用MSE损失和结构相似性指数在视觉上比较算法的重建性能。结果表明，该算法在乳房边缘和内部结构的重建质量方面优于基线迭代重建算法，并且对噪声具有鲁棒性。

##### URL
[http://arxiv.org/abs/1808.04640](http://arxiv.org/abs/1808.04640)

##### PDF
[http://arxiv.org/pdf/1808.04640](http://arxiv.org/pdf/1808.04640)

