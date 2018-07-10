---
layout: post
title: "Precision Learning: Reconstruction Filter Kernel Discretization"
date: 2018-07-09 13:15:14
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Christopher Syben, Bernhard Stimpel, Katharina Breininger, Tobias W&#xfc;rfl, Rebecca Fahrig, Arnd D&#xf6;rfler, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present substantial evidence that a deep neural network will intrinsically learn the appropriate way to discretize the ideal continuous reconstruction filter. Currently, the Ram-Lak filter or heuristic filters which impose different noise assumptions are used for filtered back-projection. All of these, however, inhibit a fully data-driven reconstruction deep learning approach. In addition, the heuristic filters are not chosen in an optimal sense. To tackle this issue, we propose a formulation to directly learn the reconstruction filter. The filter is initialized with the ideal Ramp filter as a strong pre-training and learned in frequency domain. We compare the learned filter with the Ram-Lak and the Ramp filter on a numerical phantom as well as on a real CT dataset. The results show that the network properly discretizes the continuous Ramp filter and converges towards the Ram-Lak solution. In our view these observations are interesting to gain a better understanding of deep learning techniques and traditional analytic techniques such as Wiener filtering and discretization theory. Furthermore, this will allow fully trainable data-driven reconstruction deep learning approaches.

##### Abstract (translated by Google)
在本文中，我们提出了大量证据，证明深度神经网络将从本质上学习离散理想连续重建滤波器的适当方法。目前，采用不同噪声假设的Ram-Lak滤波器或启发式滤波器用于滤波反投影。然而，所有这些都抑制了完全数据驱动的重建深度学习方法。此外，启发式滤波器不是在最佳意义上选择的。为了解决这个问题，我们提出了一个直接学习重建滤波器的公式。使用理想的斜坡滤波器初始化滤波器作为强大的预训练并在频域中学习。我们将数学模型以及真实CT数据集上的学习滤波器与Ram-Lak和Ramp滤波器进行比较。结果表明，网络适当地离散连续斜坡滤波器并收敛于Ram-Lak解。在我们看来，这些观察结果对于更好地理解深度学习技术和传统的分析技术（如维纳滤波和离散化理论）很有意义。此外，这将允许完全可训练的数据驱动的重建深度学习方法。

##### URL
[http://arxiv.org/abs/1710.06287](http://arxiv.org/abs/1710.06287)

##### PDF
[http://arxiv.org/pdf/1710.06287](http://arxiv.org/pdf/1710.06287)

