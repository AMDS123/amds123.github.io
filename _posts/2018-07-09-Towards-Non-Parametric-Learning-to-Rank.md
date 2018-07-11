---
layout: post
title: "Towards Non-Parametric Learning to Rank"
date: 2018-07-09 21:27:14
categories: arXiv_AI
tags: arXiv_AI
author: Ao Liu, Qiong Wu, Zhenming Liu, Lirong Xia
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies a stylized, yet natural, learning-to-rank problem and points out the critical incorrectness of a widely used nearest neighbor algorithm. We consider a model with $n$ agents (users) $\{x_i\}_{i \in [n]}$ and $m$ alternatives (items) $\{y_j\}_{j \in [m]}$, each of which is associated with a latent feature vector. Agents rank items nondeterministically according to the Plackett-Luce model, where the higher the utility of an item to the agent, the more likely this item will be ranked high by the agent. Our goal is to find neighbors of an arbitrary agent or alternative in the latent space. 
 We first show that the Kendall-tau distance based kNN produces incorrect results in our model. Next, we fix the problem by introducing a new algorithm with features constructed from "global information" of the data matrix. Our approach is in sharp contrast to most existing feature engineering methods. Finally, we design another new algorithm identifying similar alternatives. The construction of alternative features can be done using "local information," highlighting the algorithmic difference between finding similar agents and similar alternatives.

##### Abstract (translated by Google)
本文研究了一种程式化但自然的学习排名问题，并指出了广泛使用的最近邻算法的关键不正确性。我们考虑使用$ n $代理（用户）的模型$ \ {x_i \} _ {i \ in [n]} $和$ m $ alternatives（items）$ \ {y_j \} _ {j \ in [m] } $，每个都与潜在的特征向量相关联。代理商根据Plackett-Luce模型对项目进行不确定性排名，其中项目对代理商的效用越高，该项目被代理商排名越高的可能性越大。我们的目标是在潜在空间中寻找任意代理人或替代者的邻居。
 我们首先表明基于Kendall-tau距离的kNN在我们的模型中产生不正确的结果。接下来，我们通过引入一种新算法来解决问题，该算法具有根据数据矩阵的“全局信息”构造的特征。我们的方法与大多数现有的特征工程方法形成鲜明对比。最后，我们设计了另一种识别类似替代品的新算法可以使用“本地信息”来完成替代特征的构建，突出显示寻找类似代理和类似替代方案之间的算法差异。

##### URL
[http://arxiv.org/abs/1807.03395](http://arxiv.org/abs/1807.03395)

##### PDF
[http://arxiv.org/pdf/1807.03395](http://arxiv.org/pdf/1807.03395)

