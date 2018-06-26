---
layout: post
title: "On Adversarial Examples for Character-Level Neural Machine Translation"
date: 2018-06-23 20:08:56
categories: arXiv_AI
tags: arXiv_AI Adversarial NMT Deep_Learning
author: Javid Ebrahimi, Daniel Lowd, Dejing Dou
mathjax: true
---

* content
{:toc}

##### Abstract
Evaluating on adversarial examples has become a standard procedure to measure robustness of deep learning models. Due to the difficulty of creating white-box adversarial examples for discrete text input, most analyses of the robustness of NLP models have been done through black-box adversarial examples. We investigate adversarial examples for character-level neural machine translation (NMT), and contrast black-box adversaries with a novel white-box adversary, which employs differentiable string-edit operations to rank adversarial changes. We propose two novel types of attacks which aim to remove or change a word in a translation, rather than simply break the NMT. We demonstrate that white-box adversarial examples are significantly stronger than their black-box counterparts in different attack scenarios, which show more serious vulnerabilities than previously known. In addition, after performing adversarial training, which takes only 3 times longer than regular training, we can improve the model's robustness significantly.

##### Abstract (translated by Google)
对敌对案例进行评估已成为衡量深度学习模型稳健性的标准程序。由于难以创建用于离散文本输入的白盒对抗性例子，因此大多数NLP模型的鲁棒性分析都是通过黑盒对抗性例子完成的。我们调查了角色层次神经机器翻译（NMT）的对抗性例子，并与一个新颖的白盒对手对比黑盒对手，该对手采用可区分的字符串编辑操作对对抗性变化进行排名。我们提出两种新型的攻击方式，旨在移除或更改翻译中的单词，而不是简单地打破NMT。我们证明，在不同的攻击场景中，白盒对抗示例比其黑盒对应示例明显更强大，这些示例显示比先前已知的更严重的漏洞。此外，在进行对抗训练后，训练时间仅比常规训练长3倍，我们可以显着提高模型的鲁棒性。

##### URL
[http://arxiv.org/abs/1806.09030](http://arxiv.org/abs/1806.09030)

##### PDF
[http://arxiv.org/pdf/1806.09030](http://arxiv.org/pdf/1806.09030)

