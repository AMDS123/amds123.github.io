---
layout: post
title: "Towards Flops-constrained Face Recognition"
date: 2019-09-02 09:42:52
categories: arXiv_CV
tags: arXiv_CV QA Face Optimization Recognition Face_Recognition
author: Yu Liu, Guanglu Song, Manyuan Zhang, Jihao Liu, Yucong Zhou, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale face recognition is challenging especially when the computational budget is limited. Given a \textit{flops} upper bound, the key is to find the optimal neural network architecture and optimization method. In this article, we briefly introduce the solutions of team 'trojans' for the ICCV19 - Lightweight Face Recognition Challenge~\cite{lfr}. The challenge requires each submission to be one single model with the computational budget no higher than 30 GFlops. We introduce a searched network architecture `Efficient PolyFace' based on the Flops constraint, a novel loss function `ArcNegFace', a novel frame aggregation method `QAN++', together with a bag of useful tricks in our implementation (augmentations, regular face, label smoothing, anchor finetuning, etc.). Our basic model, `Efficient PolyFace', takes 28.25 Gflops for the `deepglint-large' image-based track, and the `PolyFace+QAN++' solution takes 24.12 Gflops for the `iQiyi-large' video-based track. These two solutions achieve 94.198\% @ 1e-8 and 72.981\% @ 1e-4 in the two tracks respectively, which are the state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00632](http://arxiv.org/abs/1909.00632)

##### PDF
[http://arxiv.org/pdf/1909.00632](http://arxiv.org/pdf/1909.00632)

