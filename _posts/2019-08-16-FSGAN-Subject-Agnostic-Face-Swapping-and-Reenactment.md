---
layout: post
title: "FSGAN: Subject Agnostic Face Swapping and Reenactment"
date: 2019-08-16 11:16:22
categories: arXiv_CV
tags: arXiv_CV GAN Face Optimization RNN Quantitative
author: Yuval Nirkin, Yosi Keller, Tal Hassner
mathjax: true
---

* content
{:toc}

##### Abstract
We present Face Swapping GAN (FSGAN) for face swapping and reenactment. Unlike previous work, FSGAN is subject agnostic and can be applied to pairs of faces without requiring training on those faces. To this end, we describe a number of technical contributions. We derive a novel recurrent neural network (RNN)-based approach for face reenactment which adjusts for both pose and expression variations and can be applied to a single image or a video sequence. For video sequences, we introduce continuous interpolation of the face views based on reenactment, Delaunay Triangulation, and barycentric coordinates. Occluded face regions are handled by a face completion network. Finally, we use a face blending network for seamless blending of the two faces while preserving target skin color and lighting conditions. This network uses a novel Poisson blending loss which combines Poisson optimization with perceptual loss. We compare our approach to existing state-of-the-art systems and show our results to be both qualitatively and quantitatively superior.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05932](https://arxiv.org/abs/1908.05932)

##### PDF
[https://arxiv.org/pdf/1908.05932](https://arxiv.org/pdf/1908.05932)

