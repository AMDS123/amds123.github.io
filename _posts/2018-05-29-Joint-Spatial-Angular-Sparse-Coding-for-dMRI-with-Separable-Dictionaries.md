---
layout: post
title: "Joint Spatial-Angular Sparse Coding for dMRI with Separable Dictionaries"
date: 2018-05-29 15:05:26
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Evan Schwab, Ren&#xe9; Vidal, Nicolas Charon
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion MRI (dMRI) provides the ability to reconstruct neuronal fibers in the brain, $\textit{in vivo}$, by measuring water diffusion along angular gradient directions in q-space. High angular resolution diffusion imaging (HARDI) can produce better estimates of fiber orientation than the popularly used diffusion tensor imaging, but the high number of samples needed to estimate diffusivity requires longer patient scan times. To accelerate dMRI, compressed sensing (CS) has been utilized by exploiting a sparse dictionary representation of the data, discovered through sparse coding. The sparser the representation, the fewer samples are needed to reconstruct a high resolution signal with limited information loss, and so an important area of research has focused on finding the sparsest possible representation of dMRI. Current reconstruction methods however, rely on an angular representation $\textit{per voxel}$ with added spatial regularization, and so, for non-zero signals, one is required to have at least one non-zero coefficient per voxel. This means that the global level of sparsity must be greater than the number of voxels. In contrast, we propose a joint spatial-angular representation of dMRI that will allow us to achieve levels of global sparsity that are below the number of voxels. A major challenge, however, is the computational complexity of solving a global sparse coding problem over large-scale dMRI. In this work, we present novel adaptations of popular sparse coding algorithms that become better suited for solving large-scale problems by exploiting spatial-angular separability. Our experiments show that our method achieves significantly sparser representations of HARDI than is possible by the state of the art.

##### Abstract (translated by Google)
扩散MRI（dMRI）通过测量q空间中沿角度梯度方向的水扩散，提供了重建大脑中的神经元纤维的能力。与普遍使用的弥散张量成像相比，高角度分辨率扩散成像（HARDI）可以产生更好的纤维取向估计，但估计弥散度所需的大量样本需要更长的患者扫描时间。为了加速dMRI，通过利用通过稀疏编码发现的数据的稀疏字典表示来利用压缩感测（CS）。稀疏表示，需要更少的样本来重建信息损失有限的高分辨率信号，因此重要的研究领域集中在寻找dMRI的尽可能最稀少的表示。然而，当前的重构方法依赖于具有增加的空间正则化的角度表示$ \ textit {每个体素}，因此对于非零信号，每个体素至少需要一个非零系数。这意味着全球稀疏程度必须大于体素的数量。相反，我们提出了dMRI的联合空间角度表示，它将使我们能够达到低于体素数量的全局稀疏度。然而，一个主要挑战是解决大规模dMRI的全局稀疏编码问题的计算复杂性。在这项工作中，我们提出了流行的稀疏编码算法的新颖改编，它们更适合通过利用空间角分离性来解决大规模问题。我们的实验表明，我们的方法实现了比现有技术更可能的HARDI稀疏表示。

##### URL
[http://arxiv.org/abs/1612.05846](http://arxiv.org/abs/1612.05846)

##### PDF
[http://arxiv.org/pdf/1612.05846](http://arxiv.org/pdf/1612.05846)

