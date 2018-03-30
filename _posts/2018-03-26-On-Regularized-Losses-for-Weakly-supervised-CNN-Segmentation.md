---
layout: post
title: "On Regularized Losses for Weakly-supervised CNN Segmentation"
date: 2018-03-26 13:14:58
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Semantic_Segmentation Inference Deep_Learning
author: Meng Tang, Federico Perazzi, Abdelaziz Djelouah, Ismail Ben Ayed, Christopher Schroers, Yuri Boykov
mathjax: true
---

* content
{:toc}

##### Abstract
Minimization of regularized losses is a principled approach to weak supervision well-established in deep learning, in general. However, it is largely overlooked in semantic segmentation currently dominated by methods mimicking full supervision via "fake" fully-labeled training masks (proposals) generated from available partial input. To obtain such full masks the typical methods explicitly use standard regularization techniques for "shallow" segmentation, e.g. graph cuts or dense CRFs. In contrast, we integrate such standard regularizers directly into the loss functions over partial input. This approach simplifies weakly-supervised training by avoiding extra MRF/CRF inference steps or layers explicitly generating full masks, while improving both the quality and efficiency of training. This paper proposes and experimentally compares different losses integrating MRF/CRF regularization terms. We juxtapose our regularized losses with earlier proposal-generation methods using explicit regularization steps or layers. Our approach achieves state-of-the-art accuracy in semantic segmentation with near full-supervision quality.

##### Abstract (translated by Google)
一般而言，规范化损失最小化是深度学习中弱势监管的原则性方法。然而，在目前由模仿全面监督的方法主导的语义分割中，很大程度上被忽视，这些方法通过从可用的部分输入生成的“假”完全标记的训练掩码（提议）进行。为了获得这种完整的掩码，典型的方法明确地使用标准正则化技术进行“浅”分割，例如，图形切割或密集的CRF。相比之下，我们将这些标准规范化器直接集成到部分输入的损失函数中。这种方法通过避免额外的MRF / CRF推断步骤或层明确生成完整的蒙版，简化了弱监督培训，同时提高了培训的质量和效率。本文提出并实验性地比较了不同的损失整合MRF / CRF正则化术语。我们使用明确的正则化步骤或层将我们的正则化损失与较早的提案生成方法并置。我们的方法在接近全监督质量的情况下实现了语义分割的最新准确性。

##### URL
[https://arxiv.org/abs/1803.09569](https://arxiv.org/abs/1803.09569)

##### PDF
[https://arxiv.org/pdf/1803.09569](https://arxiv.org/pdf/1803.09569)

