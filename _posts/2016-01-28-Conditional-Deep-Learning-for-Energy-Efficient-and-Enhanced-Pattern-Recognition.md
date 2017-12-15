---
layout: post
title: "Conditional Deep Learning for Energy-Efficient and Enhanced Pattern Recognition"
date: 2016-01-28 18:34:42
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Recognition
author: Priyadarshini Panda, Abhronil Sengupta, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning neural networks have emerged as one of the most powerful classification tools for vision related applications. However, the computational and energy requirements associated with such deep nets can be quite high, and hence their energy-efficient implementation is of great interest. Although traditionally the entire network is utilized for the recognition of all inputs, we observe that the classification difficulty varies widely across inputs in real-world datasets; only a small fraction of inputs require the full computational effort of a network, while a large majority can be classified correctly with very low effort. In this paper, we propose Conditional Deep Learning (CDL) where the convolutional layer features are used to identify the variability in the difficulty of input instances and conditionally activate the deeper layers of the network. We achieve this by cascading a linear network of output neurons for each convolutional layer and monitoring the output of the linear network to decide whether classification can be terminated at the current stage or not. The proposed methodology thus enables the network to dynamically adjust the computational effort depending upon the difficulty of the input data while maintaining competitive classification accuracy. We evaluate our approach on the MNIST dataset. Our experiments demonstrate that our proposed CDL yields 1.91x reduction in average number of operations per input, which translates to 1.84x improvement in energy. In addition, our results show an improvement in classification accuracy from 97.5% to 98.9% as compared to the original network.

##### Abstract (translated by Google)
深度学习神经网络已经成为视觉相关应用最强大的分类工具之一。然而，与这种深网络相关的计算和能量需求可能相当高，因此其节能实施具有极大的兴趣。虽然传统上整个网络被用来识别所有的输入，但是我们观察到在真实世界的数据集中输入的分类难度差异很大;只有一小部分的输入需要网络的全部计算工作，而大多数输入可以用很少的努力正确分类。在本文中，我们提出了条件深度学习（CDL），其中卷积层特征用于识别输入实例难度的可变性并有条件地激活网络的更深层。我们通过级联每个卷积层的输出神经元的线性网络并监视线性网络的输出来决定是否可以在当前阶段终止分类。所提出的方法因此使得网络能够根据输入数据的难度来动态地调整计算努力，同时保持有竞争力的分类准确度。我们在MNIST数据集上评估我们的方法。我们的实验表明，我们提出的CDL平均每个输入的操作数量减少了1.91倍，这相当于提高了1.84倍的能量。另外，与原始网络相比，我们的结果显示分类准确率从97.5％提高到98.9％。

##### URL
[https://arxiv.org/abs/1509.08971](https://arxiv.org/abs/1509.08971)

##### PDF
[https://arxiv.org/pdf/1509.08971](https://arxiv.org/pdf/1509.08971)

