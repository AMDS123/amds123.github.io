---
layout: post
title: "Selfless Sequential Learning"
date: 2018-06-14 09:06:10
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Rahaf Aljundi, Marcus Rohrbach, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
Sequential learning studies the problem of learning tasks in a sequence with restricted access to only the data of the current task. In the setting with a fixed model capacity, the learning process should not be selfish and account for later tasks to be added and therefore aim at utilizing a minimum number of neurons, leaving enough capacity for future needs. We explore different regularization strategies and activation functions that could lead to less interference between the different tasks. We show that learning a sparse representation is more beneficial for sequential learning than encouraging parameter sparsity regardless of their corresponding neurons. We particularly propose a novel regularizer that encourages representation sparsity by means of neural inhibition. It results in few active neurons which in turn leaves more free neurons to be utilized by upcoming tasks. We combine our regularizer with state-of-the-art lifelong learning methods that penalize changes on important previously learned parts of the network. We show that increased sparsity translates in a performance improvement on the different tasks that are learned in a sequence.

##### Abstract (translated by Google)
顺序学习研究一系列学习任务的问题，只能访问当前任务的数据。在具有固定模型能力的环境中，学习过程不应该是自私的，并且需要添加以后的任务，因此旨在利用最少数量的神经元，为未来的需求留下足够的容量。我们探索不同的正则化策略和激活函数，可以减少不同任务之间的干扰。我们表明，学习稀疏表示对序贯学习更有利，而不是鼓励参数稀疏性，而不管它们对应的神经元如何。我们特别提出了一种新颖的正则化算法，鼓励通过神经抑制来表示稀疏性。它导致几个活跃的神经元，从而留下更多的自由神经元被即将到来的任务利用。我们结合我们的正规化者和先进的终身学习方法，惩罚重要的以前学过的网络部分的变化。我们表明，增加的稀疏性可以转化为在序列中学习的不同任务的性能改进。

##### URL
[http://arxiv.org/abs/1806.05421](http://arxiv.org/abs/1806.05421)

##### PDF
[http://arxiv.org/pdf/1806.05421](http://arxiv.org/pdf/1806.05421)

