---
layout: post
title: "A Deep Learning Approach for Reconstruction Filter Kernel Discretization"
date: 2017-10-17 13:57:00
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Christopher Syben, Bernhard Stimpel, Katharina Breininger, Tobias Würfl, Rebecca Fahrig, Arnd Dörfler, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present substantial evidence that a deep neural network will intrinsically learn the appropriate way to discretize the ideal continuous reconstruction filter. Currently, the Ram-Lak filter or heuristic filters which impose different noise assumptions are used for filtered back-projection. All of these, however, inhibit a fully data-driven reconstruction deep learning approach. In addition, the heuristic filters are not chosen in an optimal sense. To tackle this issue, we propose a formulation to directly learn the reconstruction filter. The filter is initialized with the ideal Ramp filter as a strong pre-training and learned in frequency domain. We compare the learned filter with the Ram-Lak and the Ramp filter on a numerical phantom as well as on a real CT dataset. The results show that the network properly discretizes the continuous Ramp filter and converges towards the Ram-Lak solution. In our view these observations are interesting to gain a better understanding of deep learning techniques and traditional analytic techniques such as Wiener filtering and discretization theory. Furthermore, this will allow fully trainable data-driven reconstruction deep learning approaches.

##### Abstract (translated by Google)
在本文中，我们提出了大量的证据表明，深度神经网络将内在地学习离散理想连续重建滤波器的适当方式。目前，采用不同噪声假设的Ram-Lak滤波器或启发式滤波器被用于滤波反投影。所有这些，但是，抑制完全数据驱动的重建深度学习方法。另外，启发式过滤器不是以最佳方式选择的。为了解决这个问题，我们提出了一个直接学习重构滤波器的公式。滤波器通过理想的Ramp滤波器进行初始化，作为强大的预训练并在频域学习。我们将学习的滤波器与数值模型中的Ram-Lak和Ramp滤波器以及真实的CT数据集进行比较。结果表明，网络适当地离散连续Ramp滤波器并收敛到Ram-Lak解。在我们看来，这些观察结果对深入了解深度学习技术和传统分析技术（如维纳滤波和离散化理论）很有帮助。此外，这将使完全可训练的数据驱动重建深度学习方法。

##### URL
[https://arxiv.org/abs/1710.06287](https://arxiv.org/abs/1710.06287)

##### PDF
[https://arxiv.org/pdf/1710.06287](https://arxiv.org/pdf/1710.06287)

