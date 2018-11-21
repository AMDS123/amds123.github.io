---
layout: post
title: "Factorized Distillation: Training Holistic Person Re-identification Model by Distilling an Ensemble of Partial ReID Models"
date: 2018-11-20 04:50:09
categories: arXiv_AI
tags: arXiv_AI Re-identification Knowledge Attention Person_Re-identification
author: Pengyuan Ren, Jianmin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (ReID) is aimed at identifying the same person across videos captured from different cameras. In the view that networks extracting global features using ordinary network architectures are difficult to extract local features due to their weak attention mechanisms, researchers have proposed a lot of elaborately designed ReID networks, while greatly improving the accuracy, the model size and the feature extraction latency are also soaring. We argue that a relatively compact ordinary network extracting globally pooled features has the capability to extract discriminative local features and can achieve state-of-the-art precision if only the model's parameters are properly learnt. In order to reduce the difficulty in learning hard identity labels, we propose a novel knowledge distillation method: Factorized Distillation, which factorizes both feature maps and retrieval features of holistic ReID network to mimic representations of multiple partial ReID models, thus transferring the knowledge from partial ReID models to the holistic network. Experiments show that the performance of model trained with the proposed method can outperform state-of-the-art with relatively few network parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08073](http://arxiv.org/abs/1811.08073)

##### PDF
[http://arxiv.org/pdf/1811.08073](http://arxiv.org/pdf/1811.08073)

