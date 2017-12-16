---
layout: post
title: "Scalable Online Convolutional Sparse Coding"
date: 2017-11-02 15:55:05
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Optimization
author: Yaqing Wang, Quanming Yao, James T. Kwok, Lionel M. Ni
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional sparse coding (CSC) improves sparse coding by learning a shift-invariant dictionary from the data. However, existing CSC algorithms operate in the batch mode and are expensive, in terms of both space and time, on large datasets. In this paper, we alleviate these problems by using online learning. The key is a reformulation of the CSC objective so that convolution can be handled easily in the frequency domain and much smaller history matrices are needed. We use the alternating direction method of multipliers (ADMM) to solve the resulting optimization problem and the ADMM subproblems have efficient closed-form solutions. Theoretical analysis shows that the learned dictionary converges to a stationary point of the optimization problem. Extensive experiments show that convergence of the proposed method is much faster and its reconstruction performance is also better. Moreover, while existing CSC algorithms can only run on a small number of images, the proposed method can handle at least ten times more images.

##### Abstract (translated by Google)
卷积稀疏编码（CSC）通过从数据中学习移位不变字典来改善稀疏编码。然而，现有的CSC算法在批处理模式下运行，并且在空间和时间上对大数据集而言是昂贵的。在本文中，我们通过使用在线学习来缓解这些问题。关键在于CSC目标的重新构造，使得卷积可以在频域中容易地处理，并且需要更小的历史矩阵。我们使用乘法器的交替方向方法（ADMM）来解决最终的优化问题，并且ADMM子问题具有高效的闭合解决方案。理论分析表明，学习词典收敛到优化问题的一个平稳点。大量的实验表明，该方法的收敛速度更快，重建性能也更好。此外，虽然现有的CSC算法只能在少量图像上运行，但所提出的方法至少可以处理十倍以上的图像。

##### URL
[https://arxiv.org/abs/1706.06972](https://arxiv.org/abs/1706.06972)

##### PDF
[https://arxiv.org/pdf/1706.06972](https://arxiv.org/pdf/1706.06972)

