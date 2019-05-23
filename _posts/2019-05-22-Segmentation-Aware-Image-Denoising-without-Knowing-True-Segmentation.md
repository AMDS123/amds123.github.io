---
layout: post
title: "Segmentation-Aware Image Denoising without Knowing True Segmentation"
date: 2019-05-22 06:05:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Sicheng Wang, Bihan Wen, Junru Wu, Dacheng Tao, Zhangyang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Several recent works discussed application-driven image restoration neural networks, which are capable of not only removing noise in images but also preserving their semantic-aware details, making them suitable for various high-level computer vision tasks as the pre-processing step. However, such approaches require extra annotations for their high-level vision tasks, in order to train the joint pipeline using hybrid losses. The availability of those annotations is yet often limited to a few image sets, potentially restricting the general applicability of these methods to denoising more unseen and unannotated images. Motivated by that, we propose a segmentation-aware image denoising model dubbed U-SAID, based on a novel unsupervised approach with a pixel-wise uncertainty loss. U-SAID does not need any ground-truth segmentation map, and thus can be applied to any image dataset. It generates denoised images with comparable or even better quality, and the denoised results show stronger robustness for subsequent semantic segmentation tasks, when compared to either its supervised counterpart or classical "application-agnostic" denoisers. Moreover, we demonstrate the superior generalizability of U-SAID in three-folds, by plugging its "universal" denoiser without fine-tuning: (1) denoising unseen types of images; (2) denoising as pre-processing for segmenting unseen noisy images; and (3) denoising for unseen high-level tasks. Extensive experiments demonstrate the effectiveness, robustness and generalizability of the proposed U-SAID over various popular image sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08965](http://arxiv.org/abs/1905.08965)

##### PDF
[http://arxiv.org/pdf/1905.08965](http://arxiv.org/pdf/1905.08965)

