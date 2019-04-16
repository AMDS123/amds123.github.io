---
layout: post
title: "Stack-Captioning: Coarse-to-Fine Learning for Image Captioning"
date: 2018-03-14 09:31:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Reinforcement_Learning Caption Inference Prediction
author: Jiuxiang Gu, Jianfei Cai, Gang Wang, Tsuhan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The existing image captioning approaches typically train a one-stage sentence decoder, which is difficult to generate rich fine-grained descriptions. On the other hand, multi-stage image caption model is hard to train due to the vanishing gradient problem. In this paper, we propose a coarse-to-fine multi-stage prediction framework for image captioning, composed of multiple decoders each of which operates on the output of the previous stage, producing increasingly refined image descriptions. Our proposed learning approach addresses the difficulty of vanishing gradients during training by providing a learning objective function that enforces intermediate supervisions. Particularly, we optimize our model with a reinforcement learning approach which utilizes the output of each intermediate decoder's test-time inference algorithm as well as the output of its preceding decoder to normalize the rewards, which simultaneously solves the well-known exposure bias problem and the loss-evaluation mismatch problem. We extensively evaluate the proposed approach on MSCOCO and show that our approach can achieve the state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1709.03376](https://arxiv.org/abs/1709.03376)

##### PDF
[https://arxiv.org/pdf/1709.03376](https://arxiv.org/pdf/1709.03376)

