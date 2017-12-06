---
layout: post
title: 'Towards Diverse and Natural Image Descriptions via a Conditional GAN'
date: 2017-08-11 05:02:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN Reinforcement_Learning Caption RNN
author: Bo Dai, Sanja Fidler, Raquel Urtasun, Dahua Lin
---

* content
{:toc}

##### Abstract
Despite the substantial progress in recent years, the image captioning techniques are still far from being perfect.Sentences produced by existing methods, e.g. those based on RNNs, are often overly rigid and lacking in variability. This issue is related to a learning principle widely used in practice, that is, to maximize the likelihood of training samples. This principle encourages high resemblance to the "ground-truth" captions while suppressing other reasonable descriptions. Conventional evaluation metrics, e.g. BLEU and METEOR, also favor such restrictive methods. In this paper, we explore an alternative approach, with the aim to improve the naturalness and diversity -- two essential properties of human expression. Specifically, we propose a new framework based on Conditional Generative Adversarial Networks (CGAN), which jointly learns a generator to produce descriptions conditioned on images and an evaluator to assess how well a description fits the visual content. It is noteworthy that training a sequence generator is nontrivial. We overcome the difficulty by Policy Gradient, a strategy stemming from Reinforcement Learning, which allows the generator to receive early feedback along the way. We tested our method on two large datasets, where it performed competitively against real people in our user study and outperformed other methods on various tasks.

##### Abstract (translated by Google)
尽管近年来取得了实质性的进展，但图像字幕技术还远未完善。现有方法产生的句子，例如那些基于RNN的，往往过于僵化，缺乏可变性。这个问题涉及到实践中广泛使用的学习原则，即最大化训练样本的可能性。这个原则鼓励高度相似的“地面真相”字幕，同时压制其他合理的描述。常规的评估指标，例如BLEU和METEOR也赞成这种限制性的方法。在本文中，我们探讨另一种方法，目的是改善自然和多样性 - 人类表达的两个基本属性。具体来说，我们提出了一个基于条件生成敌对网络（CGAN）的新框架，它们共同学习一个生成器来产生对图像有条件的描述，一个评估者来评估描述如何适合视觉内容。值得注意的是，训练序列生成器是非常重要的。我们通过策略梯度（一种源自强化学习的策略）来克服困难，这种策略允许发生器在一路上获得早期反馈。我们在两个大数据集上测试了我们的方法，在我们的用户研究中，它对真实的人进行了竞争性的表现，并且在各种任务上胜过了其他的方法。

##### URL
[https://arxiv.org/abs/1703.06029](https://arxiv.org/abs/1703.06029)

