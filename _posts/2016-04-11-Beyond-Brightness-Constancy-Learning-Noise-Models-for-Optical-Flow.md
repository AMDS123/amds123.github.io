---
layout: post
title: "Beyond Brightness Constancy: Learning Noise Models for Optical Flow"
date: 2016-04-11 07:23:44
categories: arXiv_CV
tags: arXiv_CV
author: Dan Rosenbaum, Yair Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
Optical flow is typically estimated by minimizing a "data cost" and an optional regularizer. While there has been much work on different regularizers many modern algorithms still use a data cost that is not very different from the ones used over 30 years ago: a robust version of brightness constancy or gradient constancy. In this paper we leverage the recent availability of ground-truth optical flow databases in order to learn a data cost. Specifically we take a generative approach in which the data cost models the distribution of noise after warping an image according to the flow and we measure the "goodness" of a data cost by how well it matches the true distribution of flow warp error. Consistent with current practice, we find that robust versions of gradient constancy are better models than simple brightness constancy but a learned GMM that models the density of patches of warp error gives a much better fit than any existing assumption of constancy. This significant advantage of the GMM is due to an explicit modeling of the spatial structure of warp errors, a feature which is missing from almost all existing data costs in optical flow. Finally, we show how a good density model of warp error patches can be used for optical flow estimation on whole images. We replace the data cost by the expected patch log-likelihood (EPLL), and show how this cost can be optimized iteratively using an additional step of denoising the warp error image. The results of our experiments are promising and show that patch models with higher likelihood lead to better optical flow estimation.

##### Abstract (translated by Google)
光流量通常通过最小化“数据成本”和可选的正规化器来估计。虽然在不同的正规化器上已经做了许多工作，但许多现代算法仍然使用与30年前所用的数据成本差别不大的数据成本：亮度恒定性或梯度恒定性的稳健版本。在本文中，我们利用最新的地面实况光流数据库的可用性来学习数据成本。具体来说，我们采取一种生成方法，其中数据成本根据流程对图像进行变形之后对噪声的分布进行建模，我们通过与流动扭曲误差的真实分布相匹配的程度来衡量数据成本的“优劣”。与目前的实践一致，我们发现梯度稳定性的稳健版本比简单的亮度稳定性更好，但是学习GMM模型比较了任何现有的恒定性假设。 GMM的这个显着的优点是由于对扭曲误差的空间结构的明确建模，这是光流中几乎所有现有数据成本中缺少的特征。最后，我们展示了一个好的密度模型的扭曲误差补丁可以用于整个图像的光流估计。我们用预期的补丁对数似然（EPLL）来代替数据成本，并且显示如何使用额外的对经纱错误图像进行去噪的步骤迭代地优化成本。我们的实验结果是有希望的，并且表明具有较高可能性的修补模型导致更好的光流估计。

##### URL
[https://arxiv.org/abs/1604.02815](https://arxiv.org/abs/1604.02815)

##### PDF
[https://arxiv.org/pdf/1604.02815](https://arxiv.org/pdf/1604.02815)

