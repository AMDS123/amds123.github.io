---
layout: post
title: "Efficient Learning of Bounded-Treewidth Bayesian Networks from Complete and Incomplete Data Sets"
date: 2018-02-07 15:09:32
categories: arXiv_AI
tags: arXiv_AI Inference
author: Mauro Scanagatta, Giorgio Corani, Marco Zaffalon, Jaemin Yoo, U Kang
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a Bayesian networks with bounded treewidth is important for reducing the complexity of the inferences. We present a novel anytime algorithm (k-MAX) method for this task, which scales up to thousands of variables. Through extensive experiments we show that it consistently yields higher-scoring structures than its competitors on complete data sets. We then consider the problem of structure learning from incomplete data sets. This can be addressed by structural EM, which however is computationally very demanding. We thus adopt the novel k-MAX algorithm in the maximization step of structural EM, obtaining an efficient computation of the expected sufficient statistics. We test the resulting structural EM method on the task of imputing missing data, comparing it against the state-of-the-art approach based on random forests. Our approach achieves the same imputation accuracy of the competitors, but in about one tenth of the time. Furthermore we show that it has worst-case complexity linear in the input size, and that it is easily parallelizable.

##### Abstract (translated by Google)
学习具有有限树宽度的贝叶斯网络对于降低推理的复杂性非常重要。我们提出了一种新颖的任何时间算法（k-MAX）方法来完成这个任务，这个方法可以扩展到数千个变量。通过广泛的实验，我们发现它在整个数据集上始终比竞争对手得到更高的评分结构。然后我们考虑从不完整的数据集中学习结构的问题。这可以通过结构EM来解决，然而这在计算上是非常苛刻的。因此，我们在结构EM的最大化步骤中采用了新颖的k-MAX算法，从而获得了对预期足够统计量的有效计算。我们测试了由此产生的结构EM方法的输入丢失数据的任务，将其与基于随机森林的最先进的方法进行比较。我们的方法达到了与竞争对手相同的估算精度，但大约只有十分之一的时间。此外，我们还表明它具有输入大小的最坏情况复杂度线性，并且容易并行化。

##### URL
[http://arxiv.org/abs/1802.02468](http://arxiv.org/abs/1802.02468)

##### PDF
[http://arxiv.org/pdf/1802.02468](http://arxiv.org/pdf/1802.02468)

