---
layout: post
title: "Memorize or generalize? Searching for a compositional RNN in a haystack"
date: 2018-02-18 23:15:26
categories: arXiv_AI
tags: arXiv_AI RNN Gradient_Descent
author: Adam Li&#x161;ka, Germ&#xe1;n Kruszewski, Marco Baroni
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are very powerful learning systems, but they do not readily generalize from one task to the other. This is partly due to the fact that they do not learn in a compositional way, that is, by discovering skills that are shared by different tasks, and recombining them to solve new problems. In this paper, we explore the compositional generalization capabilities of recurrent neural networks (RNNs). We first propose the lookup table composition domain as a simple setup to test compositional behaviour and show that it is theoretically possible for a standard RNN to learn to behave compositionally in this domain when trained with standard gradient descent and provided with additional supervision. We then remove this additional supervision and perform a search over a large number of model initializations to investigate the proportion of RNNs that can still converge to a compositional solution. We discover that a small but non-negligible proportion of RNNs do reach partial compositional solutions even without special architectural constraints. This suggests that a combination of gradient descent and evolutionary strategies directly favouring the minority models that developed more compositional approaches might suffice to lead standard RNNs towards compositional solutions.

##### Abstract (translated by Google)
神经网络是非常强大的学习系统，但它们不容易从一个任务推演到另一个任务。这部分是由于他们没有从构图的角度学习，也就是通过发现不同任务共享的技能，并重新组合来解决新问题。在本文中，我们探讨了递归神经网络（RNN）的组成泛化能力。我们首先提出查找表格组成领域作为一个简单的设置来测试组成的行为，并表明在标准梯度下降训练和提供额外的监督下，标准RNN在理论上可以学习在这个领域的组成行为。然后，我们删除这些额外的监督，并对大量模型初始化进行搜索，以调查RNNs的比例，这些比例仍然可以收敛到组合解决方案。我们发现即使没有特殊的架构限制，RNN的一小部分但不可忽略的比例确实达到了部分组合解决方案。这表明梯度下降和演化策略的结合直接有利于开发更多组成方法的少数模型，可能足以将标准RNN引向组合解决方案。

##### URL
[http://arxiv.org/abs/1802.06467](http://arxiv.org/abs/1802.06467)

##### PDF
[http://arxiv.org/pdf/1802.06467](http://arxiv.org/pdf/1802.06467)

