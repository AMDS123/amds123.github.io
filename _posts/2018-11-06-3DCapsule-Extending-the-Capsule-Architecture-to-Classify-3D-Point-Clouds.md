---
layout: post
title: "3DCapsule: Extending the Capsule Architecture to Classify 3D Point Clouds"
date: 2018-11-06 06:57:49
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Ali Cheraghian, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces the 3DCapsule, which is a 3D extension of the recently introduced Capsule concept that makes it applicable to unordered point sets. The original Capsule relies on the existence of a spatial relationship between the elements in the feature map it is presented with, whereas in point permutation invariant formulations of 3D point set classification methods, such relationships are typically lost. Here, a new layer called ComposeCaps is introduced that, in lieu of a spatially relevant feature mapping, learns a new mapping that can be exploited by the 3DCapsule. Previous works in the 3D point set classification domain have focused on other parts of the architecture, whereas instead, the 3DCapsule is a drop-in replacement of the commonly used fully connected classifier. It is demonstrated via an ablation study, that when the 3DCapsule is applied to recent 3D point set classification architectures, it consistently shows an improvement, in particular when subjected to noisy data. Similarly, the ComposeCaps layer is evaluated and demonstrates an improvement over the baseline. In an apples-to-apples comparison against state-of-the-art methods, again, better performance is demonstrated by the 3DCapsule.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02191](https://arxiv.org/abs/1811.02191)

##### PDF
[https://arxiv.org/pdf/1811.02191](https://arxiv.org/pdf/1811.02191)

