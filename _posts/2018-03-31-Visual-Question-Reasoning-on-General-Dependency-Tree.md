---
layout: post
title: "Visual Question Reasoning on General Dependency Tree"
date: 2018-03-31 01:48:27
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Knowledge QA Attention Relation VQA
author: Qingxing Cao, Xiaodan Liang, Bailing Li, Guanbin Li, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
The collaborative reasoning for understanding each image-question pair is very critical but under-explored for an interpretable Visual Question Answering (VQA) system. Although very recent works also tried the explicit compositional processes to assemble multiple sub-tasks embedded in the questions, their models heavily rely on the annotations or hand-crafted rules to obtain valid reasoning layout, leading to either heavy labor or poor performance on composition reasoning. In this paper, to enable global context reasoning for better aligning image and language domains in diverse and unrestricted cases, we propose a novel reasoning network called Adversarial Composition Modular Network (ACMN). This network comprises of two collaborative modules: i) an adversarial attention module to exploit the local visual evidence for each word parsed from the question; ii) a residual composition module to compose the previously mined evidence. Given a dependency parse tree for each question, the adversarial attention module progressively discovers salient regions of one word by densely combining regions of child word nodes in an adversarial manner. Then residual composition module merges the hidden representations of an arbitrary number of children through sum pooling and residual connection. Our ACMN is thus capable of building an interpretable VQA system that gradually dives the image cues following a question-driven reasoning route and makes global reasoning by incorporating the learned knowledge of all attention modules in a principled manner. Experiments on relational datasets demonstrate the superiority of our ACMN and visualization results show the explainable capability of our reasoning system.

##### Abstract (translated by Google)
理解每个图像 - 问题对的协作推理非常关键，但对于可解释的视觉问题回答（VQA）系统而言探索不足。虽然最近的作品也尝试使用明确的组合过程来组合嵌入问题中的多个子任务，但是他们的模型在很大程度上依赖于注释或手工制作的规则来获得有效的推理布局，从而导致人工繁重或组合推理表现不佳。在本文中，为了在不同和不受限制的情况下实现全局上下文推理以更好地协调图像和语言域，我们提出了一种称为Adversarial Composition Modular Network（ACMN）的新型推理网络。该网络包括两个协作模块：i）对抗性注意模块，用于利用从问题解析的每个单词的本地视觉证据; ii）残余组合物模块以组成先前开采的证据。给定每个问题的依赖性解析树，对抗性关注模块通过以对抗方式密集地组合子字节点的区域来逐步发现一个单词的显着区域。然后，残差合成模块通过总和池和剩余连接合并任意数量的子节点的隐藏表示。因此，我们的ACMN能够构建可解释的VQA系统，该系统在问题驱动的推理路线之后逐渐潜入图像线索，并通过以原则方式结合所有注意力模块的学习知识来进行全局推理。关系数据集的实验证明了我们的ACMN的优越性，可视化结果显示了我们推理系统的可解释能力。

##### URL
[https://arxiv.org/abs/1804.00105](https://arxiv.org/abs/1804.00105)

##### PDF
[https://arxiv.org/pdf/1804.00105](https://arxiv.org/pdf/1804.00105)

