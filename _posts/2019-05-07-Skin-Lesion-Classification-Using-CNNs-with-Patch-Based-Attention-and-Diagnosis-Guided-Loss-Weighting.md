---
layout: post
title: "Skin Lesion Classification Using CNNs with Patch-Based Attention and Diagnosis-Guided Loss Weighting"
date: 2019-05-07 20:04:20
categories: arXiv_CV
tags: arXiv_CV Attention Image_Classification Classification
author: Nils Gessert, Thilo Sentker, Frederic Madesta, R&#xfc;diger Schmitz, Helge Kniep, Ivo Baltruschat, Ren&#xe9; Werner
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: This work addresses two key problems of skin lesion classification. The first problem is the effective use of high-resolution images with pretrained standard architectures for image classification. The second problem is the high class imbalance encountered in real-world multi-class datasets. Methods: To use high-resolution images, we propose a novel patch-based attention architecture that provides global context between small, high-resolution patches. We modify three pretrained architectures and study the performance of patch-based attention. To counter class imbalance problems, we compare oversampling, balanced batch sampling, and class-specific loss weighting. Additionally, we propose a novel diagnosis-guided loss weighting method which takes the method used for ground-truth annotation into account. Results: Our patch-based attention mechanism outperforms previous methods and improves the mean sensitivity by 7%. Class balancing significantly improves the mean sensitivity and we show that our diagnosis-guided loss weighting method improves the mean sensitivity by 3% over normal loss balancing. Conclusion: The novel patch-based attention mechanism can be integrated into pretrained architectures and provides global context between local patches while outperforming other patch-based methods. Hence, pretrained architectures can be readily used with high-resolution images without downsampling. The new diagnosis-guided loss weighting method outperforms other methods and allows for effective training when facing class imbalance. Significance: The proposed methods improve automatic skin lesion classification. They can be extended to other clinical applications where high-resolution image data and class imbalance are relevant.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02793](http://arxiv.org/abs/1905.02793)

##### PDF
[http://arxiv.org/pdf/1905.02793](http://arxiv.org/pdf/1905.02793)

