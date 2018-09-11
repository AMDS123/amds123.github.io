---
layout: post
title: "Learning to Solve NP-Complete Problems - A Graph Neural Network for the Decision TSP"
date: 2018-09-08 00:11:51
categories: arXiv_AI
tags: arXiv_AI Relation
author: Marcelo O. R. Prates, Pedro H. C. Avelar, Henrique Lemos, Luis Lamb, Moshe Vardi
mathjax: true
---

* content
{:toc}

##### Abstract
Graph Neural Networks (GNN) are a promising technique for bridging differential programming and combinatorial domains. GNNs employ trainable modules which can be assembled in different configurations that reflect the relational structure of each problem instance. In this paper, we show that GNNs can learn to solve, with very little supervision, the decision variant of the Traveling Salesperson Problem (TSP), a highly relevant $\mathcal{NP}$-Complete problem. Our model is trained to function as an effective message-passing algorithm in which edges (embedded with their weights) communicate with vertices for a number of iterations after which the model is asked to decide whether a route with cost $&lt;C$ exists. We show that such a network can be trained with sets of dual examples: given the optimal tour cost $C^{*}$, we produce one decision instance with target cost $x\%$ smaller and one with target cost $x\%$ larger than $C^{*}$. We were able to obtain $80\%$ accuracy training with $-2\%,+2\%$ deviations, and the same trained model can generalize for more relaxed deviations with increasing performance. We also show that the model is capable of generalizing for larger problem sizes. Finally, we provide a method for predicting the optimal route cost within $2\%$ deviation from the ground truth. In summary, our work shows that Graph Neural Networks are powerful enough to solve $\mathcal{NP}$-Complete problems which combine symbolic and numeric data.

##### Abstract (translated by Google)
图神经网络（GNN）是用于桥接差分编程和组合域的有前景的技术。 GNN采用可训练的模块，这些模块可以以不同的配置组装，以反映每个问题实例的关系结构。在本文中，我们表明GNN可以学习如何在很少的监督下解决旅行销售员问题（TSP）的决策变体，这是一个高度相关的$ \ mathcal {NP} $  - 完全问题。我们的模型被训练成用作有效的消息传递算法，其中边（嵌入其权重）与顶点通信多次迭代，之后要求模型决定是否存在成本$ <C $的路由。我们展示了这样的网络可以通过一系列双重示例进行训练：给定最佳巡回成本$ C ^ {*} $，我们生成一个目标成本为$ x \％$的决策实例和一个目标成本为$ x的决策实例％$大于$ C ^ {*} $。我们能够以$ -2 \％，+ 2 \％$偏差获得$ 80 \％$准确度训练，并且相同的训练模型可以通过提高性能来概括更轻松的偏差。我们还表明该模型能够推广更大的问题规模。最后，我们提供了一种方法，用于预测最优路线成本在$ 2 \％$偏离地面实况的范围内。总之，我们的工作表明，图形神经网络足以解决$ \ mathcal {NP} $  - 完整的问题，它们结合了符号和数字数据。

##### URL
[http://arxiv.org/abs/1809.02721](http://arxiv.org/abs/1809.02721)

##### PDF
[http://arxiv.org/pdf/1809.02721](http://arxiv.org/pdf/1809.02721)

