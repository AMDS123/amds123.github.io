---
layout: post
title: "An extended Perona-Malik model based on probabilistic models"
date: 2016-12-19 13:39:45
categories: arXiv_CV
tags: arXiv_CV
author: Lars M. Mescheder, Dirk A. Lorenz
mathjax: true
---

* content
{:toc}

##### Abstract
The Perona-Malik model has been very successful at restoring images from noisy input. In this paper, we reinterpret the Perona-Malik model in the language of Gaussian scale mixtures and derive some extensions of the model. Specifically, we show that the expectation-maximization (EM) algorithm applied to Gaussian scale mixtures leads to the lagged-diffusivity algorithm for computing stationary points of the Perona-Malik diffusion equations. Moreover, we show how mean field approximations to these Gaussian scale mixtures lead to a modification of the lagged-diffusivity algorithm that better captures the uncertainties in the restoration. Since this modification can be hard to compute in practice we propose relaxations to the mean field objective to make the algorithm computationally feasible. Our numerical experiments show that this modified lagged-diffusivity algorithm often performs better at restoring textured areas and fuzzy edges than the unmodified algorithm. As a second application of the Gaussian scale mixture framework, we show how an efficient sampling procedure can be obtained for the probabilistic model, making the computation of the conditional mean and other expectations algorithmically feasible. Again, the resulting algorithm has a strong resemblance to the lagged-diffusivity algorithm. Finally, we show that a probabilistic version of the Mumford-Shah segementation model can be obtained in the same framework with a discrete edge-prior.

##### Abstract (translated by Google)
Perona-Malik模型在从嘈杂输入中恢复图像方面非常成功。在本文中，我们用高斯尺度混合语言重新解释Perona-Malik模型，并推导出模型的一些扩展。具体而言，我们证明了应用于高斯尺度混合的期望最大化（EM）算法导致了计算Perona-Malik扩散方程平稳点的滞后扩散算法。此外，我们还展示了这些高斯尺度混合的平均场逼近如何导致修正滞后扩散算法，更好地捕捉修复中的不确定性。由于这种修改在实际中很难计算，我们建议放宽平均场目标以使算法在计算上可行。我们的数值实验表明，这种改进的滞后扩散算法在恢复纹理区域和模糊边缘方面常常比未修改的算法更好地执行。作为高斯尺度混合框架的第二个应用，我们展示了如何获得一个有效的抽样过程的概率模型，使计算条件均值和其他期望在算法上是可行的。再次，所得到的算法与滞后扩散算法有很强的相似性。最后，我们展示了一个概率版本的Mumford-Shah segementation模型，可以在相同的框架中获得一个离散的边缘优先。

##### URL
[https://arxiv.org/abs/1612.06176](https://arxiv.org/abs/1612.06176)

##### PDF
[https://arxiv.org/pdf/1612.06176](https://arxiv.org/pdf/1612.06176)

