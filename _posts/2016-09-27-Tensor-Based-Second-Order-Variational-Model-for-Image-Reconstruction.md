---
layout: post
title: "Tensor Based Second Order Variational Model for Image Reconstruction"
date: 2016-09-27 12:51:09
categories: arXiv_CV
tags: arXiv_CV
author: Jinming Duan, Wil OC Ward, Luke Sibbett, Zhenkuan Pan, Li Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Second order total variation (SOTV) models have advantages for image reconstruction over their first order counterparts including their ability to remove the staircase artefact in the reconstructed image, but they tend to blur the reconstructed image. To overcome this drawback, we introduce a new Tensor Weighted Second Order (TWSO) model for image reconstruction. Specifically, we develop a novel regulariser for the SOTV model that uses the Frobenius norm of the product of the SOTV Hessian matrix and the anisotropic tensor. We then adapt the alternating direction method of multipliers (ADMM) to solve the proposed model by breaking down the original problem into several subproblems. All the subproblems have closed-forms and can thus be solved efficiently. The proposed method is compared with a range of state-of-the-art approaches such as tensor-based anisotropic diffusion, total generalised variation, Euler's elastica, etc. Numerical experimental results of the method on both synthetic and real images from the Berkeley database BSDS500 demonstrate that the proposed method eliminates both the staircase and blurring effects and outperforms the existing approaches for image inpainting and denoising applications.

##### Abstract (translated by Google)
二阶总变分（SOTV）模型在其一阶对应物上的图像重构具有优势，包括它们能够去除重建图像中的阶梯伪影，但是它们倾向于使重建图像模糊。为了克服这个缺点，我们引入了用于图像重建的新的张量加权二阶（TWSO）模型。具体而言，我们为SOTV模型开发了一种新型调节器，它使用SOTV Hessian矩阵和各向异性张量积的Frobenius范数。然后，我们采用交替方向的乘法器（ADMM）来解决所提出的模型，将原问题分解成几个子问题。所有的子问题都有封闭的形式，因此可以得到有效的解决。将该方法与基于张量的各向异性扩散，总体广义变分，欧拉弹性等一系列最新方法进行了比较。数值实验结果表明该方法在伯克利数据库的合成图像和真实图像BSDS500表明，该方法消除了楼梯和模糊效果，并且胜过了现有的图像修复和去噪方法。

##### URL
[https://arxiv.org/abs/1609.08387](https://arxiv.org/abs/1609.08387)

##### PDF
[https://arxiv.org/pdf/1609.08387](https://arxiv.org/pdf/1609.08387)

