---
layout: post
title: "Channel Splitting Network for Single MR Image Super-Resolution"
date: 2018-10-15 15:15:16
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Deep_Learning
author: Xiaole Zhao, Yulun Zhang, Tao Zhang, Xueming Zou
mathjax: true
---

* content
{:toc}

##### Abstract
High resolution magnetic resonance (MR) imaging is desirable in many clinical applications due to its contribution to more accurate subsequent analyses and early clinical diagnoses. Single image super resolution (SISR) is an effective and cost efficient alternative technique to improve the spatial resolution of MR images. In the past few years, SISR methods based on deep learning techniques, especially convolutional neural networks (CNNs), have achieved state-of-the-art performance on natural images. However, the information is gradually weakened and training becomes increasingly difficult as the network deepens. The problem is more serious for medical images because lacking high quality and effective training samples makes deep models prone to underfitting or overfitting. Nevertheless, many current models treat the hierarchical features on different channels equivalently, which is not helpful for the models to deal with the hierarchical features discriminatively and targetedly. To this end, we present a novel channel splitting network (CSN) to ease the representational burden of deep models. The proposed CSN model divides the hierarchical features into two branches, i.e., residual branch and dense branch, with different information transmissions. The residual branch is able to promote feature reuse, while the dense branch is beneficial to the exploration of new features. Besides, we also adopt the merge-and-run mapping to facilitate information integration between different branches. Extensive experiments on various MR images, including proton density (PD), T1 and T2 images, show that the proposed CSN model achieves superior performance over other state-of-the-art SISR methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.06453](https://arxiv.org/abs/1810.06453)

##### PDF
[https://arxiv.org/pdf/1810.06453](https://arxiv.org/pdf/1810.06453)

