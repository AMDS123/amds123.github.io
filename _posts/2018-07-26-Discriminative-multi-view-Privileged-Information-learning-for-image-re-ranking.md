---
layout: post
title: "Discriminative multi-view Privileged Information learning for image re-ranking"
date: 2018-07-26 18:57:14
categories: arXiv_CV
tags: arXiv_CV Image_Caption Embedding
author: Jun Li, Chang Xu, Wankou Yang, Changyin Sun, Dacheng Tao, Hong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional multi-view re-ranking methods usually perform asymmetrical matching between the region of interest (ROI) in the query image and the whole target image for similarity computation. Due to the inconsistency in the visual appearance, this practice tends to degrade the retrieval accuracy particularly when the image ROI, which is usually interpreted as the image objectness, accounts for a smaller region in the image. Since Privileged Information (PI), which can be viewed as the image prior, enables well characterizing the image objectness, we are aiming at leveraging PI for further improving the performance of the multi-view re-ranking accuracy in this paper. Towards this end, we propose a discriminative multi-view re-ranking approach in which both the original global image visual contents and the local auxiliary PI features are simultaneously integrated into a unified training framework for generating the latent subspaces with sufficient discriminating power. For the on-the-fly re-ranking, since the multi-view PI features are unavailable, we only project the original multi-view image representations onto the latent subspace, and thus the re-ranking can be achieved by computing and sorting the distances from the multi-view embeddings to the separating hyperplane. Extensive experimental evaluations on the two public benchmarks Oxford5k and Paris6k reveal our approach provides further performance boost for accurate image re-ranking, whilst the comparative study demonstrates the advantage of our method against other multi-view re-ranking methods.

##### Abstract (translated by Google)
传统的多视图重新排序方法通常执行查询图像中的感兴趣区域（ROI）与用于相似性计算的整个目标图像之间的不对称匹配。由于视觉外观的不一致性，这种做法倾向于降低检索精度，特别是当图像ROI（通常被解释为图像对象性）占图像中的较小区域时。由于特权信息（PI）可以被视为先前的图像，因此可以很好地表征图像对象，我们的目标是利用PI进一步提高本文中多视图重新排序精度的性能。为此，我们提出了一种判别性多视图重新排序方法，其中原始全局图像视觉内容和本地辅助PI特征同时被集成到统一训练框架中，用于生成具有足够区分能力的潜在子空间。对于即时重新排名，由于多视图PI特征不可用，我们仅将原始多视图图像表示投影到潜在子空间上，因此可以通过计算和排序来实现重新排序。从多视图嵌入到分离超平面的距离。对Oxford5k和Paris6k两个公共基准的广泛实验评估表明，我们的方法为准确的图像重新排序提供了进一步的性能提升，而比较研究证明了我们的方法对其他多视图重新排序方法的优势。

##### URL
[http://arxiv.org/abs/1808.04437](http://arxiv.org/abs/1808.04437)

##### PDF
[http://arxiv.org/pdf/1808.04437](http://arxiv.org/pdf/1808.04437)

