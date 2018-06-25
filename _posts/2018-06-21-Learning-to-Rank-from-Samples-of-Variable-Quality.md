---
layout: post
title: "Learning to Rank from Samples of Variable Quality"
date: 2018-06-21 09:40:20
categories: arXiv_AI
tags: arXiv_AI
author: Mostafa Dehghani, Jaap Kamps
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep neural networks requires many training samples, but in practice, training labels are expensive to obtain and may be of varying quality, as some may be from trusted expert labelers while others might be from heuristics or other sources of weak supervision such as crowd-sourcing. This creates a fundamental quality-versus quantity trade-off in the learning process. Do we learn from the small amount of high-quality data or the potentially large amount of weakly-labeled data? We argue that if the learner could somehow know and take the label-quality into account when learning the data representation, we could get the best of both worlds. To this end, we introduce "fidelity-weighted learning" (FWL), a semi-supervised student-teacher approach for training deep neural networks using weakly-labeled data. FWL modulates the parameter updates to a student network (trained on the task we care about) on a per-sample basis according to the posterior confidence of its label-quality estimated by a teacher (who has access to the high-quality labels). Both student and teacher are learned from the data. We evaluate FWL on document ranking where we outperform state-of-the-art alternative semi-supervised methods.

##### Abstract (translated by Google)
训练深度神经网络需要许多训练样本，但实际上，训练标签的获取成本很高，并且质量可能有所不同，有些可能来自可信的专家贴标签者，而另一些可能来自启发式或其他弱监管来源，采购。这在学习过程中创建了基本的质量与数量的权衡。我们是否从少量的高质量数据或潜在的大量弱标记数据中学习？我们认为，如果学习者在学习数据表示时能够以某种方式了解并考虑标签质量，那么我们就可以获得两全其美的好处。为此，我们引入“保真加权学习”（FWL），这是一种半监督学生 - 老师方法，用于使用弱标记数据训练深度神经网络。 FWL根据其标签质量的后置置信度（可以访问高质量标签）对每个样本基础上的参数更新进行调整（针对我们关心的任务进行训练）。学生和老师从数据中学习。我们评估FWL在文档排名方面的优势，我们超越了最先进的替代半监督方法。

##### URL
[http://arxiv.org/abs/1806.08694](http://arxiv.org/abs/1806.08694)

##### PDF
[http://arxiv.org/pdf/1806.08694](http://arxiv.org/pdf/1806.08694)

