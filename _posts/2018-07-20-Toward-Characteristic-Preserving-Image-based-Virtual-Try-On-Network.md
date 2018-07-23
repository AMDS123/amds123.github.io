---
layout: post
title: "Toward Characteristic-Preserving Image-based Virtual Try-On Network"
date: 2018-07-20 01:42:58
categories: arXiv_CV
tags: arXiv_CV Attention Quantitative
author: Bochao Wang, Huabin Zhang, Xiaodan Liang, Yimin Chen, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based virtual try-on systems for fitting a new in-shop clothes into a person image have attracted increasing research attention, yet is still challenging. A desirable pipeline should not only transform the target clothes into the most fit shape seamlessly but also preserve well the clothes identity in the generated image, that is, the key characteristics (e.g. texture, logo, embroidery) that depict the original clothes. However, previous image-conditioned generation works fail to meet these critical requirements towards the plausible virtual try-on performance since they fail to handle large spatial misalignment between the input image and target clothes. Prior work explicitly tackled spatial deformation using shape context matching, but failed to preserve clothing details due to its coarse-to-fine strategy. In this work, we propose a new fully-learnable Characteristic-Preserving Virtual Try-On Network (CP-VTON) for addressing all real-world challenges in this task. First, CP-VTON learns a thin-plate spline transformation for transforming the in-shop clothes into fitting the body shape of the target person via a new Geometric Matching Module (GMM) rather than computing correspondences of interest points as prior works did. Second, to alleviate boundary artifacts of warped clothes and make the results more realistic, we employ a Try-On Module that learns a composition mask to integrate the warped clothes and the rendered image to ensure smoothness. Extensive experiments on a fashion dataset demonstrate our CP-VTON achieves the state-of-the-art virtual try-on performance both qualitatively and quantitatively.

##### Abstract (translated by Google)
用于将新的店内服装装配到人物图像中的基于图像的虚拟试穿系统引起了越来越多的研究关注，但仍然具有挑战性。理想的管道不仅应该将目标衣服无缝地变换成最合身的形状，而且还要在所生成的图像中很好地保持衣服的身份，即描绘原始衣服的关键特征（例如纹理，标志，刺绣）。然而，之前的图像条件生成工作无法满足对可信的虚拟试穿性能的这些关键要求，因为它们无法处理输入图像和目标服装之间的大的空间错位。之前的工作使用形状上下文匹配明确地解决了空间变形，但由于其从粗到细的策略而未能保留服装细节。在这项工作中，我们提出了一个新的完全可学习的特征保留虚拟试穿网络（CP-VTON），用于解决此任务中的所有现实挑战。首先，CP-VTON学习薄板样条转换，通过新的几何匹配模块（GMM）将店内服装转换为适合目标人物的体形，而不是像先前的工作那样计算兴趣点的对应关系。其次，为了减轻扭曲衣服的边界伪影并使结果更加逼真，我们采用了一个试穿模块来学习合成蒙版，以整合扭曲的衣服和渲染的图像，以确保平滑。对时尚数据集进行的大量实验表明，我们的CP-VTON在质量和数量上都实现了最先进的虚拟试穿性能。

##### URL
[http://arxiv.org/abs/1807.07688](http://arxiv.org/abs/1807.07688)

##### PDF
[http://arxiv.org/pdf/1807.07688](http://arxiv.org/pdf/1807.07688)

