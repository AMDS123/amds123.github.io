---
layout: post
title: "Solving Fourier ptychographic imaging problems via neural network modeling and TensorFlow"
date: 2018-03-09 09:38:32
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Shaowei Jiang, Kaikai Guo, Jun Liao, Guoan Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Fourier ptychography is a recently developed imaging approach for large field-of-view and high-resolution microscopy. Here we model the Fourier ptychographic forward imaging process using a convolution neural network (CNN) and recover the complex object information in the network training process. In this approach, the input of the network is the point spread function in the spatial domain or the coherent transfer function in the Fourier domain. The object is treated as 2D learnable weights of a convolution or a multiplication layer. The output of the network is modeled as the loss function we aim to minimize. The batch size of the network corresponds to the number of captured low-resolution images in one forward / backward pass. We use a popular open-source machine learning library, TensorFlow, for setting up the network and conducting the optimization process. We analyze the performance of different learning rates, different solvers, and different batch sizes. It is shown that a large batch size with the Adam optimizer achieves the best performance in general. To accelerate the phase retrieval process, we also discuss a strategy to implement Fourier-magnitude projection using a multiplication neural network model. Since convolution and multiplication are the two most-common operations in imaging modeling, the reported approach may provide a new perspective to examine many coherent and incoherent systems. As a demonstration, we discuss the extensions of the reported networks for modeling single-pixel imaging and structured illumination microscopy (SIM). 4-frame resolution doubling is demonstrated using a neural network for SIM. We have made our implementation code open-source for the broad research community.

##### Abstract (translated by Google)
傅里叶心电图是最近开发的一种用于大视场和高分辨率显微镜的成像方法。在这里，我们使用卷积神经网络（CNN）对傅立叶前向成像过程进行建模，并在网络训练过程中恢复复杂的对象信息。在这种方法中，网络的输入是空间域中的点扩展函数或傅立叶域中的相干传递函数。该对象被视为卷积或乘法层的2D可学习权重。网络的输出建模为我们旨在最小化的损失函数。网络的批量大小对应于一次前进/后退过程中捕获的低分辨率图像的数量。我们使用流行的开源机器学习库TensorFlow来设置网络并执行优化过程。我们分析不同学习率，不同求解器和不同批次的性能。结果表明，使用Adam优化器的大批量处理能力总体上达到了最佳性能。为了加速阶段检索过程，我们还讨论了使用乘法神经网络模型实现傅里叶量级投影的策略。由于卷积和倍增是成像建模中最常见的两种操作，所报告的方法可能为检查许多相干和不连贯的系统提供了新的视角。作为演示，我们讨论了用于建模单像素成像和结构化照明显微镜（SIM）的已报告网络的扩展。使用SIM的神经网络来演示4帧分辨率加倍。我们已经为广泛的研究团体制定了实施代码开放源代码。

##### URL
[http://arxiv.org/abs/1803.03434](http://arxiv.org/abs/1803.03434)

##### PDF
[http://arxiv.org/pdf/1803.03434](http://arxiv.org/pdf/1803.03434)

