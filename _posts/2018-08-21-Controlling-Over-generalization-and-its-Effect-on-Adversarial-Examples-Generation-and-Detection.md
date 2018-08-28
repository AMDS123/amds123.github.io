---
layout: post
title: "Controlling Over-generalization and its Effect on Adversarial Examples Generation and Detection"
date: 2018-08-21 02:05:57
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN Classification Prediction Detection
author: Mahdieh Abbasi, Arezoo Rajabi, Azadeh Sadat Mozafari, Rakesh B. Bobba, Christian Gagne
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) allowed improving the state-of-the-art for many vision applications. However, naive CNNs suffer from two serious issues: vulnerability to adversarial examples and making incorrect but confident predictions for out-distribution samples. In this paper, we draw a connection between these two issues of CNNs through over-generalization. We reveal an augmented CNN (an extra output class added) as a simple yet effective end-to-end approach has the capacity for controlling over-generalization. We demonstrate training an augmented CNN on only a properly selected natural out-distribution dataset and interpolated samples empowers it to classify a wide range of unseen out-distribution samples as dustbin. Meanwhile, its misclassification rates on a broad spectrum of well-known black-box adversaries drop drastically as it classifies a portion of adversaries as dustbin class (rejection option) while correctly classifies some of the remaining. However, such an augmented CNN is never trained with any types of adversaries. Finally, generation of white-box adversarial attacks using augmented CNNs can be harder as the attack algorithms have to avoid dustbin regions for generating actual adversaries.

##### Abstract (translated by Google)
卷积神经网络（CNN）允许改进许多视觉应用的最新技术。然而，幼稚的CNN遭受两个严重问题：易受对抗性示例的影响，并且对于分发样本做出错误但有信心的预测。在本文中，我们通过过度概括将这两个CNN问题联系起来。我们揭示了增强的CNN（增加了额外的输出类），因为简单而有效的端到端方法具有控制过度泛化的能力。我们展示了仅在正确选择的自然分布数据集上训练增强的CNN，并且插值样本使其能够将各种看不见的分布样本分类为垃圾箱。与此同时，它对众多知名黑匣子对手的错误分类率急剧下降，因为它将一部分对手分类为垃圾箱类别（拒绝选项），同时正确分类其余部分。然而，这种增强的CNN从未受过任何类型的对手的训练。最后，使用增强的CNN产生白盒对抗性攻击可能更难，因为攻击算法必须避免垃圾箱区域产生实际的对手。

##### URL
[http://arxiv.org/abs/1808.08282](http://arxiv.org/abs/1808.08282)

##### PDF
[http://arxiv.org/pdf/1808.08282](http://arxiv.org/pdf/1808.08282)

