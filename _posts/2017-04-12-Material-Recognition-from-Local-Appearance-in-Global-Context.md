---
layout: post
title: "Material Recognition from Local Appearance in Global Context"
date: 2017-04-12 04:05:10
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Gabriel Schwartz, Ko Nishino
mathjax: true
---

* content
{:toc}

##### Abstract
Recognition of materials has proven to be a challenging problem due to the wide variation in appearance within and between categories. Global image context, such as where the material is or what object it makes up, can be crucial to recognizing the material. Existing methods, however, operate on an implicit fusion of materials and context by using large receptive fields as input (i.e., large image patches). Many recent material recognition methods treat materials as yet another set of labels like objects. Materials are, however, fundamentally different from objects as they have no inherent shape or defined spatial extent. Approaches that ignore this can only take advantage of limited implicit context as it appears during training. We instead show that recognizing materials purely from their local appearance and integrating separately recognized global contextual cues including objects and places leads to superior dense, per-pixel, material recognition. We achieve this by training a fully-convolutional material recognition network end-to-end with only material category supervision. We integrate object and place estimates to this network from independent CNNs. This approach avoids the necessity of preparing an impractically-large amount of training data to cover the product space of materials, objects, and scenes, while fully leveraging contextual cues for dense material recognition. Furthermore, we perform a detailed analysis of the effects of context granularity, spatial resolution, and the network level at which we introduce context. On a recently introduced comprehensive and diverse material database \cite{Schwartz2016}, we confirm that our method achieves state-of-the-art accuracy with significantly less training data compared to past methods.

##### Abstract (translated by Google)
材料的识别已被证明是一个具有挑战性的问题，因为在类别之内和之间的外观差异很大。全球形象背景下，如材料是什么或它构成什么对象，对于识别材料至关重要。然而，现有方法通过使用大的感受域作为输入（即，大图像片）来对材料和背景进行隐式融合。许多最近的材料识别方法将材料视为另一组标签，如物体。然而，材料与物体完全不同，因为它们没有固有的形状或限定的空间范围。忽视这一点的方法只能利用训练期间出现的有限隐式上下文。我们反过来表明，纯粹从当地的外观识别材料，并整合分离公认的全球背景线索，包括物体和地方，导致优越的密集，像素，材料的认可。我们通过仅用材料类别监督端对端地训练全卷积材料识别网络来实现这一点。我们将对象和地点估算值从独立的CNN整合到这个网络中。这种方法避免了准备大量不切实际的训练数据来覆盖材料，物体和场景的产品空间的必要性，同时充分利用上下文线索来进行高密度材料识别。此外，我们还详细分析了上下文粒度，空间分辨率以及我们引入上下文的网络级别的影响。在最近推出的全面多样化的材料数据库中，我们确认，与过去的方法相比，我们的方法能够以更少的培训数据实现最新的准确性。

##### URL
[https://arxiv.org/abs/1611.09394](https://arxiv.org/abs/1611.09394)

##### PDF
[https://arxiv.org/pdf/1611.09394](https://arxiv.org/pdf/1611.09394)

