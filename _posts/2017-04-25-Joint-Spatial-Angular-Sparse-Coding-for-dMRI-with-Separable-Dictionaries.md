---
layout: post
title: "Joint Spatial-Angular Sparse Coding for dMRI with Separable Dictionaries"
date: 2017-04-25 16:33:07
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Evan Schwab, René Vidal, Nicolas Charon
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion MRI (dMRI) provides the ability to reconstruct neuronal fibers in the brain, $\textit{in vivo}$, by measuring water diffusion along angular gradient directions in $q$-space. High angular resolution diffusion imaging (HARDI) can produce better estimates of fiber orientation than the popularly used diffusion tensor imaging, but the high number of samples needed to estimate diffusivity requires lengthy patient scan times. To accelerate dMRI, compressed sensing (CS) has been utilized by exploiting a sparse dictionary representation of the data, discovered through sparse coding. The sparser the representation, the fewer samples are needed to reconstruct a high resolution signal with limited information loss, and so an important area of research has focused on finding the sparsest possible representation of dMRI. Current reconstruction methods however, rely on an angular representation $\textit{per voxel}$ with added spatial regularization, and so, the global level of sparsity can be no less than the number of voxels. Therefore, state-of-the-art dMRI CS frameworks may have a fundamental limit to the rate acceleration that can be achieved. In contrast, we propose a joint spatial-angular representation of dMRI that will allow us to achieve levels of global sparsity that are below the number of voxels. A major challenge, however, is the computational complexity of solving a global sparse coding problem over large-scale dMRI. In this work, we present novel adaptations of popular sparse coding algorithms that become better suited for solving large-scale problems by exploiting spatial-angular separability. Our experiments show that our method achieves significantly sparser representations of HARDI than the state-of-the-art which has the potential to increase HARDI acceleration to new levels.

##### Abstract (translated by Google)
扩散MRI（dMRI）提供了通过在$ q $空间中沿角度梯度方向测量水扩散来重建大脑中的神经元纤维的能力。与普遍使用的扩散张量成像相比，高角度分辨率扩散成像（HARDI）可以产生更好的纤维取向估计，但估计扩散性所需的大量样本需要漫长的患者扫描时间。为了加速dMRI，压缩感知（CS）已经被利用，通过利用稀疏编码发现的数据的稀疏字典表示。表征越稀疏，重构高分辨率信号所需的样本越少，信息损失就越少，所以重要的研究领域集中在寻找dMRI的尽可能最少的表示。然而，当前的重建方法依赖于具有增加的空间正则化的角度表示$ \ textit {每个体素} $，因此，稀疏度的全局水平可以不低于体素的数量。因此，最先进的dMRI CS框架可能会对可实现的速率加速有一个基本的限制。相比之下，我们提出了dMRI的联合空间角度表示，这将使我们能够达到低于体素数量的全局稀疏水平。然而，一个主要的挑战是在大规模dMRI上解决全局稀疏编码问题的计算复杂性。在这项工作中，我们提出了流行的稀疏编码算法的新颖的适应，变得更适合于通过利用空间角度可分性来解决大规模问题。我们的实验表明，我们的方法实现了比现有技术更加稀疏的HARDI表示，这有可能将HARDI加速度提高到新的水平。

##### URL
[https://arxiv.org/abs/1612.05846](https://arxiv.org/abs/1612.05846)

##### PDF
[https://arxiv.org/pdf/1612.05846](https://arxiv.org/pdf/1612.05846)

