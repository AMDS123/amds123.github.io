---
layout: post
title: "Unifying Bilateral Filtering and Adversarial Training for Robust Neural Networks"
date: 2018-08-01 22:55:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Optimization
author: Neale Ratzlaff, Fuxin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recent analysis of deep neural networks has revealed their vulnerability to carefully structured adversarial examples. Many effective algorithms exist to craft these adversarial examples, but performant defenses seem to be far away. In this work, we explore the use of edge-aware bilateral filtering as a projection back to the space of natural images. We show that bilateral filtering is an effective defense in multiple attack settings, where the strength of the adversary gradually increases. In the case of adversary who has no knowledge of the defense, bilateral filtering can remove more than 90% of adversarial examples from a variety of different attacks. To harden our network against an adversary with complete knowledge of our defense, we adapt the bilateral filter as a trainable layer in a neural network. When trained under a framework of robust optimization, we show that the resulting model is hard to fool with even the best attack methods.

##### Abstract (translated by Google)
最近对深度神经网络的分析揭示了它们对精心构造的对抗性例子的脆弱性。有许多有效的算法来制作这些对抗性的例子，但是高效的防御似乎很遥远。在这项工作中，我们探索使用边缘感知双边滤波作为回归自然图像空间的投影。我们证明双边过滤是多种攻击设置中的有效防御，其中对手的力量逐渐增加。对于不了解防御的对手，双边过滤可以从各种不同的攻击中移除90％以上的对抗性示例。为了使我们的网络能够对抗完全了解我们防御的对手，我们将双边滤波器调整为神经网络中的可训练层。当在强大优化的框架下进行训练时，我们表明即使是最好的攻击方法，最终的模型也很难愚弄。

##### URL
[http://arxiv.org/abs/1804.01635](http://arxiv.org/abs/1804.01635)

##### PDF
[http://arxiv.org/pdf/1804.01635](http://arxiv.org/pdf/1804.01635)

