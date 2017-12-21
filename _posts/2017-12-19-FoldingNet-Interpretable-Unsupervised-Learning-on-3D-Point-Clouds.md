---
layout: post
title: "FoldingNet: Interpretable Unsupervised Learning on 3D Point Clouds"
date: 2017-12-19 23:49:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Classification
author: Yaoqing Yang, Chen Feng, Yiru Shen, Dong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep networks that directly handle points in a point set, e.g., PointNet, have been state-of-the-art for supervised semantic learning tasks on point clouds such as classification and segmentation. In this work, a novel end-to-end deep auto-encoder is proposed to address unsupervised learning challenges on point clouds. On the encoder side, a graph-based enhancement is enforced to promote local structures on top of PointNet. Then, a novel folding-based approach is proposed in the decoder, which folds a 2D grid onto the underlying 3D object surface of a point cloud. The proposed decoder only uses about 7\% parameters of a decoder with fully-connected neural networks, yet leads to a more discriminative representation that achieves higher linear SVM classification accuracy than the benchmark. In addition, the proposed decoder structure is shown, in theory, to be a generic architecture that is able to reconstruct an arbitrary point cloud from a 2D grid. Finally, this folding-based decoder is interpretable since the reconstruction could be viewed as a fine granular warping from the 2D grid to the point cloud surface.

##### Abstract (translated by Google)
直接处理点集（例如PointNet）中的点的最近的深度网络对于诸如分类和分割的点云上的受监督的语义学习任务而言是最先进的。在这项工作中，提出了一种新型的端到端深度自动编码器来解决点云上的无监督学习挑战。在编码器方面，强化了基于图形的增强来促进PointNet上的局部结构。然后，在解码器中提出了一种基于折叠的新方法，将2D网格折叠到点云底层的三维物体表面上。所提出的解码器仅使用具有完全连接的神经网络的解码器的大约7％的参数，但是导致更具辨别性的表示，其实现比基准更高的线性SVM分类准确度。另外，所提出的解码器结构在理论上被示出为能够从2D网格重建任意点云的通用体系结构。最后，这种基于折叠的解码器是可解释的，因为重建可以被看作是从2D网格到点云表面的细粒度翘曲。

##### URL
[https://arxiv.org/abs/1712.07262](https://arxiv.org/abs/1712.07262)

##### PDF
[https://arxiv.org/pdf/1712.07262](https://arxiv.org/pdf/1712.07262)

