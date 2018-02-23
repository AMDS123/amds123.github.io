---
layout: post
title: "The Secret Sharer: Measuring Unintended Neural Network Memorization & Extracting Secrets"
date: 2018-02-22 18:42:41
categories: arXiv_AI
tags: arXiv_AI Regularization Deep_Learning
author: Nicholas Carlini, Chang Liu, Jernej Kos, &#xda;lfar Erlingsson, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models based on neural networks and deep learning are being rapidly adopted for many purposes. What those models learn, and what they may share, is a significant concern when the training data may contain secrets and the models are public -- e.g., when a model helps users compose text messages using models trained on all users' messages. 
 This paper presents exposure: a simple-to-compute metric that can be applied to any deep learning model for measuring the memorization of secrets. Using this metric, we show how to extract those secrets efficiently using black-box API access. Further, we show that unintended memorization occurs early, is not due to over-fitting, and is a persistent issue across different types of models, hyperparameters, and training strategies. We experiment with both real-world models (e.g., a state-of-the-art translation model) and datasets (e.g., the Enron email dataset, which contains users' credit card numbers) to demonstrate both the utility of measuring exposure and the ability to extract secrets. 
 Finally, we consider many defenses, finding some ineffective (like regularization), and others to lack guarantees. However, by instantiating our own differentially-private recurrent model, we validate that by appropriately investing in the use of state-of-the-art techniques, the problem can be resolved, with high utility.

##### Abstract (translated by Google)
基于神经网络和深度学习的机器学习模型正在迅速地被用于多种目的。当训练数据可能包含秘密并且模型是公开的时候，这些模型学到什么以及它们可以共享什么，这是一个重要的问题 - 例如，当模型可以帮助用户使用在所有用户的消息上训练的模型组成文本消息时。
 本白皮书介绍了暴露度：一种易于计算的度量标准，可应用于任何深度学习模型，用于测量秘密的记忆。使用这个指标，我们展示了如何使用黑盒API访问有效地提取这些秘密。此外，我们表明，意外记忆发生的早，不是由于过度拟合，并且是跨不同类型的模型，超参数和培训策略的持久性问题。我们试验了真实世界模型（例如，最先进的翻译模型）和数据集（例如包含用户信用卡号码的安然电子邮件数据集），以展示测量暴露的效用和提取秘密的能力。
 最后，我们考虑许多防御措施，发现一些无效（如正规化），而另一些则缺乏保证。然而，通过实例化我们自己的差异 - 私人循环模型，我们验证了通过适当地投资使用最先进的技术，问题可以得到解决，具有很高的实用性。

##### URL
[http://arxiv.org/abs/1802.08232](http://arxiv.org/abs/1802.08232)

##### PDF
[http://arxiv.org/pdf/1802.08232](http://arxiv.org/pdf/1802.08232)

