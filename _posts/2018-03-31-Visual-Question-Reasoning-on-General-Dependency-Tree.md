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
理解每个图像 - 问题对的合作推理非常关键，但是对于可解释的视觉问题回答（VQA）系统来说，这个问题还处于探索之中。尽管最近的作品也尝试了明确的构图过程来组装多个嵌入在问题中的子任务，但他们的模型严重依赖注释或手工制定的规则来获得有效的推理布局，从而导致组合推理中的重劳或性能不佳。在本文中，为了使全局上下文推理更好地在不同和不受限制的情况下对齐图像和语言域，我们提出了一种称为Adversarial Composition Modular Network（ACMN）的新型推理网络。该网络包含两个协作模块：i）对抗注意模块，用于利用从问题解析的每个词的当地视觉证据; ii）组成先前挖掘的证据的剩余组成模块。给定每个问题的依赖关系解析树，敌对关注模块通过以对抗方式密集地组合儿童词节点的区域来逐步发现一个词的显着区域。然后，剩余组合模块通过汇总和剩余连接合并任意数量的儿童的隐藏表示。因此，我们的ACMN能够建立一个可解释的VQA系统，通过以问题为导向的推理路线逐渐潜入影像线索，并通过以原则方式整合所有关注模块的学习知识来进行全局推理。关系数据集上的实验证明了我们ACMN的优越性和可视化结果显示了我们推理系统的可解释能力。

##### URL
[http://arxiv.org/abs/1804.00105](http://arxiv.org/abs/1804.00105)

##### PDF
[http://arxiv.org/pdf/1804.00105](http://arxiv.org/pdf/1804.00105)

