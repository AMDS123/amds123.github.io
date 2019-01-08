---
layout: post
title: "Unsupervised uncertainty estimation using spatiotemporal cues in video saliency detection"
date: 2019-01-06 15:17:59
categories: arXiv_CV
tags: arXiv_CV Salient Attention Detection Relation
author: Tariq Alshawi, Zhiling Long, Ghassan AlRegib
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of quantifying reliability of computational saliency for videos, which can be used to improve saliency-based video processing and enable more reliable performance and risk assessment of such processing. Our approach is twofold. First, we explore spatial correlations in both saliency map and eye-fixation map. Then, we learn spatiotemporal correlations that define a reliable saliency map. We first study spatiotemporal eye-fixation data from a public dataset and investigate a common feature in human visual attention, which dictates correlation in saliency between a pixel and its direct neighbors. Based on the study, we then develop an algorithm that estimates a pixel-wise uncertainty map that reflects our confidence in the associated computational saliency map by relating a pixel's saliency to the saliency of its neighbors. To estimate such uncertainties, we measure the divergence of a pixel, in a saliency map, from its local neighborhood. Additionally, we propose a systematic procedure to evaluate the estimation performance by explicitly computing uncertainty ground truth as a function of a given saliency map and eye fixations of human subjects. In our experiments, we explore multiple definitions of locality and neighborhoods in spatiotemporal video signals. In addition, we examine the relationship between the parameters of our proposed algorithm and the content of the videos. The proposed algorithm is unsupervised, making it more suitable for generalization to most natural videos. Also, it is computationally efficient and flexible for customization to specific video content. Experiments using three publicly available video datasets show that the proposed algorithm outperforms state-of-the-art uncertainty estimation methods with improvement in accuracy up to 63% and offers efficiency and flexibility that make it more useful in practical situations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01550](http://arxiv.org/abs/1901.01550)

##### PDF
[http://arxiv.org/pdf/1901.01550](http://arxiv.org/pdf/1901.01550)

