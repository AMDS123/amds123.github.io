---
layout: post
title: "Interpretability Beyond Classification Output: Semantic Bottleneck Networks"
date: 2019-07-25 07:53:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning Prediction
author: Max Losch, Mario Fritz, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Today's deep learning systems deliver high performance based on end-to-end training. While they deliver strong performance, these systems are hard to interpret. To address this issue, we propose Semantic Bottleneck Networks (SBN): deep networks with semantically interpretable intermediate layers that all downstream results are based on. As a consequence, the analysis on what the final prediction is based on is transparent to the engineer and failure cases and modes can be analyzed and avoided by high-level reasoning. We present a case study on street scene segmentation to demonstrate the feasibility and power of SBN. In particular, we start from a well performing classic deep network which we adapt to house a SB-Layer containing task related semantic concepts (such as object-parts and materials). Importantly, we can recover state of the art performance despite a drastic dimensionality reduction from 1000s (non-semantic feature) to 10s (semantic concept) channels. Additionally we show how the activations of the SB-Layer can be used for both the interpretation of failure cases of the network as well as for confidence prediction of the resulting output. For the first time, e.g., we show interpretable segmentation results for most predictions at over 99% accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10882](http://arxiv.org/abs/1907.10882)

##### PDF
[http://arxiv.org/pdf/1907.10882](http://arxiv.org/pdf/1907.10882)

