---
layout: post
title: "Learning Sparse High Dimensional Filters: Image Filtering, Dense CRFs and Bilateral Neural Networks"
date: 2015-11-25 23:16:15
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Gradient_Descent
author: Varun Jampani, Martin Kiefel, Peter V. Gehler
mathjax: true
---

* content
{:toc}

##### Abstract
Bilateral filters have wide spread use due to their edge-preserving properties. The common use case is to manually choose a parametric filter type, usually a Gaussian filter. In this paper, we will generalize the parametrization and in particular derive a gradient descent algorithm so the filter parameters can be learned from data. This derivation allows to learn high dimensional linear filters that operate in sparsely populated feature spaces. We build on the permutohedral lattice construction for efficient filtering. The ability to learn more general forms of high-dimensional filters can be used in several diverse applications. First, we demonstrate the use in applications where single filter applications are desired for runtime reasons. Further, we show how this algorithm can be used to learn the pairwise potentials in densely connected conditional random fields and apply these to different image segmentation tasks. Finally, we introduce layers of bilateral filters in CNNs and propose bilateral neural networks for the use of high-dimensional sparse data. This view provides new ways to encode model structure into network architectures. A diverse set of experiments empirically validates the usage of general forms of filters.

##### Abstract (translated by Google)
双边滤波器由于其边缘保持特性而具有广泛的应用。常见的用例是手动选择参数滤波器类型，通常是高斯滤波器。在本文中，我们将推广参数化，特别是导出一个梯度下降算法，使滤波器参数可以从数据中学习。这种推导允许学习在稀疏填充的特征空间中操作的高维线性滤波器。我们建立在permutohedral晶格构造上进行高效过滤。学习更一般形式的高维滤波器的能力可用于多种不同的应用。首先，我们演示了在运行时需要单个过滤器应用程序的应用程序中的使用。进一步，我们展示了如何使用这种算法来学习密集连接条件随机场中的成对电势，并将其应用于不同的图像分割任务。最后，我们在CNN中引入了双层滤波器，并提出了使用高维稀疏数据的双边神经网络。该视图提供了将模型结构编码到网络架构中的新方法。一组不同的实验验证了一般形式的过滤器的使用。

##### URL
[https://arxiv.org/abs/1503.04949](https://arxiv.org/abs/1503.04949)

##### PDF
[https://arxiv.org/pdf/1503.04949](https://arxiv.org/pdf/1503.04949)

