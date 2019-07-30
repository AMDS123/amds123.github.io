---
layout: post
title: "Regularizing Proxies with Multi-Adversarial Training for Unsupervised Domain-Adaptive Semantic Segmentation"
date: 2019-07-29 08:55:22
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Semantic_Segmentation
author: Tong Shen, Dong Gong, Wei Zhang, Chunhua Shen, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Training a semantic segmentation model requires a large amount of pixel-level annotation, hampering its application at scale. With computer graphics, we can generate almost unlimited training data with precise annotation. However,a deep model trained with synthetic data usually cannot directly generalize well to realistic images due to domain shift. It has been observed that highly confident labels for the unlabeled real images may be predicted relying on the labeled synthetic data. To tackle the unsupervised domain adaptation problem, we explore the possibilities to generate high-quality labels as proxy labels to supervise the training on target data. Specifically, we propose a novel proxy-based method using multi-adversarial training. We first train the model using synthetic data (source domain). Multiple discriminators are used to align the features be-tween the source and target domain (real images) at different levels. Then we focus on obtaining and selecting high-quality proxy labels by incorporating both the confidence of the class predictor and that from the adversarial discriminators. Our discriminators not only work as a regularizer to encourage feature alignment but also provide an alternative confidence measure for generating proxy labels. Relying on the generated high-quality proxies, our model can be trained in a "supervised manner" on the target do-main. On two major tasks, GTA5-&gt;Cityscapes and SYNTHIA-&gt;Cityscapes, our method achieves state-of-the-art results, outperforming the previous by a large margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12282](http://arxiv.org/abs/1907.12282)

##### PDF
[http://arxiv.org/pdf/1907.12282](http://arxiv.org/pdf/1907.12282)

