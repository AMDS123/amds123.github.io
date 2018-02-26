---
layout: post
title: "SPLATNet: Sparse Lattice Networks for Point Cloud Processing"
date: 2018-02-22 19:30:09
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN
author: Hang Su, Varun Jampani, Deqing Sun, Subhransu Maji, Vangelis Kalogerakis, Ming-Hsuan Yang, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
We present a network architecture for processing point clouds that directly operates on the collection of points represented as a sparse set of samples in a high-dimensional lattice. Naively applying convolutions on this lattice scales poorly both in terms of memory and computational cost as the size of the lattice increases. Instead, our network uses sparse bilateral convolutional layers as building blocks. These layers maintain efficiency by using indexing structures to apply convolutions only on occupied parts of the lattice, and allow flexible specification of the lattice structure enabling hierarchical and spatially-aware feature learning, as well as joint 2D-3D reasoning. Both point-based and image-based representations can be easily incorporated in a network with such layers and the resulting model can be trained in an end-to-end manner. We present results on 3D segmentation tasks where our approach outperforms existing state-of-the-art techniques.

##### Abstract (translated by Google)
我们提出了一种处理点云的网络体系结构，它直接对点集合进行操作，这些点表示为一个高维网格中的稀疏样本集合。天然地应用这种网格上的卷积在内存和计算成本方面都会随着网格大小的增加而缩小。相反，我们的网络使用稀疏的双边卷积层作为构建块。这些层通过使用索引结构来仅对格子的占用部分应用卷积来保持效率，并且允许灵活指定格子结构以实现分级和空间感知特征学习，以及联合2D-3D推理。基于点的图像和基于图像的表示可以很容易地结合到具有这种图层的网络中，并且所得到的模型可以以端对端的方式进行训练。我们展示了3D分割任务的结果，其中我们的方法胜过了现有的最新技术。

##### URL
[http://arxiv.org/abs/1802.08275](http://arxiv.org/abs/1802.08275)

##### PDF
[http://arxiv.org/pdf/1802.08275](http://arxiv.org/pdf/1802.08275)

