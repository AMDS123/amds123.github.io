---
layout: post
title: "Towards Diverse and Natural Image Descriptions via a Conditional GAN"
date: 2017-08-11 05:02:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN Reinforcement_Learning Caption RNN
author: Bo Dai, Sanja Fidler, Raquel Urtasun, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the substantial progress in recent years, the image captioning techniques are still far from being perfect.Sentences produced by existing methods, e.g. those based on RNNs, are often overly rigid and lacking in variability. This issue is related to a learning principle widely used in practice, that is, to maximize the likelihood of training samples. This principle encourages high resemblance to the "ground-truth" captions while suppressing other reasonable descriptions. Conventional evaluation metrics, e.g. BLEU and METEOR, also favor such restrictive methods. In this paper, we explore an alternative approach, with the aim to improve the naturalness and diversity -- two essential properties of human expression. Specifically, we propose a new framework based on Conditional Generative Adversarial Networks (CGAN), which jointly learns a generator to produce descriptions conditioned on images and an evaluator to assess how well a description fits the visual content. It is noteworthy that training a sequence generator is nontrivial. We overcome the difficulty by Policy Gradient, a strategy stemming from Reinforcement Learning, which allows the generator to receive early feedback along the way. We tested our method on two large datasets, where it performed competitively against real people in our user study and outperformed other methods on various tasks.

##### Abstract (translated by Google)
尽管近年来取得了实质性进展，但是图像字幕技术仍远未完善。现有方法产生的效果，例如：基于RNN的那些通常过于严格且缺乏可变性。该问题与实践中广泛使用的学习原则有关，即最大化训练样本的可能性。这一原则鼓励与“地面实况”字幕高度相似，同时抑制其他合理的描述。传统的评估指标，例如BLEU和METEOR也赞成这种限制性方法。在本文中，我们探索了另一种方法，旨在提高自然性和多样性 - 人类表达的两个基本属性。具体而言，我们提出了一种基于条件生成对抗网络（CGAN）的新框架，该框架联合学习生成器以生成以图像为条件的描述，并评估器评估描述与视觉内容的匹配程度。值得注意的是，训练序列发生器是非常重要的。我们克服了政策梯度的困难，这是一种源自强化学习的策略，它允许发电机在此过程中接收早期反馈。我们在两个大型数据集上测试了我们的方法，在我们的用户研究中它与真人竞争，并且在各种任务上表现优于其他方法。

##### URL
[https://arxiv.org/abs/1703.06029](https://arxiv.org/abs/1703.06029)

##### PDF
[https://arxiv.org/pdf/1703.06029](https://arxiv.org/pdf/1703.06029)

