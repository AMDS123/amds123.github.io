---
layout: post
title: "Zero-Shot Transfer Learning for Event Extraction"
date: 2017-07-04 16:48:28
categories: arXiv_CL
tags: arXiv_CL Transfer_Learning
author: Lifu Huang, Heng Ji, Kyunghyun Cho, Clare R. Voss
mathjax: true
---

* content
{:toc}

##### Abstract
Most previous event extraction studies have relied heavily on features derived from annotated event mentions, thus cannot be applied to new event types without annotation effort. In this work, we take a fresh look at event extraction and model it as a grounding problem. We design a transferable neural architecture, mapping event mentions and types jointly into a shared semantic space using structural and compositional neural networks, where the type of each event mention can be determined by the closest of all candidate types . By leveraging (1)~available manual annotations for a small set of existing event types and (2)~existing event ontologies, our framework applies to new event types without requiring additional annotation. Experiments on both existing event types (e.g., ACE, ERE) and new event types (e.g., FrameNet) demonstrate the effectiveness of our approach. \textit{Without any manual annotations} for 23 new event types, our zero-shot framework achieved performance comparable to a state-of-the-art supervised model which is trained from the annotations of 500 event mentions.

##### Abstract (translated by Google)
大多数先前的事件提取研究都严重依赖于注释事件提及的特征，因此不能应用于没有注解的新事件类型。在这项工作中，我们重新审视事件提取，并将其作为一个接地问题进行建模。我们设计了一个可移植的神经架构，将事件提及和类型映射到一个共享的语义空间，使用结构和组合神经网络，其中每个事件的类型可以由所有候选类型中最接近的类型确定。通过利用（1）〜可用手动注释为一小组现有事件类型和（2）〜现有事件本体，我们的框架适用于新的事件类型，而不需要额外的注释。现有事件类型（例如，ACE，ERE）和新事件类型（例如，FrameNet）的实验证明了我们的方法的有效性。 \ textit {没有任何手动注释} 23个新的事件类型，我们的zero-shot框架实现了性能可比的最先进的监督模型，从500个事件提到的注释训练。

##### URL
[https://arxiv.org/abs/1707.01066](https://arxiv.org/abs/1707.01066)

##### PDF
[https://arxiv.org/pdf/1707.01066](https://arxiv.org/pdf/1707.01066)

