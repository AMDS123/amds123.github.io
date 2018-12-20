---
layout: post
title: "A Two-Stream Mutual Attention Network for Semi-supervised Biomedical Segmentation with Noisy Labels"
date: 2018-12-19 08:56:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: haobo Min, Xuejin Chen, Zheng-Jun Zha, Feng Wu, Yongdong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
\begin{abstract} Learning-based methods suffer from a deficiency of clean annotations, especially in biomedical segmentation. Although many semi-supervised methods have been proposed to provide extra training data, automatically generated labels are usually too noisy to retrain models effectively. In this paper, we propose a Two-Stream Mutual Attention Network (TSMAN) that weakens the influence of back-propagated gradients caused by incorrect labels, thereby rendering the network robust to unclean data. The proposed TSMAN consists of two sub-networks that are connected by three types of attention models in different layers. The target of each attention model is to indicate potentially incorrect gradients in a certain layer for both sub-networks by analyzing their inferred features using the same input. In order to achieve this purpose, the attention models are designed based on the propagation analysis of noisy gradients at different layers. This allows the attention models to effectively discover incorrect labels and weaken their influence during the parameter updating process. By exchanging multi-level features within the two-stream architecture, the effects of noisy labels in each sub-network are reduced by decreasing the updating gradients. Furthermore, a hierarchical distillation is developed to provide more reliable pseudo labels for unlabelded data, which further boosts the performance of our retrained TSMAN. The experiments using both the HVSMR 2016 and BRATS 2015 benchmarks demonstrate that our semi-supervised learning framework surpasses the state-of-the-art fully-supervised results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.11719](http://arxiv.org/abs/1807.11719)

##### PDF
[http://arxiv.org/pdf/1807.11719](http://arxiv.org/pdf/1807.11719)

