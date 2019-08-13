---
layout: post
title: "SCAR: Spatial-/Channel-wise Attention Regression Networks for Crowd Counting"
date: 2019-08-10 09:20:18
categories: arXiv_CV
tags: arXiv_CV Attention
author: Junyu Gao, Qi Wang, Yuan Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, crowd counting is a hot topic in crowd analysis. Many CNN-based counting algorithms attain good performance. However, these methods only focus on the local appearance features of crowd scenes but ignore the large-range pixel-wise contextual and crowd attention information. To remedy the above problems, in this paper, we introduce the Spatial-/Channel-wise Attention Models into the traditional Regression CNN to estimate the density map, which is named as "SCAR". It consists of two modules, namely Spatial-wise Attention Model (SAM) and Channel-wise Attention Model (CAM). The former can encode the pixel-wise context of the entire image to more accurately predict density maps at the pixel level. The latter attempts to extract more discriminative features among different channels, which aids model to pay attention to the head region, the core of crowd scenes. Intuitively, CAM alleviates the mistaken estimation for background regions. Finally, two types of attention information and traditional CNN's feature maps are integrated by a concatenation operation. Furthermore, the extensive experiments are conducted on four popular datasets, Shanghai Tech Part A/B, GCC, and UCF_CC_50 Dataset. The results show that the proposed method achieves state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03716](https://arxiv.org/abs/1908.03716)

##### PDF
[https://arxiv.org/pdf/1908.03716](https://arxiv.org/pdf/1908.03716)

