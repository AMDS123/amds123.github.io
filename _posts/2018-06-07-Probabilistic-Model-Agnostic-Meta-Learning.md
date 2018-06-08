---
layout: post
title: "Probabilistic Model-Agnostic Meta-Learning"
date: 2018-06-07 17:53:20
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: Chelsea Finn, Kelvin Xu, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Meta-learning for few-shot learning entails acquiring a prior over previous tasks and experiences, such that new tasks be learned from small amounts of data. However, a critical challenge in few-shot learning is task ambiguity: even when a powerful prior can be meta-learned from a large number of prior tasks, a small dataset for a new task can simply be too ambiguous to acquire a single model (e.g., a classifier) for that task that is accurate. In this paper, we propose a probabilistic meta-learning algorithm that can sample models for a new task from a model distribution. Our approach extends model-agnostic meta-learning, which adapts to new tasks via gradient descent, to incorporate a parameter distribution that is trained via a variational lower bound. At meta-test time, our algorithm adapts via a simple procedure that injects noise into gradient descent, and at meta-training time, the model is trained such that this stochastic adaptation procedure produces samples from the approximate model posterior. Our experimental results show that our method can sample plausible classifiers and regressors in ambiguous few-shot learning problems.

##### Abstract (translated by Google)
对于少量学习的元学习需要先获得先前的任务和经验，以便从少量数据中学习新任务。然而，少量学习中的一个关键挑战是任务模糊性：即使一个强大的先验可以从大量的先前任务中学习到元数据，新任务的小数据集可能会太模糊以至于无法获取单个模型例如分类器），这是准确的。在本文中，我们提出了一种概率元学习算法，可以从模型分布中为新任务抽样模型。我们的方法扩展了模型不可知的元学习，它通过梯度下降来适应新的任务，并纳入通过变分下界训练的参数分布。在元测试时间，我们的算法通过一个简单的程序进行调整，该过程将噪声注入梯度下降，并且在元训练时间，对该模型进行训练，使得该随机适应程序从近似模型后验产生样本。我们的实验结果表明，我们的方法可以用模糊的少数学习问题对合理的分类器和回归器进行抽样。

##### URL
[http://arxiv.org/abs/1806.02817](http://arxiv.org/abs/1806.02817)

##### PDF
[http://arxiv.org/pdf/1806.02817](http://arxiv.org/pdf/1806.02817)

