---
layout: post
title: "Gibbs-Ringing Artifact Removal Based on Local Subvoxel-shifts"
date: 2015-01-30 12:52:30
categories: arXiv_CV
tags: arXiv_CV
author: Elias Kellner, Bibek Dhital, Marco Reisert
mathjax: true
---

* content
{:toc}

##### Abstract
Gibbs-ringing is a well known artifact which manifests itself as spurious oscillations in the vicinity of sharp image transients, e.g. at tissue boundaries. The origin can be seen in the truncation of k-space during MRI data-acquisition. Consequently, correction techniques like Gegenbauer reconstruction or extrapolation methods aim at recovering these missing data. Here, we present a simple and robust method which exploits a different view on the Gibbs-phenomena. The truncation in k-space can be interpreted as a convolution with a sinc-function in image space. Hence, the severity of the artifacts depends on how the sinc-function is sampled. We propose to re-interpolate the image based on local, subvoxel shifts to sample the ringing pattern at the zero-crossings of the oscillating sinc-function. With this, the artifact can effectively and robustly be removed with a minimal amount of smoothing.

##### Abstract (translated by Google)
吉布斯（Gibbs-Ringing）振荡是众所周知的伪像，其表现为在急剧图像瞬变附近的虚假振荡，例如，在组织边界。 MRI数据采集过程中的k空间截断可以看出原点。因此，Gegenbauer重建或外推法等修正技术的目的是恢复这些缺失的数据。在这里，我们提出一个简单而强大的方法，利用吉布斯现象的不同观点。 k空间中的截断可以被解释为与图像空间中的sinc函数的卷积。因此，伪像的严重程度取决于sinc函数如何被采样。我们建议基于局部子体素位移对图像进行重新插值，以在振荡sinc函数的零交叉处对振铃模式进行采样。有了这个，神器可以有效地和稳健地去除最少量的平滑。

##### URL
[https://arxiv.org/abs/1501.07758](https://arxiv.org/abs/1501.07758)

##### PDF
[https://arxiv.org/pdf/1501.07758](https://arxiv.org/pdf/1501.07758)

