---
layout: post
title: "Unsupervised Learning of Landmarks by Descriptor Vector Exchange"
date: 2019-08-18 11:35:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection
author: James Thewlis, Samuel Albanie, Hakan Bilen, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
Equivariance to random image transformations is an effective method to learn landmarks of object categories, such as the eyes and the nose in faces, without manual supervision. However, this method does not explicitly guarantee that the learned landmarks are consistent with changes between different instances of the same object, such as different facial identities. In this paper, we develop a new perspective on the equivariance approach by noting that dense landmark detectors can be interpreted as local image descriptors equipped with invariance to intra-category variations. We then propose a direct method to enforce such an invariance in the standard equivariant loss. We do so by exchanging descriptor vectors between images of different object instances prior to matching them geometrically. In this manner, the same vectors must work regardless of the specific object identity considered. We use this approach to learn vectors that can simultaneously be interpreted as local descriptors and dense landmarks, combining the advantages of both. Experiments on standard benchmarks show that this approach can match, and in some cases surpass state-of-the-art performance amongst existing methods that learn landmarks without supervision. Code is available at www.robots.ox.ac.uk/~vgg/research/DVE/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06427](http://arxiv.org/abs/1908.06427)

##### PDF
[http://arxiv.org/pdf/1908.06427](http://arxiv.org/pdf/1908.06427)

