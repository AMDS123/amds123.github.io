---
layout: post
title: "Beyond Bilinear: Generalized Multimodal Factorized High-order Pooling for Visual Question Answering"
date: 2019-05-16 04:16:57
categories: arXiv_CV
tags: arXiv_CV QA Attention Prediction Relation VQA
author: Zhou Yu, Jun Yu, Chenchao Xiang, Jianping Fan, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Visual question answering (VQA) is challenging because it requires a simultaneous understanding of both visual content of images and textual content of questions. To support the VQA task, we need to find good solutions for the following three issues: 1) fine-grained feature representations for both the image and the question; 2) multi-modal feature fusion that is able to capture the complex interactions between multi-modal features; 3) automatic answer prediction that is able to consider the complex correlations between multiple diverse answers for the same question. For fine-grained image and question representations, a `co-attention' mechanism is developed by using a deep neural network architecture to jointly learn the attentions for both the image and the question, which can allow us to reduce the irrelevant features effectively and obtain more discriminative features for image and question representations. For multi-modal feature fusion, a generalized Multi-modal Factorized High-order pooling approach (MFH) is developed to achieve more effective fusion of multi-modal features by exploiting their correlations sufficiently, which can further result in superior VQA performance as compared with the state-of-the-art approaches. For answer prediction, the KL (Kullback-Leibler) divergence is used as the loss function to achieve precise characterization of the complex correlations between multiple diverse answers with the same or similar meaning, which can allow us to achieve faster convergence rate and obtain slightly better accuracy on answer prediction. A deep neural network architecture is designed to integrate all these aforementioned modules into a unified model for achieving superior VQA performance. With an ensemble of our MFH models, we achieve the state-of-the-art performance on the large-scale VQA datasets and win the runner-up in VQA Challenge 2017.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.03619](https://arxiv.org/abs/1708.03619)

##### PDF
[https://arxiv.org/pdf/1708.03619](https://arxiv.org/pdf/1708.03619)

