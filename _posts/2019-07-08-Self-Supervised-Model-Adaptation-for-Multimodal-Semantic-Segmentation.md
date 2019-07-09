---
layout: post
title: "Self-Supervised Model Adaptation for Multimodal Semantic Segmentation"
date: 2019-07-08 16:58:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Relation
author: Abhinav Valada, Rohit Mohan, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to reliably perceive and understand the scene is an integral enabler for robots to operate in the real-world. This problem is inherently challenging due to the multitude of object types as well as appearance changes caused by varying illumination and weather conditions. Leveraging complementary modalities can enable learning of semantically richer representations that are resilient to such perturbations. Despite the tremendous progress in recent years, most multimodal convolutional neural network approaches directly concatenate feature maps from individual modality streams rendering the model incapable of focusing only on relevant complementary information for fusion. To address this limitation, we propose a mutimodal semantic segmentation framework that dynamically adapts the fusion of modality-specific features while being sensitive to the object category, spatial location and scene context in a self-supervised manner. Specifically, we propose an architecture consisting of two modality-specific encoder streams that fuse intermediate encoder representations into a single decoder using our proposed self-supervised model adaptation fusion mechanism which optimally combines complementary features. As intermediate representations are not aligned across modalities, we introduce an attention scheme for better correlation. In addition, we propose a computationally efficient unimodal segmentation architecture termed AdapNet++ that incorporates a new encoder with multiscale residual units and an efficient atrous spatial pyramid pooling that has a larger effective receptive field with more than 10x fewer parameters, complemented with a strong decoder with a multi-resolution supervision scheme that recovers high-resolution details. Comprehensive empirical evaluations on several benchmarks demonstrate that both our unimodal and multimodal architectures achieve state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.03833](http://arxiv.org/abs/1808.03833)

##### PDF
[http://arxiv.org/pdf/1808.03833](http://arxiv.org/pdf/1808.03833)

