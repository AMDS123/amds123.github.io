---
layout: post
title: "SFCN-OPI: Detection and Fine-grained Classification of Nuclei Using Sibling FCN with Objectness Prior Interaction"
date: 2017-12-22 03:56:56
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Yanning Zhou, Qi Dou, Hao Chen, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Cell nuclei detection and fine-grained classification have been fundamental yet challenging problems in histopathology image analysis. Due to the nuclei tiny size, significant inter-/intra-class variances, as well as the inferior image quality, previous automated methods would easily suffer from limited accuracy and robustness. In the meanwhile, existing approaches usually deal with these two tasks independently, which would neglect the close relatedness of them. In this paper, we present a novel method of sibling fully convolutional network with prior objectness interaction (called SFCN-OPI) to tackle the two tasks simultaneously and interactively using a unified end-to-end framework. Specifically, the sibling FCN branches share features in earlier layers while holding respective higher layers for specific tasks. More importantly, the detection branch outputs the objectness prior which dynamically interacts with the fine-grained classification sibling branch during the training and testing processes. With this mechanism, the fine-grained classification successfully focuses on regions with high confidence of nuclei existence and outputs the conditional probability, which in turn benefits the detection through back propagation. Extensive experiments on colon cancer histology images have validated the effectiveness of our proposed SFCN-OPI and our method has outperformed the state-of-the-art methods by a large margin.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.08297](https://arxiv.org/abs/1712.08297)

##### PDF
[https://arxiv.org/pdf/1712.08297](https://arxiv.org/pdf/1712.08297)

