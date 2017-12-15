---
layout: post
title: "Estimation of Fiber Orientations Using Neighborhood Information"
date: 2016-05-16 09:59:51
categories: arXiv_CV
tags: arXiv_CV Regularization Quantitative Relation
author: Chuyang Ye, Jiachen Zhuo, Rao P. Gullapalli, Jerry L. Prince
mathjax: true
---

* content
{:toc}

##### Abstract
Data from diffusion magnetic resonance imaging (dMRI) can be used to reconstruct fiber tracts, for example, in muscle and white matter. Estimation of fiber orientations (FOs) is a crucial step in the reconstruction process and these estimates can be corrupted by noise. In this paper, a new method called Fiber Orientation Reconstruction using Neighborhood Information (FORNI) is described and shown to reduce the effects of noise and improve FO estimation performance by incorporating spatial consistency. FORNI uses a fixed tensor basis to model the diffusion weighted signals, which has the advantage of providing an explicit relationship between the basis vectors and the FOs. FO spatial coherence is encouraged using weighted l1-norm regularization terms, which contain the interaction of directional information between neighbor voxels. Data fidelity is encouraged using a squared error between the observed and reconstructed diffusion weighted signals. After appropriate weighting of these competing objectives, the resulting objective function is minimized using a block coordinate descent algorithm, and a straightforward parallelization strategy is used to speed up processing. Experiments were performed on a digital crossing phantom, ex vivo tongue dMRI data, and in vivo brain dMRI data for both qualitative and quantitative evaluation. The results demonstrate that FORNI improves the quality of FO estimation over other state of the art algorithms.

##### Abstract (translated by Google)
来自扩散磁共振成像（dMRI）的数据可用于重建纤维束，例如在肌肉和白质中。纤维取向（FO）的估计是重建过程中的关键步骤，并且这些估计可能被噪声破坏。在本文中，描述了一种称为“使用邻域信息的光纤方位重构”（FORNI）的新方法，通过结合空间一致性来降低噪声的影响并提高FO估计性能。 FORNI使用固定的张量基础来对扩散加权信号进行建模，这具有提供基矢量和FO之间的明确关系的优点。 FO空间一致性是鼓励使用加权l1范数正则化项，其中包含相邻体素之间的方向信息的相互作用。使用观察到的和重建的扩散加权信号之间的平方误差鼓励数据保真度。在对这些竞争目标进行适当的加权之后，使用块坐标下降算法使得到的目标函数最小化，并且使用直接的并行化策略来加速处理。在数字交叉幻影，离体舌dMRI数据和体内大脑dMRI数据进行了定性和定量评估的实验。结果表明，FORNI相对于其他现有算法提高了FO估计的质量。

##### URL
[https://arxiv.org/abs/1601.04115](https://arxiv.org/abs/1601.04115)

##### PDF
[https://arxiv.org/pdf/1601.04115](https://arxiv.org/pdf/1601.04115)

