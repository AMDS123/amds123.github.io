---
layout: post
title: "Deep neural networks can be improved using human-derived contextual expectations"
date: 2018-03-29 00:59:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Harish Katti, Marius V. Peelen, S. P. Arun
mathjax: true
---

* content
{:toc}

##### Abstract
Real-world objects occur in specific contexts. Such context has been shown to facilitate detection by constraining the locations to search. But can context directly benefit object detection? To do so, context needs to be learned independently from target features. This is impossible in traditional object detection where classifiers are trained on images containing both target features and surrounding context. In contrast, humans can learn context and target features separately, such as when we see highways without cars. Here we show for the first time that human-derived scene expectations can be used to improve object detection performance in machines. To measure contextual expectations, we asked human subjects to indicate the scale, location and likelihood at which cars or people might occur in scenes without these objects. Humans showed highly systematic expectations that we could accurately predict using scene features. This allowed us to predict human expectations on novel scenes without requiring manual annotation. On augmenting deep neural networks with predicted human expectations, we obtained substantial gains in accuracy for detecting cars and people (1-3%) as well as on detecting associated objects (3-20%). In contrast, augmenting deep networks with other conventional features yielded far smaller gains. This improvement was due to relatively poor matches at highly likely locations being correctly labelled as target and conversely strong matches at unlikely locations being correctly rejected as false alarms. Taken together, our results show that augmenting deep neural networks with human-derived context features improves their performance, suggesting that humans learn scene context separately unlike deep networks.

##### Abstract (translated by Google)
真实世界的对象出现在特定的上下文中。已经显示这样的上下文通过限制要搜索的位置来促进检测。但是上下文可以直接受益于对象检测？为此，上下文需要独立于目标特征来学习。在传统的对象检测中这是不可能的，其中分类器在包含目标特征和周围上下文的图像上训练。相比之下，人类可以分别学习背景和目标特征，例如当我们看到没有汽车的高速公路时。在这里，我们首次展示了人类派生的场景期望可以用来改善机器中的物体检测性能。为了测量情境期望，我们要求人类受试者指出在没有这些物体的场景中可能出现汽车或人的规模，位置和可能性。人类表现出高度系统性的期望，我们可以准确预测使用场景特征。这使我们能够在不需要手动注释的情况下预测人们对新颖场景的期望。在预测人类预期的深度神经网络方面，我们在检测汽车和人（1-3％）以及检测相关物体（3-20％）方面获得了显着的准确性。相比之下，使用其他传统特性增强深度网络的增益要小得多。这种改进是由于相当差的匹配在很可能的位置被正确标记为目标，相反，在不可能的位置处的强匹配被正确拒绝为假警报。综合起来，我们的研究结果表明，用人类派生的背景特征增强深度神经网络可以提高他们的表现，这表明人类不同于深度网络学习场景背景。

##### URL
[http://arxiv.org/abs/1611.07218](http://arxiv.org/abs/1611.07218)

##### PDF
[http://arxiv.org/pdf/1611.07218](http://arxiv.org/pdf/1611.07218)

