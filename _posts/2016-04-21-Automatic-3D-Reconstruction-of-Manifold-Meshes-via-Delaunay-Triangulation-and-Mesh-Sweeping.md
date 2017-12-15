---
layout: post
title: "Automatic 3D Reconstruction of Manifold Meshes via Delaunay Triangulation and Mesh Sweeping"
date: 2016-04-21 11:10:19
categories: arXiv_CV
tags: arXiv_CV Face Quantitative
author: Andrea Romanoni, Amaël Delaunoy, Marc Pollefeys, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a new approach to incrementally initialize a manifold surface for automatic 3D reconstruction from images. More precisely we focus on the automatic initialization of a 3D mesh as close as possible to the final solution; indeed many approaches require a good initial solution for further refinement via multi-view stereo techniques. Our novel algorithm automatically estimates an initial manifold mesh for surface evolving multi-view stereo algorithms, where the manifold property needs to be enforced. It bootstraps from 3D points extracted via Structure from Motion, then iterates between a state-of-the-art manifold reconstruction step and a novel mesh sweeping algorithm that looks for new 3D points in the neighborhood of the reconstructed manifold to be added in the manifold reconstruction. The experimental results show quantitatively that the mesh sweeping improves the resolution and the accuracy of the manifold reconstruction, allowing a better convergence of state-of-the-art surface evolution multi-view stereo algorithms.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法来增量初始化一个流形面的自动三维重建的图像。更确切地说，我们专注于尽可能靠近最终解决方案的3D网格的自动初始化;事实上，许多方法需要通过多视图立体技术进一步改进的良好初始解决方案。我们的新算法自动估计表面演进的多视图立体算法的初始流形网格，其中多样性属性需要执行。它从通过Structure from Motion提取的3D点开始引导，然后在最先进的流形重构步骤和新型网格扫描算法之间进行迭代，该算法在重构流形的邻域中寻找新的3D点，以在流形中添加重建。实验结果定量表明，网格扫描提高了分辨率和流形重建的精度，从而可以更好地收敛最先进的表面演化多视图立体算法。

##### URL
[https://arxiv.org/abs/1604.06258](https://arxiv.org/abs/1604.06258)

##### PDF
[https://arxiv.org/pdf/1604.06258](https://arxiv.org/pdf/1604.06258)

