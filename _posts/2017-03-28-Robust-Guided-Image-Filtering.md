---
layout: post
title: "Robust Guided Image Filtering"
date: 2017-03-28 02:59:15
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Wei Liu, Xiaogang Chen, Chunhua Shen, Jingyi Yu, Qiang Wu, Jie Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The process of using one image to guide the filtering process of another one is called Guided Image Filtering (GIF). The main challenge of GIF is the structure inconsistency between the guidance image and the target image. Besides, noise in the target image is also a challenging issue especially when it is heavy. In this paper, we propose a general framework for Robust Guided Image Filtering (RGIF), which contains a data term and a smoothness term, to solve the two issues mentioned above. The data term makes our model simultaneously denoise the target image and perform GIF which is robust against the heavy noise. The smoothness term is able to make use of the property of both the guidance image and the target image which is robust against the structure inconsistency. While the resulting model is highly non-convex, it can be solved through the proposed Iteratively Re-weighted Least Squares (IRLS) in an efficient manner. For challenging applications such as guided depth map upsampling, we further develop a data-driven parameter optimization scheme to properly determine the parameter in our model. This optimization scheme can help to preserve small structures and sharp depth edges even for a large upsampling factor (8x for example). Moreover, the specially designed structure of the data term and the smoothness term makes our model perform well in edge-preserving smoothing for single-image tasks (i.e., the guidance image is the target image itself). This paper is an extension of our previous work [1], [2].

##### Abstract (translated by Google)
使用一个图像来引导另一个图像的过滤过程的过程被称为引导图像过滤（GIF）。 GIF的主要挑战是引导图像和目标图像之间的结构不一致。此外，目标图像中的噪声也是一个具有挑战性的问题，尤其是在重量较大的情况下在本文中，我们提出了一个鲁棒导引图像过滤（RGIF）的一般框架，其中包含一个数据项和一个平滑项，以解决上述两个问题。数据项使得我们的模型同时对目标图像进行去噪，并执行对强噪声强健的GIF。平滑项能够利用对结构不一致的鲁棒性的引导图像和目标图像两者的特性。虽然得到的模型是高度非凸的，但是可以通过所提出的迭代重新加权最小平方（IRLS）以有效的方式来解决。对于具有挑战性的应用，例如引导深度图上采样，我们进一步开发数据驱动参数优化方案，以正确确定我们模型中的参数。即使对于大的上采样因子（例如8倍），这种优化方案也可以帮助保持小的结构和尖锐的深度边缘。而且，数据项和平滑项的特殊设计结构使得我们的模型在单幅图像任务（即引导图像是目标图像本身）的边缘保持平滑中表现良好。本文是我们以前的工作的延伸[1]，[2]。

##### URL
[https://arxiv.org/abs/1703.09379](https://arxiv.org/abs/1703.09379)

##### PDF
[https://arxiv.org/pdf/1703.09379](https://arxiv.org/pdf/1703.09379)

