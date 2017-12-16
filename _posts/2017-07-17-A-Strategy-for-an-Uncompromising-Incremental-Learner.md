---
layout: post
title: "A Strategy for an Uncompromising Incremental Learner"
date: 2017-07-17 07:30:18
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Ragav Venkatesan, Hemanth Venkateswara, Sethuraman Panchanathan, Baoxin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-class supervised learning systems require the knowledge of the entire range of labels they predict. Often when learnt incrementally, they suffer from catastrophic forgetting. To avoid this, generous leeways have to be made to the philosophy of incremental learning that either forces a part of the machine to not learn, or to retrain the machine again with a selection of the historic data. While these hacks work to various degrees, they do not adhere to the spirit of incremental learning. In this article, we redefine incremental learning with stringent conditions that do not allow for any undesirable relaxations and assumptions. We design a strategy involving generative models and the distillation of dark knowledge as a means of hallucinating data along with appropriate targets from past distributions. We call this technique, phantom sampling.We show that phantom sampling helps avoid catastrophic forgetting during incremental learning. Using an implementation based on deep neural networks, we demonstrate that phantom sampling dramatically avoids catastrophic forgetting. We apply these strategies to competitive multi-class incremental learning of deep neural networks. Using various benchmark datasets and through our strategy, we demonstrate that strict incremental learning could be achieved. We further put our strategy to test on challenging cases, including cross-domain increments and incrementing on a novel label space. We also propose a trivial extension to unbounded-continual learning and identify potential for future development.

##### Abstract (translated by Google)
多级监督学习系统需要知道他们预测的整个标签范围。通常在渐进地学习时，他们会遭受灾难性的遗忘。为了避免这种情况，必须对渐进式学习的理念给予充分的理解，这种学习要么迫使机器的一部分不学习，要么通过选择历史数据再次重新训练机器。虽然这些黑客工作不同程度，他们不坚持渐进式学习的精神。在这篇文章中，我们重新定义了增量学习的严格条件，不允许有任何不良的松弛和假设。我们设计了一个涉及生成模型的策略，并将黑暗知识的蒸馏作为一种幻觉数据以及过去分布的适当目标。我们称这种技术为幻像取样。我们表明，幻像取样有助于避免增量学习过程中的灾难性遗忘。使用基于深度神经网络的实现，我们证明了幻像采样显着避免了灾难性的遗忘。我们将这些策略应用于深度神经网络的竞争性多类增量学习。使用各种基准数据集并通过我们的策略，我们证明可以实现严格的增量学习。我们进一步将我们的策略用于测试具有挑战性的案例，包括跨域增量和在新标签空间上递增。我们也提出对无边界连续学习的微小延伸，并确定未来发展的潜力。

##### URL
[https://arxiv.org/abs/1705.00744](https://arxiv.org/abs/1705.00744)

##### PDF
[https://arxiv.org/pdf/1705.00744](https://arxiv.org/pdf/1705.00744)

