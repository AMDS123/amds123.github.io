---
layout: post
title: "VideoStory Embeddings Recognize Events when Examples are Scarce"
date: 2015-11-08 14:59:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Embedding Detection Relation Recognition
author: Amirhossein Habibian, Thomas Mensink, Cees G.M. Snoek
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims for event recognition when video examples are scarce or even completely absent. The key in such a challenging setting is a semantic video representation. Rather than building the representation from individual attribute detectors and their annotations, we propose to learn the entire representation from freely available web videos and their descriptions using an embedding between video features and term vectors. In our proposed embedding, which we call VideoStory, the correlations between the terms are utilized to learn a more effective representation by optimizing a joint objective balancing descriptiveness and predictability.We show how learning the VideoStory using a multimodal predictability loss, including appearance, motion and audio features, results in a better predictable representation. We also propose a variant of VideoStory to recognize an event in video from just the important terms in a text query by introducing a term sensitive descriptiveness loss. Our experiments on three challenging collections of web videos from the NIST TRECVID Multimedia Event Detection and Columbia Consumer Videos datasets demonstrate: i) the advantages of VideoStory over representations using attributes or alternative embeddings, ii) the benefit of fusing video modalities by an embedding over common strategies, iii) the complementarity of term sensitive descriptiveness and multimodal predictability for event recognition without examples. By it abilities to improve predictability upon any underlying video feature while at the same time maximizing semantic descriptiveness, VideoStory leads to state-of-the-art accuracy for both few- and zero-example recognition of events in video.

##### Abstract (translated by Google)
当视频例子稀缺甚至完全不存在时，本文旨在进行事件识别。在这样具有挑战性的环境中的关键是语义视频表示。我们建议使用视频特征和术语向量之间的嵌入来从免费可用的网络视频及其描述中学习整个表示，而不是从个体属性检测器及其注释中构建表示。在我们提出的被称为VideoStory的嵌入中，通过优化联合目标平衡描述性和可预测性来利用术语之间的相关性来学习更有效的表示。我们展示了如何使用多模态可预测性损失来学习VideoStory，包括外观，运动和音频功能，导致更好的可预测的表示。我们还提出了一个VideoStory的变体，通过引入一个术语敏感的描述性丢失来从文本查询中的重要术语中识别视频中的事件。我们对来自NIST TRECVID多媒体事件检测和哥伦比亚消费者视频数据集的三个具有挑战性的网络视频集合的实验证明：i）VideoStory优于使用属性或替代嵌入的表示; ii）通过嵌入常见视频策略，iii）术语敏感性描述性和事件识别的多模式可预测性的互补性而没有例子。通过它能够提高对任何基础视频特征的可预测性，同时最大化语义描述性，VideoStory可以为视频中事件的少和零示例识别提供最先进的准确性。

##### URL
[https://arxiv.org/abs/1511.02492](https://arxiv.org/abs/1511.02492)

##### PDF
[https://arxiv.org/pdf/1511.02492](https://arxiv.org/pdf/1511.02492)

