---
layout: post
title: "Topology Reduction in Deep Convolutional Feature Extraction Networks"
date: 2017-07-10 06:35:48
categories: arXiv_CV
tags: arXiv_CV CNN
author: Thomas Wiatowski, Philipp Grohs, Helmut Bölcskei
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) used in practice employ potentially hundreds of layers and $10$,$000$s of nodes. Such network sizes entail significant computational complexity due to the large number of convolutions that need to be carried out; in addition, a large number of parameters needs to be learned and stored. Very deep and wide CNNs may therefore not be well suited to applications operating under severe resource constraints as is the case, e.g., in low-power embedded and mobile platforms. This paper aims at understanding the impact of CNN topology, specifically depth and width, on the network's feature extraction capabilities. We address this question for the class of scattering networks that employ either Weyl-Heisenberg filters or wavelets, the modulus non-linearity, and no pooling. The exponential feature map energy decay results in Wiatowski et al., 2017, are generalized to $\mathcal{O}(a^{-N})$, where an arbitrary decay factor $a>1$ can be realized through suitable choice of the Weyl-Heisenberg prototype function or the mother wavelet. We then show how networks of fixed (possibly small) depth $N$ can be designed to guarantee that $((1-\varepsilon)\cdot 100)\%$ of the input signal's energy are contained in the feature vector. Based on the notion of operationally significant nodes, we characterize, partly rigorously and partly heuristically, the topology-reducing effects of (effectively) band-limited input signals, band-limited filters, and feature map symmetries. Finally, for networks based on Weyl-Heisenberg filters, we determine the prototype function bandwidth that minimizes---for fixed network depth $N$---the average number of operationally significant nodes per layer.

##### Abstract (translated by Google)
在实践中使用的深度卷积神经网络（CNN）潜在地使用了数百个层和$ 10 $，$ 000 $ s的节点。由于需要执行大量的卷积，这样的网络尺寸会带来相当大的计算复杂度;另外还需要学习和存储大量的参数。因此，非常深的和宽的CNN可能不适合在严格资源限制下运行的应用，例如在低功率嵌入式和移动平台中。本文旨在了解CNN拓扑的影响，特别是深度和宽度对网络特征提取能力的影响。我们针对使用Weyl-Heisenberg滤波器或小波的散射网络类，模数非线性度和不汇聚来解决这个问题。将指数特征图能量衰减结果推广到Wiatowski等，2017，推广到$ \ mathcal {O}（a ^ { -  N}）$，其中任意衰减因子$ a> 1 $可以通过适当的选择Weyl-Heisenberg原型函数或母小波函数。然后，我们将展示如何设计固定的（可能小的）深度的网络$ N $，以保证输入信号的能量包含在特征向量中（$ \（1 \ \ varepsilon）\ cdot 100）\％$。基于操作重要节点的概念，我们部分严格地和部分地启发式地描述（有效）带限输入信号，带限滤波器和特征映射对称的拓扑减少效应。最后，对于基于Weyl-Heisenberg滤波器的网络，我们确定原型函数的带宽，以最小化固定网络深度。$ N $ ---每层操作重要节点的平均数量。

##### URL
[https://arxiv.org/abs/1707.02711](https://arxiv.org/abs/1707.02711)

##### PDF
[https://arxiv.org/pdf/1707.02711](https://arxiv.org/pdf/1707.02711)

