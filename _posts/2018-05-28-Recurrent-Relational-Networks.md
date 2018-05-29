---
layout: post
title: "Recurrent Relational Networks"
date: 2018-05-28 11:44:06
categories: arXiv_AI
tags: arXiv_AI Inference Relation
author: Rasmus Berg Palm, Ulrich Paquet, Ole Winther
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is concerned with learning to solve tasks that require a chain of interdependent steps of relational inference, like answering complex questions about the relationships between objects, or solving puzzles where the smaller elements of a solution mutually constrain each other. We introduce the recurrent relational network, a general purpose module that operates on a graph representation of objects. As a generalization of Santoro et al. [2017]'s relational network, it can augment any neural network model with the capacity to do many-step relational reasoning. We achieve state of the art results on the bAbI textual question-answering dataset with the recurrent relational network, consistently solving 20/20 tasks. As bAbI is not particularly challenging from a relational reasoning point of view, we introduce Pretty-CLEVR, a new diagnostic dataset for relational reasoning. In the Pretty-CLEVR set-up, we can vary the question to control for the number of relational reasoning steps that are required to obtain the answer. Using Pretty-CLEVR, we probe the limitations of multi-layer perceptrons, relational and recurrent relational networks. Finally, we show how recurrent relational networks can learn to solve Sudoku puzzles from supervised training data, a challenging task requiring upwards of 64 steps of relational reasoning. We achieve state-of-the-art results amongst comparable methods by solving 96.6% of the hardest Sudoku puzzles.

##### Abstract (translated by Google)
本文关注于学习解决需要一系列相互关联的关系推理步骤的任务，例如回答有关对象之间关系的复杂问题，或者解决解决方案中较小元素相互约束的难题。我们介绍经常性关系网络，这是一个通用模块，用于对象的图形表示。作为Santoro等人的一般化。 [2017]的关系网络，它可以增强任何具有进行多步关系推理能力的神经网络模型。我们使用经常性关系网络在bAbI文本问答数据集上实现了最先进的结果，始终如一地解决20/20任务。由于从关系推理的角度来看，bAbI并不是特别具有挑战性，所以我们引入了Pretty-CLEVR，一种用于关系推理的新诊断数据集。在Pretty-CLEVR设置中，我们可以改变问题来控制获得答案所需的关系推理步骤的数量。使用Pretty-CLEVR，我们探讨了多层感知器，关系和复发关系网络的局限性。最后，我们展示了循环关系网络如何通过监督训练数据来学习解决数独谜题，这是一项具有挑战性的任务，需要64步以上的关系推理。我们通过解决96.6％最难的数独谜题，在可比较的方法中取得了最先进的成果。

##### URL
[http://arxiv.org/abs/1711.08028](http://arxiv.org/abs/1711.08028)

##### PDF
[http://arxiv.org/pdf/1711.08028](http://arxiv.org/pdf/1711.08028)

