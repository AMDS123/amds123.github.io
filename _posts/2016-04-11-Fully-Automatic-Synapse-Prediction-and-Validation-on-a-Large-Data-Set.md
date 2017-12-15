---
layout: post
title: "Fully-Automatic Synapse Prediction and Validation on a Large Data Set"
date: 2016-04-11 19:25:44
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Detection
author: Gary B. Huang, Louis K. Scheffer, Stephen M. Plaza
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting a connectome from an electron microscopy (EM) data set requires identification of neurons and determination of synapses between neurons. As manual extraction of this information is very time-consuming, there has been extensive research effort to automatically segment the neurons to help guide and eventually replace manual tracing. Until recently, there has been comparatively less research on automatically detecting the actual synapses between neurons. This discrepancy can, in part, be attributed to several factors: obtaining neuronal shapes is a prerequisite first step in extracting a connectome, manual tracing is much more time-consuming than annotating synapses, and neuronal contact area can be used as a proxy for synapses in determining connections. However, recent research has demonstrated that contact area alone is not a sufficient predictor of synaptic connection. Moreover, as segmentation has improved, we have observed that synapse annotation is consuming a more significant fraction of overall reconstruction time. This ratio will only get worse as segmentation improves, gating overall possible speed-up. Therefore, we address this problem by developing algorithms that automatically detect pre-synaptic neurons and their post-synaptic partners. In particular, pre-synaptic structures are detected using a Deep and Wide Multiscale Recursive Network, and post-synaptic partners are detected using a MLP with features conditioned on the local segmentation. This work is novel because it requires minimal amount of training, leverages advances in image segmentation directly, and provides a complete solution for polyadic synapse detection. We further introduce novel metrics to evaluate our algorithm on connectomes of meaningful size. These metrics demonstrate that complete automatic prediction can be used to effectively characterize most connectivity correctly.

##### Abstract (translated by Google)
从电子显微镜（EM）数据集中提取连接体需要鉴定神经元并确定神经元之间的突触。由于这些信息的手工提取非常耗时，因此已经进行了大量的研究工作来自动分割神经元来帮助指导并最终取代手动跟踪。直到最近，在自动检测神经元之间的实际突触方面的研究相对较少。这种差异部分可以归因于几个因素：获取神经元形状是提取连接体的先决条件，手工描绘比注释突触要耗费更多的时间，并且神经元接触面积可以用作突触的代理在确定连接。然而，最近的研究表明，接触面积本身并不足以预测突触联系。此外，随着细分已经改善，我们已经观察到突触诠释消耗整个重建时间的更重要的部分。这个比例只会随着分段的改善而变差，从而可能会加快整体速度。因此，我们通过开发自动检测突触前神经元及其突触后配偶的算法来解决这个问题。特别地，使用深度和宽度多尺度递归网络来检测突触前结构，并且使用MLP来检测突触后合作伙伴，其特征在于局部分割。这项工作是新颖的，因为它需要最少量的训练，直接利用图像分割的进步，并为多边突触检测提供了一个完整的解决方案。我们进一步引入新颖的度量来评估我们的算法在有意义大小的connectome上。这些指标表明，可以使用完整的自动预测来正确有效地表征大多数连接。

##### URL
[https://arxiv.org/abs/1604.03075](https://arxiv.org/abs/1604.03075)

##### PDF
[https://arxiv.org/pdf/1604.03075](https://arxiv.org/pdf/1604.03075)

