---
layout: post
title: "Adversarial Machine Learning at Scale"
date: 2017-02-11 00:15:46
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Recommendation
author: Alexey Kurakin, Ian Goodfellow, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples are malicious inputs designed to fool machine learning models. They often transfer from one model to another, allowing attackers to mount black box attacks without knowledge of the target model's parameters. Adversarial training is the process of explicitly training a model on adversarial examples, in order to make it more robust to attack or to reduce its test error on clean inputs. So far, adversarial training has primarily been applied to small problems. In this research, we apply adversarial training to ImageNet. Our contributions include: (1) recommendations for how to succesfully scale adversarial training to large models and datasets, (2) the observation that adversarial training confers robustness to single-step attack methods, (3) the finding that multi-step attack methods are somewhat less transferable than single-step attack methods, so single-step attacks are the best for mounting black-box attacks, and (4) resolution of a "label leaking" effect that causes adversarially trained models to perform better on adversarial examples than on clean examples, because the adversarial example construction process uses the true label and the model can learn to exploit regularities in the construction process.

##### Abstract (translated by Google)
敌对的例子是用来欺骗机器学习模型的恶意输入。他们经常从一个模型转移到另一个模型，允许攻击者在不知道目标模型参数的情况下进行黑盒攻击。对抗训练是明确训练对抗性例子的模型的过程，以便使其更有力地攻击或减少对干净输入的测试错误。到目前为止，对抗训练主要应用于小问题。在这项研究中，我们将对抗训练应用于ImageNet。我们的贡献包括：（1）如何将对抗性训练成功地扩展到大型模型和数据集;（2）对抗性训练赋予单步攻击方法的稳健性;（3）多步攻击方法的发现比单步攻击方法稍差一点，所以单步攻击对于黑箱攻击是最好的;（4）解决“标签泄漏”效应，使对手训练的模型在对抗性的例子上表现得更好，而不是干净的例子，因为敌对的例子施工过程使用真正的标签，模型可以学习在施工过程中利用规律。

##### URL
[https://arxiv.org/abs/1611.01236](https://arxiv.org/abs/1611.01236)

##### PDF
[https://arxiv.org/pdf/1611.01236](https://arxiv.org/pdf/1611.01236)

