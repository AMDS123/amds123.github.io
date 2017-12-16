---
layout: post
title: "An End-to-End Approach to Natural Language Object Retrieval via Context-Aware Deep Reinforcement Learning"
date: 2017-03-22 09:25:49
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Fan Wu, Zhongwen Xu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end approach to the natural language object retrieval task, which localizes an object within an image according to a natural language description, i.e., referring expression. Previous works divide this problem into two independent stages: first, compute region proposals from the image without the exploration of the language description; second, score the object proposals with regard to the referring expression and choose the top-ranked proposals. The object proposals are generated independently from the referring expression, which makes the proposal generation redundant and even irrelevant to the referred object. In this work, we train an agent with deep reinforcement learning, which learns to move and reshape a bounding box to localize the object according to the referring expression. We incorporate both the spatial and temporal context information into the training procedure. By simultaneously exploiting local visual information, the spatial and temporal context and the referring language a priori, the agent selects an appropriate action to take at each time. A special action is defined to indicate when the agent finds the referred object, and terminate the procedure. We evaluate our model on various datasets, and our algorithm significantly outperforms the compared algorithms. Notably, the accuracy improvement of our method over the recent method GroundeR and SCRC on the ReferItGame dataset are 7.67% and 18.25%, respectively.

##### Abstract (translated by Google)
我们提出了一种自然语言对象检索任务的端到端方法，它根据自然语言描述（即表达式）来定位图像内的对象。以前的研究将这个问题分为两个独立的阶段：首先，从图像中计算区域提案，而不涉及语言描述;第二，对引用表达的对象建议进行评分，并选择排名最高的建议。对象提议是独立于引用表达式生成的，这使得提案生成是冗余的，甚至与被引用的对象无关。在这项工作中，我们训练一个具有深度强化学习的代理，学习移动和重塑一个包围盒来根据引用表达式来定位对象。我们将空间和时间上下文信息结合到训练过程中。通过同时利用本地视觉信息，空间和时间上下文和推理语言，代理人每次选择适当的行动。定义一个特殊的动作来表示代理何时找到被引用的对象，并终止该过程。我们评估我们的模型在各种数据集，我们的算法显着优于比较算法。值得注意的是，我们的方法在ReferItGame数据集上最近的方法GroundeR和SCRC的准确性提高分别是7.67％和18.25％。

##### URL
[https://arxiv.org/abs/1703.07579](https://arxiv.org/abs/1703.07579)

##### PDF
[https://arxiv.org/pdf/1703.07579](https://arxiv.org/pdf/1703.07579)

