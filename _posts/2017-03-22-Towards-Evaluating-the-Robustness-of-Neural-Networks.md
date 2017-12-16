---
layout: post
title: "Towards Evaluating the Robustness of Neural Networks"
date: 2017-03-22 17:46:16
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Nicholas Carlini, David Wagner
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks provide state-of-the-art results for most machine learning tasks. Unfortunately, neural networks are vulnerable to adversarial examples: given an input $x$ and any target classification $t$, it is possible to find a new input $x'$ that is similar to $x$ but classified as $t$. This makes it difficult to apply neural networks in security-critical areas. Defensive distillation is a recently proposed approach that can take an arbitrary neural network, and increase its robustness, reducing the success rate of current attacks' ability to find adversarial examples from $95\%$ to $0.5\%$. In this paper, we demonstrate that defensive distillation does not significantly increase the robustness of neural networks by introducing three new attack algorithms that are successful on both distilled and undistilled neural networks with $100\%$ probability. Our attacks are tailored to three distance metrics used previously in the literature, and when compared to previous adversarial example generation algorithms, our attacks are often much more effective (and never worse). Furthermore, we propose using high-confidence adversarial examples in a simple transferability test we show can also be used to break defensive distillation. We hope our attacks will be used as a benchmark in future defense attempts to create neural networks that resist adversarial examples.

##### Abstract (translated by Google)
神经网络为大多数机器学习任务提供了最先进的结果。不幸的是，神经网络容易受到敌对的例子：给定一个输入$ x $和任何目标分类$ t $，就有可能找到一个新的输入$ x $ $，它类似于$ x $但被归类为$ t $。这使得将神经网络应用于安全关键领域变得困难。防御性蒸馏是最近提出的一种方法，可以采用任意的神经网络，并增加其鲁棒性，将当前攻击成功率从95％到$ 0.5％的对手例子的能力降低。在本文中，我们证明了防御性蒸馏不会显着增加神经网络的鲁棒性，通过引入三个新的攻击算法，在蒸馏和未经蒸馏的神经网络上以$ 100 \％$概率成功。我们的攻击是针对以前在文献中使用的三种距离度量而定制的，与之前的对抗性示例生成算法相比，我们的攻击往往更加有效（并且从不会更糟糕）。此外，我们建议在一个简单的可转移性测试中使用高信度的对抗性的例子，我们显示也可以用来打破防御性蒸馏。我们希望我们的攻击将成为未来防御企图创建抵制敌对的神经网络的基准。

##### URL
[https://arxiv.org/abs/1608.04644](https://arxiv.org/abs/1608.04644)

##### PDF
[https://arxiv.org/pdf/1608.04644](https://arxiv.org/pdf/1608.04644)

