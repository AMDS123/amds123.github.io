---
layout: post
title: "Automated Directed Fairness Testing"
date: 2018-07-02 05:29:57
categories: arXiv_AI
tags: arXiv_AI
author: Sakshi Udeshi, Pryanshu Arora, Sudipta Chattopadhyay
mathjax: true
---

* content
{:toc}

##### Abstract
Fairness is a critical trait in decision making. As machine-learning models are increasingly being used in sensitive application domains (e.g. education and employment) for decision making, it is crucial that the decisions computed by such models are free of unintended bias. But how can we automatically validate the fairness of arbitrary machine-learning models? For a given machine-learning model and a set of sensitive input parameters, our AEQUITAS approach automatically discovers discriminatory inputs that highlight fairness violation. At the core of AEQUITAS are three novel strategies to employ probabilistic search over the input space with the objective of uncovering fairness violation. Our AEQUITAS approach leverages inherent robustness property in common machine-learning models to design and implement scalable test generation methodologies. An appealing feature of our generated test inputs is that they can be systematically added to the training set of the underlying model and improve its fairness. To this end, we design a fully automated module that guarantees to improve the fairness of the underlying model. 
 We implemented AEQUITAS and we have evaluated it on six state-of-the-art classifiers, including a classifier that was designed with fairness constraints. We show that AEQUITAS effectively generates inputs to uncover fairness violation in all the subject classifiers and systematically improves the fairness of the respective models using the generated test inputs. In our evaluation, AEQUITAS generates up to 70% discriminatory inputs (w.r.t. the total number of inputs generated) and leverages these inputs to improve the fairness up to 94%.

##### Abstract (translated by Google)
公平是决策的关键特征。随着机器学习模型越来越多地用于敏感应用领域（例如教育和就业）以进行决策，由这些模型计算出的决策不会出现意外偏差，这一点至关重要。但是，我们如何自动验证任意机器学习模型的公平性？对于给定的机器学习模型和一组敏感输入参数，我们的AEQUITAS方法自动发现突出公平违规的歧视性输入。 AEQUITAS的核心是在输入空间采用概率搜索的三种新策略，旨在揭示公平违规。我们的AEQUITAS方法利用通用机器学习模型中的固有鲁棒性来设计和实现可扩展的测试生成方法。我们生成的测试输入的一个吸引人的特性是它们可以系统地添加到底层模型的训练集中并提高其公平性。为此，我们设计了一个完全自动化的模块，以确保提高底层模型的公平性。
 我们实施了AEQUITAS，我们已经在六个最先进的分类器上进行了评估，包括一个设计有公平约束的分类器。我们证明AEQUITAS有效地生成输入以揭示所有主题分类器中的公平违规，并使用生成的测试输入系统地改善各个模型的公平性。在我们的评估中，AEQUITAS产生高达70％的歧视性输入（w.r.t.生成的输入总数），并利用这些输入将公平性提高到94％。

##### URL
[http://arxiv.org/abs/1807.00468](http://arxiv.org/abs/1807.00468)

##### PDF
[http://arxiv.org/pdf/1807.00468](http://arxiv.org/pdf/1807.00468)

