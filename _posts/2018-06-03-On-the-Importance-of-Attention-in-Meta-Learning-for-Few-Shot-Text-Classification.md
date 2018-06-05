---
layout: post
title: "On the Importance of Attention in Meta-Learning for Few-Shot Text Classification"
date: 2018-06-03 19:16:50
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention Text_Classification Represenation_Learning Classification Deep_Learning
author: Xiang Jiang, Mohammad Havaei, Gabriel Chartrand, Hassan Chouaib, Thomas Vincent, Andrew Jesson, Nicolas Chapados, Stan Matwin
mathjax: true
---

* content
{:toc}

##### Abstract
Current deep learning based text classification methods are limited by their ability to achieve fast learning and generalization when the data is scarce. We address this problem by integrating a meta-learning procedure that uses the knowledge learned across many tasks as an inductive bias towards better natural language understanding. Based on the Model-Agnostic Meta-Learning framework (MAML), we introduce the Attentive Task-Agnostic Meta-Learning (ATAML) algorithm for text classification. The essential difference between MAML and ATAML is in the separation of task-agnostic representation learning and task-specific attentive adaptation. The proposed ATAML is designed to encourage task-agnostic representation learning by way of task-agnostic parameterization and facilitate task-specific adaptation via attention mechanisms. We provide evidence to show that the attention mechanism in ATAML has a synergistic effect on learning performance. In comparisons with models trained from random initialization, pretrained models and meta trained MAML, our proposed ATAML method generalizes better on single-label and multi-label classification tasks in miniRCV1 and miniReuters-21578 datasets.

##### Abstract (translated by Google)
当前基于深度学习的文本分类方法受限于数据稀缺时实现快速学习和泛化的能力。我们通过整合一个元学习过程来解决这个问题，该过程使用跨许多任务学到的知识作为更好的自然语言理解的归纳偏见。基于模型不可知的元学习框架（MAML），我们引入了用于文本分类的注意任务 - 不可知论元学习（ATAML）算法。 MAML和ATAML之间的本质区别在于将任务无关型表示学习与特定于任务的注意力适应分开。所提出的ATAML旨在通过与任务无关的参数化方式鼓励与任务无关的表示学习，并通过注意机制促进特定于任务的适应。我们提供的证据表明，ATAML中的注意机制对学习成绩有协同作用。与从随机初始化，预训练模型和元训练MAML训练的模型进行比较，我们提出的ATAML方法更好地推广miniRCV1和miniReuters-21578数据集中的单标签和多标签分类任务。

##### URL
[http://arxiv.org/abs/1806.00852](http://arxiv.org/abs/1806.00852)

##### PDF
[http://arxiv.org/pdf/1806.00852](http://arxiv.org/pdf/1806.00852)

