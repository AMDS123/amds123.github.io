---
layout: post
title: "Compositional Memory for Visual Question Answering"
date: 2015-11-18 07:25:16
categories: arXiv_CV
tags: arXiv_CV RNN Deep_Learning VQA
author: Aiwen Jiang, Fang Wang, Fatih Porikli, Yi Li
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Question Answering (VQA) emerges as one of the most fascinating topics in computer vision recently. Many state of the art methods naively use holistic visual features with language features into a Long Short-Term Memory (LSTM) module, neglecting the sophisticated interaction between them. This coarse modeling also blocks the possibilities of exploring finer-grained local features that contribute to the question answering dynamically over time. This paper addresses this fundamental problem by directly modeling the temporal dynamics between language and all possible local image patches. When traversing the question words sequentially, our end-to-end approach explicitly fuses the features associated to the words and the ones available at multiple local patches in an attention mechanism, and further combines the fused information to generate dynamic messages, which we call episode. We then feed the episodes to a standard question answering module together with the contextual visual information and linguistic information. Motivated by recent practices in deep learning, we use auxiliary loss functions during training to improve the performance. Our experiments on two latest public datasets suggest that our method has a superior performance. Notably, on the DARQUAR dataset we advanced the state of the art by 6$\%$, and we also evaluated our approach on the most recent MSCOCO-VQA dataset.

##### Abstract (translated by Google)
视觉问答（Visual Question Answering，VQA）是近年来计算机视觉领域最令人着迷的课题之一。许多先进的方法天真地使用具有语言特征的整体视觉特征到长期短期记忆（LSTM）模块中，忽略它们之间的复杂的相互作用。这种粗糙的建模也阻止了探索更细粒度的局部特征的可能性，这些特征随着时间的推移而动态回答问题。本文通过直接模拟语言和所有可能的局部图像块之间的时间动态来解决这个基本问题。当依次遍历问题单词时，我们的端到端方法明确地将与单词相关的特征和多个本地补丁中可用的特征融合在关注机制中，并进一步将融合的信息进行组合以生成动态消息， 。然后，我们将这些情节与情境视觉信息和语言信息一起提供给标准问题回答模块。受近期深度学习实践的启发，我们在培训中使用辅助损失函数来提高绩效。我们对两个最新的公开数据集进行的实验表明，我们的方法具有优越的性能。值得注意的是，在DARQUAR数据集中，我们将先进的技术水平提高了6％，而且我们也在最新的MSCOCO-VQA数据集上评估了我们的方法。

##### URL
[https://arxiv.org/abs/1511.05676](https://arxiv.org/abs/1511.05676)

##### PDF
[https://arxiv.org/pdf/1511.05676](https://arxiv.org/pdf/1511.05676)

