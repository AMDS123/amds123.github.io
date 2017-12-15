---
layout: post
title: "Reinforcement Learning for Semantic Segmentation in Indoor Scenes"
date: 2016-06-03 16:35:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Reinforcement_Learning Semantic_Segmentation
author: Md. Alimoor Reza, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
Future advancements in robot autonomy and sophistication of robotics tasks rest on robust, efficient, and task-dependent semantic understanding of the environment. Semantic segmentation is the problem of simultaneous segmentation and categorization of a partition of sensory data. The majority of current approaches tackle this using multi-class segmentation and labeling in a Conditional Random Field (CRF) framework or by generating multiple object hypotheses and combining them sequentially. In practical settings, the subset of semantic labels that are needed depend on the task and particular scene and labelling every single pixel is not always necessary. We pursue these observations in developing a more modular and flexible approach to multi-class parsing of RGBD data based on learning strategies for combining independent binary object-vs-background segmentations in place of the usual monolithic multi-label CRF approach. Parameters for the independent binary segmentation models can be learned very efficiently, and the combination strategy---learned using reinforcement learning---can be set independently and can vary over different tasks and environments. Accuracy is comparable to state-of-art methods on a subset of the NYU-V2 dataset of indoor scenes, while providing additional flexibility and modularity.

##### Abstract (translated by Google)
机器人自主性和机器人任务复杂性的未来发展取决于对环境的强大，高效和依赖于任务的语义理解。语义分割是感知数据划分的同时分割和分类的问题。目前的大多数方法在条件随机场（CRF）框架中使用多类别分割和标记或者通过生成多个对象假设并将其依次组合来解决这个问题。在实际设置中，需要的语义标签的子集取决于任务和特定的场景，并且标记每个单个像素并不总是必要的。我们在开发更模块化和更灵活的方法的基础上，开发了一种更加模块化和灵活的方法来对RGBD数据进行多级分析，这种方法基于学习策略，将独立的二进制对象与背景分割相结合，代替通常的单片多标签CRF方法。可以非常有效地学习独立二进制分割模型的参数，并且使用强化学习学习的组合策略可以独立设置，并且可以在不同的任务和环境中变化。在室内场景的NYU-V2数据集的一个子集上，精度与先进的方法相当，同时提供了额外的灵活性和模块性。

##### URL
[https://arxiv.org/abs/1606.01178](https://arxiv.org/abs/1606.01178)

##### PDF
[https://arxiv.org/pdf/1606.01178](https://arxiv.org/pdf/1606.01178)

