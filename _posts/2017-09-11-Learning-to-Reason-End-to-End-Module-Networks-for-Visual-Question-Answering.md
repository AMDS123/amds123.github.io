---
layout: post
title: "Learning to Reason: End-to-End Module Networks for Visual Question Answering"
date: 2017-09-11 22:22:59
categories: arXiv_CV
tags: arXiv_CV Attention VQA
author: Ronghang Hu, Jacob Andreas, Marcus Rohrbach, Trevor Darrell, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language questions are inherently compositional, and many are most easily answered by reasoning about their decomposition into modular sub-problems. For example, to answer "is there an equal number of balls and boxes?" we can look for balls, look for boxes, count them, and compare the results. The recently proposed Neural Module Network (NMN) architecture implements this approach to question answering by parsing questions into linguistic substructures and assembling question-specific deep networks from smaller modules that each solve one subtask. However, existing NMN implementations rely on brittle off-the-shelf parsers, and are restricted to the module configurations proposed by these parsers rather than learning them from data. In this paper, we propose End-to-End Module Networks (N2NMNs), which learn to reason by directly predicting instance-specific network layouts without the aid of a parser. Our model learns to generate network structures (by imitating expert demonstrations) while simultaneously learning network parameters (using the downstream task loss). Experimental results on the new CLEVR dataset targeted at compositional question answering show that N2NMNs achieve an error reduction of nearly 50% relative to state-of-the-art attentional approaches, while discovering interpretable network architectures specialized for each question.

##### Abstract (translated by Google)
自然语言问题本质上是构成性的，许多问题最容易通过推理将其分解为模块化子问题来回答。例如，回答“是否有相同数量的球和盒子？”我们可以寻找球，寻找盒子，数它们，并比较结果。最近提出的神经模块网络（NMN）架构实现了这种方法来回答问题，将问题解析成语言子结构，并从较小的模块组装问题特定的深层网络，每个解决一个子任务。然而，现有的NMN实现依赖于脆弱的现成解析器，并且仅限于由这些解析器提出的模块配置，而不是从数据中学习。在本文中，我们提出端到端模块网络（N2NMN），通过直接预测特定于实例的网络布局而不借助解析器来学习推理。我们的模型学习生成网络结构（通过模拟专家演示），同时学习网络参数（使用下游任务丢失）。针对成分问题回答的新的CLEVR数据集的实验结果表明，相对于最先进的注意方法，N2NMN实现了近50％的错误减少，同时发现专用于每个问题的可解释的网络架构。

##### URL
[https://arxiv.org/abs/1704.05526](https://arxiv.org/abs/1704.05526)

##### PDF
[https://arxiv.org/pdf/1704.05526](https://arxiv.org/pdf/1704.05526)

