---
layout: post
title: "Pathologies of Neural Models Make Interpretations Difficult"
date: 2018-08-14 17:01:55
categories: arXiv_CL
tags: arXiv_CL Regularization Salient
author: Shi Feng, Eric Wallace, Alvin Grissom II, Mohit Iyyer, Pedro Rodriguez, Jordan Boyd-Graber
mathjax: true
---

* content
{:toc}

##### Abstract
Model interpretability is a crucial problem in neural networks. Existing interpretation methods highlight salient input features, often determining each feature's importance based on gradient information from the model. We instead remove the least influential words, one at a time, from language inputs. This exposes pathological model behavior on language tasks: models produce high confidence values for reduced inputs, even when humans find them nonsensical. We examine the reasons for this behavior and suggest methods of mitigation. Our results have implications for gradient-based interpretation methods, showing that determining word importance using a model's gradient often does not align with humans' perceived importance of that word. We propose a simple entropy regularization technique that mitigates these issues without affecting performance on clean examples.

##### Abstract (translated by Google)
模型可解释性是神经网络中的一个关键问题。现有的解释方法突出显着的输入特征，通常基于来自模型的梯度信息确定每个特征的重要性。相反，我们从语言输入中删除最不具影响力的单词，一次一个。这暴露了语言任务的病理模型行为：模型为减少输入产生高置信度值，即使人们发现它们是荒谬的。我们检查了这种行为的原因并提出了缓解方法。我们的结果对基于梯度的解释方法有影响，表明使用模型的梯度确定单词重要性通常不符合人们对该单词的感知重要性。我们提出了一种简单的熵正则化技术，可以在不影响干净示例性能的情况下缓解这些问题。

##### URL
[http://arxiv.org/abs/1804.07781](http://arxiv.org/abs/1804.07781)

##### PDF
[http://arxiv.org/pdf/1804.07781](http://arxiv.org/pdf/1804.07781)

