---
layout: post
title: "Deep Back Projection for Sparse-View CT Reconstruction"
date: 2018-07-06 12:06:19
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Dong Hye Ye, Gregery T. Buzzard, Max Ruby, Charles A. Bouman
mathjax: true
---

* content
{:toc}

##### Abstract
Filtered back projection (FBP) is a classical method for image reconstruction from sinogram CT data. FBP is computationally efficient but produces lower quality reconstructions than more sophisticated iterative methods, particularly when the number of views is lower than the number required by the Nyquist rate. In this paper, we use a deep convolutional neural network (CNN) to produce high-quality reconstructions directly from sinogram data. A primary novelty of our approach is that we first back project each view separately to form a stack of back projections and then feed this stack as input into the convolutional neural network. These single-view back projections convert the encoding of sinogram data into the appropriate spatial location, which can then be leveraged by the spatial invariance of the CNN to learn the reconstruction effectively. We demonstrate the benefit of our CNN based back projection on simulated sparse-view CT data over classical FBP.

##### Abstract (translated by Google)
滤波反投影（FBP）是用于从正弦图CT数据重建图像的经典方法。 FBP在计算上是高效的，但是比更复杂的迭代方法产生更低质量的重建，特别是当视图的数量低于奈奎斯特速率所需的数量时。在本文中，我们使用深度卷积神经网络（CNN）直接从正弦图数据生成高质量的重建。我们方法的一个主要新颖之处在于，我们首先分别对每个视图进行投影，以形成一组反投影，然后将此堆栈作为输入馈送到卷积神经网络中。这些单视图反投影将正弦图数据的编码转换为适当的空间位置，然后可以通过CNN的空间不变性来有效地学习重建。我们证明了基于CNN的反投影对经典FBP上的模拟稀疏视图CT数据的益处。

##### URL
[http://arxiv.org/abs/1807.02370](http://arxiv.org/abs/1807.02370)

##### PDF
[http://arxiv.org/pdf/1807.02370](http://arxiv.org/pdf/1807.02370)

