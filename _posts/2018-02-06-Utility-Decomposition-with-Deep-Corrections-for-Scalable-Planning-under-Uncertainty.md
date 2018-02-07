---
layout: post
title: "Utility Decomposition with Deep Corrections for Scalable Planning under Uncertainty"
date: 2018-02-06 03:02:22
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Maxime Bouton, Kyle Julian, Alireza Nakhaei, Kikuo Fujimura, Mykel J. Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
Decomposition methods have been proposed in the past to approximate solutions to large sequential decision making problems. In contexts where an agent interacts with multiple entities, utility decomposition can be used where each individual entity is considered independently. The individual utility functions are then combined in real time to solve the global problem. Although these techniques can perform well empirically, they sacrifice optimality. This paper proposes an approach inspired from multi-fidelity optimization to learn a correction term with a neural network representation. Learning this correction can significantly improve performance. We demonstrate this approach on a pedestrian avoidance problem for autonomous driving. By leveraging strategies to avoid a single pedestrian, the decomposition method can scale to avoid multiple pedestrians. We verify empirically that the proposed correction method leads to a significant improvement over the decomposition method alone and outperforms a policy trained on the full scale problem without utility decomposition.

##### Abstract (translated by Google)
过去已经提出了分解方法来逼近大的顺序决策问题的解决方案。在代理与多个实体交互的情况下，可以在每个实体被独立考虑的情况下使用效用分解。然后将各个效用函数实时结合起来解决全球问题。虽然这些技术可以很好地经验性地执行，但它们牺牲了最优性。本文提出了一种启发于多保真优化的方法来学习具有神经网络表示的校正项。学习这一修正可以显着提高性能。我们证明这种方法对自动驾驶的行人避让问题。通过利用策略避开单个行人，分解方法可以扩展以避免多个行人。我们经验地验证，所提出的校正方法比单独的分解方法导致显着的改进，并且胜过在没有效用分解的情况下训练全面问题的策略。

##### URL
[http://arxiv.org/abs/1802.01772](http://arxiv.org/abs/1802.01772)

##### PDF
[http://arxiv.org/pdf/1802.01772](http://arxiv.org/pdf/1802.01772)

