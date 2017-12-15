---
layout: post
title: "Removing Biases from Trainable MT Metrics by Using Self-Training"
date: 2015-08-10 22:24:36
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Miloš Stanojević
mathjax: true
---

* content
{:toc}

##### Abstract
Most trainable machine translation (MT) metrics train their weights on human judgments of state-of-the-art MT systems outputs. This makes trainable metrics biases in many ways. One of them is preferring longer translations. These biased metrics when used for tuning are evaluating different types of translations -- n-best lists of translations with very diverse quality. Systems tuned with these metrics tend to produce overly long translations that are preferred by the metric but not by humans. This is usually solved by manually tweaking metric's weights to equally value recall and precision. Our solution is more general: (1) it does not address only the recall bias but also all other biases that might be present in the data and (2) it does not require any knowledge of the types of features used which is useful in cases when manual tuning of metric's weights is not possible. This is accomplished by self-training on unlabeled n-best lists by using metric that was initially trained on standard human judgments. One way of looking at this is as domain adaptation from the domain of state-of-the-art MT translations to diverse n-best list translations.

##### Abstract (translated by Google)
大多数可训练的机器翻译（MT）度量标准在对最先进的MT系统输出的人为判断上进行权重训练。这使得可训练指标在很多方面都有偏差。其中之一是宁愿更长的翻译。当用于调整时，这些有偏差的度量标准正在评估不同类型的翻译 - 具有非常不同质量的翻译的最佳列表。用这些指标调整的系统倾向于产生过度长的翻译，这是由度量偏好的，而不是由人类偏好的。通常通过手动调整度量的权重来解决这个问题，以便同样地提高召回率和精度。我们的解决方案是更一般的：（1）它不仅仅解决回忆偏差，而且解决数据中可能存在的所有其他偏差，（2）它不需要任何关于在案例中有用的特征类型的知识当手动调整度量权重是不可能的。这是通过使用最初接受标准人类判断训练的度量，通过对未标记的n最佳列表进行自我训练来实现的。看待这个问题的一个方法就是从最先进的MT翻译领域到多元化的n最佳列表翻译的领域调整。

##### URL
[https://arxiv.org/abs/1508.02445](https://arxiv.org/abs/1508.02445)

##### PDF
[https://arxiv.org/pdf/1508.02445](https://arxiv.org/pdf/1508.02445)

