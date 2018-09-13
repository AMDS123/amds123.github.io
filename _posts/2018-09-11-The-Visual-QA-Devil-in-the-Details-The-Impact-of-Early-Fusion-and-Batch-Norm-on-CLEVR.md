---
layout: post
title: "The Visual QA Devil in the Details: The Impact of Early Fusion and Batch Norm on CLEVR"
date: 2018-09-11 07:14:30
categories: arXiv_CV
tags: arXiv_CV QA Relation
author: Mateusz Malinowski, Carl Doersch
mathjax: true
---

* content
{:toc}

##### Abstract
Visual QA is a pivotal challenge for higher-level reasoning, requiring understanding language, vision, and relationships between many objects in a scene. Although datasets like CLEVR are designed to be unsolvable without such complex relational reasoning, some surprisingly simple feed-forward, "holistic" models have recently shown strong performance on this dataset. These models lack any kind of explicit iterative, symbolic reasoning procedure, which are hypothesized to be necessary for counting objects, narrowing down the set of relevant objects based on several attributes, etc. The reason for this strong performance is poorly understood. Hence, our work analyzes such models, and finds that minor architectural elements are crucial to performance. In particular, we find that \textit{early fusion} of language and vision provides large performance improvements. This contrasts with the late fusion approaches popular at the dawn of Visual QA. We propose a simple module we call Multimodal Core, which we hypothesize performs the fundamental operations for multimodal tasks. We believe that understanding why these elements are so important to complex question answering will aid the design of better-performing algorithms for Visual QA while minimizing hand-engineering effort.

##### Abstract (translated by Google)
Visual QA是高级推理的关键挑战，需要理解场景中许多对象之间的语言，视觉和关系。尽管像CLEVR这样的数据集在没有这种复杂的关系推理的情况下被设计为无法解决，但是一些令人惊讶的简单前馈，“整体”模型最近在该数据集上表现出了强大的性能。这些模型缺少任何类型的显式迭代符号推理过程，这些过程被假设为计算对象所必需的，基于若干属性缩小相关对象的集合等。这种强大性能的原因很难理解。因此，我们的工作分析了这些模型，并发现次要的建筑元素对性能至关重要。特别是，我们发现语言和视觉的\ textit {早期融合}提供了很大的性能改进。这与在Visual QA曙光中流行的后期融合方法形成对比。我们提出了一个简单的模块，我们称之为Multimodal Core，我们假设它执行多模式任务的基本操作。我们相信理解为什么这些元素对于复杂的问答非常重要，这将有助于设计性能更好的Visual QA算法，同时最大限度地减少手工工作。

##### URL
[http://arxiv.org/abs/1809.04482](http://arxiv.org/abs/1809.04482)

##### PDF
[http://arxiv.org/pdf/1809.04482](http://arxiv.org/pdf/1809.04482)

