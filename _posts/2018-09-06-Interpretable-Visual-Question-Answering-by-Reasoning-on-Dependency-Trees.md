---
layout: post
title: "Interpretable Visual Question Answering by Reasoning on Dependency Trees"
date: 2018-09-06 04:09:28
categories: arXiv_CV
tags: arXiv_CV QA Attention Relation VQA
author: Qingxing Cao, Xiaodan Liang, Bailin Li, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Collaborative reasoning for understanding each image-question pair is very critical but underexplored for an interpretable visual question answering system. Although very recent works also attempted to use explicit compositional processes to assemble multiple subtasks embedded in the questions, their models heavily rely on annotations or handcrafted rules to obtain valid reasoning processes, leading to either heavy workloads or poor performance on composition reasoning. In this paper, to better align image and language domains in diverse and unrestricted cases, we propose a novel neural network model that performs global reasoning on a dependency tree parsed from the question, and we thus phrase our model as parse-tree-guided reasoning network (PTGRN). This network consists of three collaborative modules: i) an attention module to exploit the local visual evidence for each word parsed from the question, ii) a gated residual composition module to compose the previously mined evidence, and iii) a parse-tree-guided propagation module to pass the mined evidence along the parse tree. Our PTGRN is thus capable of building an interpretable VQA system that gradually derives the image cues following a question-driven parse-tree reasoning route. Experiments on relational datasets demonstrate the superiority of our PTGRN over current state-of-the-art VQA methods, and the visualization results highlight the explainable capability of our reasoning system.

##### Abstract (translated by Google)
用于理解每个图像 - 问题对的协作推理是非常关键的，但是对于可解释的视觉问答系统来说是未充分探索的。虽然最近的工作也尝试使用显式组合过程来组合嵌入在问题中的多个子任务，但是他们的模型在很大程度上依赖于注释或手工制作的规则来获得有效的推理过程，从而导致繁重的工作负载或组合推理的不良性能。在本文中，为了更好地在不同和不受限制的情况下对齐图像和语言域，我们提出了一种新的神经网络模型，该模型在从问题解析的依赖关系树上执行全局推理，因此我们将我们的模型表示为解析树引导的推理网络（PTGRN）。该网络由三个协作模块组成：i）用于利用从问题解析的每个单词的本地视觉证据的注意模块，ii）用于组成先前挖掘的证据的门控残差组合模块，以及iii）解析树引导的传播模块沿着解析树传递挖掘的证据。因此，我们的PTGRN能够构建可解释的VQA系统，该系统在问题驱动的分析树推理路线之后逐渐导出图像提示。关系数据集的实验证明了我们的PTGRN优于当前最先进的VQA方法的优越性，可视化结果突出了我们的推理系统的可解释能力。

##### URL
[http://arxiv.org/abs/1809.01810](http://arxiv.org/abs/1809.01810)

##### PDF
[http://arxiv.org/pdf/1809.01810](http://arxiv.org/pdf/1809.01810)

