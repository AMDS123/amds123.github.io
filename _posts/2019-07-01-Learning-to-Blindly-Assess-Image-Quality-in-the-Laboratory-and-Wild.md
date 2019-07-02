---
layout: post
title: "Learning to Blindly Assess Image Quality in the Laboratory and Wild"
date: 2019-07-01 02:31:07
categories: arXiv_CV
tags: arXiv_CV QA
author: Weixia Zhang, Kede Ma, Xiaokang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Previous models for blind image quality assessment (BIQA) can only be trained (or fine-tuned) on one subject-rated database due to the difficulty of combining multiple databases with different perceptual scales. As a result, models trained in a well-controlled laboratory environment with synthetic distortions fail to generalize to realistic distortions, whose data distribution is different. Similarly, models optimized for images captured in the wild do not account for images simulated in the laboratory. Here we describe a simple technique of training BIQA models on multiple databases simultaneously without additional subjective testing for scale realignment. Specifically, we first create and combine image pairs within individual databases, whose ground-truth binary labels are computed from the corresponding mean opinion scores, indicating which of the two images is of higher quality. We then train a deep neural network for BIQA by learning-to-rank massive such image pairs. Extensive experiments on six databases demonstrate that our BIQA method based on the proposed learning technique works well for both synthetic and realistic distortions, outperforming existing BIQA models with a single set of model parameters. The generalizability of our method is further verified by group maximum differentiation (gMAD) competition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00516](http://arxiv.org/abs/1907.00516)

##### PDF
[http://arxiv.org/pdf/1907.00516](http://arxiv.org/pdf/1907.00516)

