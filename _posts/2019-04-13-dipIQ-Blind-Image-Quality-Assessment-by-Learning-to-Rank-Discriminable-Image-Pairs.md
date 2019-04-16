---
layout: post
title: "dipIQ: Blind Image Quality Assessment by Learning-to-Rank Discriminable Image Pairs"
date: 2019-04-13 08:25:54
categories: arXiv_CV
tags: arXiv_CV QA GAN
author: Kede Ma, Wentao Liu, Tongliang Liu, Zhou Wang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Objective assessment of image quality is fundamentally important in many image processing tasks. In this work, we focus on learning blind image quality assessment (BIQA) models which predict the quality of a digital image with no access to its original pristine-quality counterpart as reference. One of the biggest challenges in learning BIQA models is the conflict between the gigantic image space (which is in the dimension of the number of image pixels) and the extremely limited reliable ground truth data for training. Such data are typically collected via subjective testing, which is cumbersome, slow, and expensive. Here we first show that a vast amount of reliable training data in the form of quality-discriminable image pairs (DIP) can be obtained automatically at low cost by exploiting large-scale databases with diverse image content. We then learn an opinion-unaware BIQA (OU-BIQA, meaning that no subjective opinions are used for training) model using RankNet, a pairwise learning-to-rank (L2R) algorithm, from millions of DIPs, each associated with a perceptual uncertainty level, leading to a DIP inferred quality (dipIQ) index. Extensive experiments on four benchmark IQA databases demonstrate that dipIQ outperforms state-of-the-art OU-BIQA models. The robustness of dipIQ is also significantly improved as confirmed by the group MAximum Differentiation (gMAD) competition method. Furthermore, we extend the proposed framework by learning models with ListNet (a listwise L2R algorithm) on quality-discriminable image lists (DIL). The resulting DIL Inferred Quality (dilIQ) index achieves an additional performance gain.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06505](http://arxiv.org/abs/1904.06505)

##### PDF
[http://arxiv.org/pdf/1904.06505](http://arxiv.org/pdf/1904.06505)

