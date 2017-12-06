---
layout: post
title: "Self-explanatory Deep Salient Object Detection"
date: 2017-08-18 13:19:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Huaxin Xiao, Jiashi Feng, Yunchao Wei, Maojun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Salient object detection has seen remarkable progress driven by deep learning techniques. However, most of deep learning based salient object detection methods are black-box in nature and lacking in interpretability. This paper proposes the first self-explanatory saliency detection network that explicitly exploits low- and high-level features for salient object detection. We demonstrate that such supportive clues not only significantly enhances performance of salient object detection but also gives better justified detection results. More specifically, we develop a multi-stage saliency encoder to extract multi-scale features which contain both low- and high-level saliency context. Dense short- and long-range connections are introduced to reuse these features iteratively. Benefiting from the direct access to low- and high-level features, the proposed saliency encoder can not only model the object context but also preserve the boundary. Furthermore, a self-explanatory generator is proposed to interpret how the proposed saliency encoder or other deep saliency models making decisions. The generator simulates the absence of interesting features by preventing these features from contributing to the saliency classifier and estimates the corresponding saliency prediction without these features. A comparison function, saliency explanation, is defined to measure the prediction changes between deep saliency models and corresponding generator. Through visualizing the differences, we can interpret the capability of different deep neural networks based saliency detection models and demonstrate that our proposed model indeed uses more reasonable structure for salient object detection. Extensive experiments on five popular benchmark datasets and the visualized saliency explanation demonstrate that the proposed method provides new state-of-the-art.

##### Abstract (translated by Google)
显着的物体检测在深度学习技术的驱动下取得了显着的进步。然而，大多数基于深度学习的显着物体检测方法本质上是黑盒子的，缺乏可解释性。本文提出了第一个自明显的显着性检测网络，明确地利用低级和高级特征进行显着物体检测。我们证明这样的支持性线索不仅显着提高了显着物体检测的性能，而且还提供了更好的合理检测结果。更具体地说，我们开发了一个多级显着性编码器来​​提取包含低级和高级显着性上下文的多尺度特征。引入密集的短程和长程连接以迭代地重用这些特征。得益于直接访问低级和高级特征，所提出的显着性编码器不仅可以对对象上下文进行建模，而且还可以保持边界。此外，提出了一个自解释发生器来解释如何提出显着性编码器或其他深度显着性模型作出决定。生成器通过防止这些特征贡献给显着性分类器并估计没有这些特征的相应的显着性预测来模拟缺少有趣的特征。定义比较函数，显着性解释，以测量深显着性模型和相应的发生器之间的预测变化。通过可视化的差异，我们可以解释基于不同深度神经网络的显着性检测模型的能力，并证明我们提出的模型确实使用更合理的结构进行显着的对象检测。五个流行的基准数据集和可视化显着性解释的广泛实验证明了所提出的方法提供了新的最新技术。

##### URL
[https://arxiv.org/abs/1708.05595](https://arxiv.org/abs/1708.05595)

