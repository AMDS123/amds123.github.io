---
layout: post
title: "Face Photo Sketch Synthesis via Larger Patch and Multiresolution Spline"
date: 2015-09-19 14:20:50
categories: arXiv_CV
tags: arXiv_CV Attention Face
author: Xu Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Face photo sketch synthesis has got some researchers' attention in recent years because of its potential applications in digital entertainment and law enforcement. Some patches based methods have been proposed to solve this problem. These methods usually focus more on how to get a sketch patch for a given photo patch than how to blend these generated patches. However, without appropriately blending method, some jagged parts and mottled points will appear in the entire face sketch. In order to get a smoother sketch, we propose a new method to reduce such jagged parts and mottled points. In our system, we resort to an existed method, which is Markov Random Fields (MRF), to train a crude face sketch firstly. Then this crude sketch face sketch will be divided into some larger patches again and retrained by Non-Negative Matrix Factorization (NMF). At last, we use Multiresolution Spline and a blend trick named full-coverage trick to blend these retrained patches. The experiment results show that compared with some previous method, we can get a smoother face sketch.

##### Abstract (translated by Google)
由于其在数字娱乐和执法领域的潜在应用，人脸照片素描合成近年来受到了研究者的关注。已经提出了一些基于补丁的方法来解决这个问题。这些方法通常更多地关注如何为给定的照片补丁获取草图补丁，而不是如何混合这些生成的补丁。但是，如果没有适当的混合方法，整个脸部轮廓就会出现一些锯齿状的斑点和斑点。为了得到更平滑的草图，我们提出了一种新的方法来减少这种锯齿状的部分和斑点。在我们的系统中，我们采用马尔可夫随机场（Markov Random Fields，MRF）这种已有的方法，首先训练出粗糙的人脸素描。然后，这个粗略的草图脸部素描将被再次分成一些更大的补丁，并通过非负矩阵分解（NMF）进行再训练。最后，我们使用多分辨率样条和一个名为全覆盖技巧的混合技巧来混合这些重新训练的分片。实验结果表明，与以前的方法相比，可以得到更平滑的脸部轮廓。

##### URL
[https://arxiv.org/abs/1509.05897](https://arxiv.org/abs/1509.05897)

##### PDF
[https://arxiv.org/pdf/1509.05897](https://arxiv.org/pdf/1509.05897)

