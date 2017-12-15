---
layout: post
title: "Knowledge Adaptation: Teaching to Adapt"
date: 2017-02-07 14:59:45
categories: arXiv_SD
tags: arXiv_SD Sentiment Knowledge Deep_Learning Detection
author: Sebastian Ruder, Parsa Ghaffari, John G. Breslin
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation is crucial in many real-world applications where the distribution of the training data differs from the distribution of the test data. Previous Deep Learning-based approaches to domain adaptation need to be trained jointly on source and target domain data and are therefore unappealing in scenarios where models need to be adapted to a large number of domains or where a domain is evolving, e.g. spam detection where attackers continuously change their tactics. To fill this gap, we propose Knowledge Adaptation, an extension of Knowledge Distillation (Bucilua et al., 2006; Hinton et al., 2015) to the domain adaptation scenario. We show how a student model achieves state-of-the-art results on unsupervised domain adaptation from multiple sources on a standard sentiment analysis benchmark by taking into account the domain-specific expertise of multiple teachers and the similarities between their domains. When learning from a single teacher, using domain similarity to gauge trustworthiness is inadequate. To this end, we propose a simple metric that correlates well with the teacher's accuracy in the target domain. We demonstrate that incorporating high-confidence examples selected by this metric enables the student model to achieve state-of-the-art performance in the single-source scenario.

##### Abstract (translated by Google)
训练数据的分布不同于测试数据的分布的许多实际应用中，领域适应是至关重要的。先前的基于深度学习的领域适应方法需要在源和目标领域数据上联合训练，并且因此在模型需要适应大量领域或者领域正在发展的情况下是不具有吸引力的。垃圾邮件检测攻击者不断地改变他们的策略。为了填补这一空白，我们提出了知识适应，这是知识蒸馏的延伸（Bucilua et al。，2006; Hinton et al。，2015）。我们展示了一个学生模型如何通过考虑多个教师领域特定的专业知识以及他们的领域之间的相似性，在标准情感分析基准上从多个来源获得最先进的无监督领域适应性结果。从单一的老师那里学习时，使用领域相似度来衡量可信度是不够的。为此，我们提出了一个简单的度量标准，与目标领域中教师的准确性相关联。我们证明，结合这个度量所选择的高可信度的例子使得学生模型能够在单一来源的场景中实现最先进的性能。

##### URL
[https://arxiv.org/abs/1702.02052](https://arxiv.org/abs/1702.02052)

##### PDF
[https://arxiv.org/pdf/1702.02052](https://arxiv.org/pdf/1702.02052)

