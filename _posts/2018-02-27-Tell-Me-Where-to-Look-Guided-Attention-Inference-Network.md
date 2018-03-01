---
layout: post
title: "Tell Me Where to Look: Guided Attention Inference Network"
date: 2018-02-27 21:17:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Weakly_Supervised Semantic_Segmentation Inference
author: Kunpeng Li, Ziyan Wu, Kuan-Chuan Peng, Jan Ernst, Yun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised learning with only coarse labels can obtain visual explanations of deep neural network such as attention maps by back-propagating gradients. These attention maps are then available as priors for tasks such as object localization and semantic segmentation. In one common framework we address three shortcomings of previous approaches in modeling such attention maps: We (1) first time make attention maps an explicit and natural component of the end-to-end training, (2) provide self-guidance directly on these maps by exploring supervision form the network itself to improve them, and (3) seamlessly bridge the gap between using weak and extra supervision if available. Despite its simplicity, experiments on the semantic segmentation task demonstrate the effectiveness of our methods. We clearly surpass the state-of-the-art on Pascal VOC 2012 val. and test set. Besides, the proposed framework provides a way not only explaining the focus of the learner but also feeding back with direct guidance towards specific tasks. Under mild assumptions our method can also be understood as a plug-in to existing weakly supervised learners to improve their generalization performance.

##### Abstract (translated by Google)
只有粗糙标签的弱监督学习可以通过反向传播梯度获得深度神经网络的视觉解释，例如注意力图。这些注意图随后可用作对象本地化和语义分割等任务的先驱。在一个共同的框架中，我们解决了以往方法在建模这些注意图时存在的三个缺点：我们（1）第一次让注意图成为端到端培训的一个显而易见和自然的组成部分，（2）直接为这些注意图提供自我指导通过探索网络本身的监督来改进它们;（3）无缝地弥合使用弱监督和额外监督（如果有的话）之间的差距。尽管简单，但语义分割任务的实验证明了我们方法的有效性。我们明显超越了Pascal VOC 2012 val的最新技术水平。和测试集。此外，提出的框架不仅可以解释学习者的重点，还可以反馈直接指导具体任务。在温和假设下，我们的方法也可以理解为现有弱监督学习者的插件，以提高其泛化性能。

##### URL
[http://arxiv.org/abs/1802.10171](http://arxiv.org/abs/1802.10171)

##### PDF
[http://arxiv.org/pdf/1802.10171](http://arxiv.org/pdf/1802.10171)

