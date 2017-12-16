---
layout: post
title: "Semantically Informed Multiview Surface Refinement"
date: 2017-06-26 12:19:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Inference
author: Maros Blaha, Mathias Rothermel, Martin R. Oswald, Torsten Sattler, Audrey Richard, Jan D. Wegner, Marc Pollefeys, Konrad Schindler
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to jointly refine the geometry and semantic segmentation of 3D surface meshes. Our method alternates between updating the shape and the semantic labels. In the geometry refinement step, the mesh is deformed with variational energy minimization, such that it simultaneously maximizes photo-consistency and the compatibility of the semantic segmentations across a set of calibrated images. Label-specific shape priors account for interactions between the geometry and the semantic labels in 3D. In the semantic segmentation step, the labels on the mesh are updated with MRF inference, such that they are compatible with the semantic segmentations in the input images. Also, this step includes prior assumptions about the surface shape of different semantic classes. The priors induce a tight coupling, where semantic information influences the shape update and vice versa. Specifically, we introduce priors that favor (i) adaptive smoothing, depending on the class label; (ii) straightness of class boundaries; and (iii) semantic labels that are consistent with the surface orientation. The novel mesh-based reconstruction is evaluated in a series of experiments with real and synthetic data. We compare both to state-of-the-art, voxel-based semantic 3D reconstruction, and to purely geometric mesh refinement, and demonstrate that the proposed scheme yields improved 3D geometry as well as an improved semantic segmentation.

##### Abstract (translated by Google)
我们提出了一种联合提炼三维表面网格的几何和语义分割的方法。我们的方法交替更新形状和语义标签。在几何细化步骤中，网格被变形能量最小化，使得它同时最大化光学一致性和一组校准图像上的语义分割的兼容性。标签特定的形状预先考虑3D中的几何和语义标签之间的交互。在语义分割步骤中，网格上的标签用MRF推断进行更新，使得它们与输入图像中的语义分割相兼容。此外，这一步包括对不同语义类的表面形状的先验假设。先验引起紧密耦合，语义信息影响形状更新，反之亦然。具体来说，我们引入了（i）自适应平滑的先验，取决于类别标签; （二）班级界线的直线性;和（iii）与表面方向一致的语义标签。新的基于网格的重建是在一系列实验和合成数据的实验中评估的。我们比较了最先进的，基于体素的语义三维重建和纯几何网格细化，并且证明了所提出的方案产生了改进的三维几何以及改进的语义分割。

##### URL
[https://arxiv.org/abs/1706.08336](https://arxiv.org/abs/1706.08336)

##### PDF
[https://arxiv.org/pdf/1706.08336](https://arxiv.org/pdf/1706.08336)

