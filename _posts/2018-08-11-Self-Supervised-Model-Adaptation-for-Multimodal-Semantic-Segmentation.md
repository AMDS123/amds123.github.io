---
layout: post
title: "Self-Supervised Model Adaptation for Multimodal Semantic Segmentation"
date: 2018-08-11 16:36:38
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
学会可靠地感知和理解场景是机器人在现实世界中运行的不可或缺的一部分。由于多种物体类型以及由变化的照明和天气条件引起的外观变化，该问题本质上具有挑战性。利用互补模态可以学习对这种扰动具有弹性的语义更丰富的表示。尽管近年来取得了巨大进步，但大多数多模式卷积神经网络方法直接连接来自各个模态流的特征图，使得该模型不能仅仅关注用于融合的相关补充信息。为了解决这个限制，我们提出了一种多模态语义分割框架，该框架动态地适应模态特定特征的融合，同时以自我监督的方式对对象类别，空间位置和场景上下文敏感。具体来说，我们提出了一种由两个模态特定的编码器流组成的体系结构，它使用我们提出的自我监督模型自适应融合机制将中间编码器表示融合到单个解码器中，该机制最佳地组合了互补特征。由于中间表示不是跨模态对齐的，我们引入了一种注意方案以获得更好的相关性。此外，我们提出了一种计算效率高的单峰分割架构，称为AdapNet ++，它结合了具有多尺度残差单元的新编码器和有效的有害空间金字塔池，其具有更大的有效感受域，参数减少10倍以上，并辅以强大的解码器和多分辨率监督方案，恢复高分辨率细节。对几个基准测试的全面实证评估表明，我们的单峰和多模式架构都实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1808.03833](http://arxiv.org/abs/1808.03833)

##### PDF
[http://arxiv.org/pdf/1808.03833](http://arxiv.org/pdf/1808.03833)

