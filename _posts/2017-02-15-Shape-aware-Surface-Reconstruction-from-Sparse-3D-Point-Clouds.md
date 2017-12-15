---
layout: post
title: "Shape-aware Surface Reconstruction from Sparse 3D Point-Clouds"
date: 2017-02-15 11:45:36
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Face
author: Florian Bernard, Luis Salamanca, Johan Thunberg, Alexander Tack, Dennis Jentsch, Hans Lamecker, Stefan Zachow, Frank Hertel, Jorge Goncalves, Peter Gemmar
mathjax: true
---

* content
{:toc}

##### Abstract
The reconstruction of an object's shape or surface from a set of 3D points plays an important role in medical image analysis, e.g. in anatomy reconstruction from tomographic measurements or in the process of aligning intra-operative navigation and preoperative planning data. In such scenarios, one usually has to deal with sparse data, which significantly aggravates the problem of reconstruction. However, medical applications often provide contextual information about the 3D point data that allow to incorporate prior knowledge about the shape that is to be reconstructed. To this end, we propose the use of a statistical shape model (SSM) as a prior for surface reconstruction. The SSM is represented by a point distribution model (PDM), which is associated with a surface mesh. Using the shape distribution that is modelled by the PDM, we formulate the problem of surface reconstruction from a probabilistic perspective based on a Gaussian Mixture Model (GMM). In order to do so, the given points are interpreted as samples of the GMM. By using mixture components with anisotropic covariances that are "oriented" according to the surface normals at the PDM points, a surface-based fitting is accomplished. Estimating the parameters of the GMM in a maximum a posteriori manner yields the reconstruction of the surface from the given data points. We compare our method to the extensively used Iterative Closest Points method on several different anatomical datasets/SSMs (brain, femur, tibia, hip, liver) and demonstrate superior accuracy and robustness on sparse data.

##### Abstract (translated by Google)
从一组3D点重建对象的形状或表面在医学图像分析中起着重要的作用，例如，在断层扫描测量的解剖重建中或在对准术中导航和术前计划数据的过程中。在这种情况下，通常需要处理稀疏的数据，这显着加剧了重建的问题。然而，医学应用通常提供关于3D点数据的上下文信息，其允许并入关于要重建的形状的先前知识。为此，我们建议使用统计形状模型（SSM）作为表面重建的先验。 SSM由与表面网格相关的点分布模型（PDM）表示。利用PDM建模的形状分布，从高斯混合模型（Gaussian Mixture Model，GMM）的概率角度出发，提出了表面重构问题。为了这样做，给定的点被解释为GMM的样本。通过使用具有根据PDM点处的表面法线“定向”的各向异性协方差的混合物成分，完成了基于表面的拟合。以最大后验方式估计GMM的参数，从给定的数据点产生表面重建。我们将我们的方法与在几种不同的解剖数据集/ SSM（脑，股骨，胫骨，髋，肝）上广泛使用的迭代最接近点方法进行了比较，并证明了对稀疏数据的优越的准确性和鲁棒性。

##### URL
[https://arxiv.org/abs/1602.08425](https://arxiv.org/abs/1602.08425)

##### PDF
[https://arxiv.org/pdf/1602.08425](https://arxiv.org/pdf/1602.08425)

