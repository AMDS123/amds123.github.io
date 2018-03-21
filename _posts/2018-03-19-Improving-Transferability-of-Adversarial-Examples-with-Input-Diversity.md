---
layout: post
title: "Improving Transferability of Adversarial Examples with Input Diversity"
date: 2018-03-19 15:07:51
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge CNN
author: Cihang Xie, Zhishuai Zhang, Jianyu Wang, Yuyin Zhou, Zhou Ren, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Though convolutional neural networks have achieved state-of-the-art performance on various vision tasks, they are extremely vulnerable to adversarial examples, which are obtained by adding human-imperceptible perturbations to the original images. Adversarial examples can thus be used as an useful tool to evaluate and select the most robust models in safety-critical applications. However, most of the existing adversarial attacks only achieve relatively low success rates under the challenging black-box setting, where the attackers have no knowledge of the model structure and parameters. To this end, we propose to improve the transferability of adversarial examples by creating diverse input patterns. Instead of only using the original images to generate adversarial examples, our method applies random transformations to the input images at each iteration. Extensive experiments on ImageNet show that the proposed attack method can generate adversarial examples that transfer much better to different networks than existing baselines. To further improve the transferability, we (1) integrate the recently proposed momentum method into the attack process; and (2) attack an ensemble of networks simultaneously. By evaluating our method against top defense submissions and official baselines from NIPS 2017 adversarial competition, this enhanced attack reaches an average success rate of 73.0%, which outperforms the top 1 attack submission in the NIPS competition by a large margin of 6.6%. We hope that our proposed attack strategy can serve as a benchmark for evaluating the robustness of networks to adversaries and the effectiveness of different defense methods in future. The code is public available at this https URL

##### Abstract (translated by Google)
虽然卷积神经网络已经在各种视觉任务上取得了最先进的性能，但它们极易受到对抗性例子的影响，这些例子是通过在原始图像上添加人为不可察觉的干扰而获得的。敌对案例因此可以用作评估和选择安全关键型应用程序中最稳健模型的有用工具。然而，大多数现有的敌对攻击在具有挑战性的黑匣子设置下只能实现相对较低的成功率，攻击者不知道模型结构和参数。为此，我们建议通过创建不同的输入模式来提高对抗性例子的可转移性。我们的方法不是仅使用原始图像来生成敌对示例，而是在每次迭代时对输入图像应用随机变换。在ImageNet上进行的大量实验表明，所提出的攻击方法可以产生对抗性的例子，这些例子比现有的基线更好地转移到不同的网络。为了进一步提高可转移性，我们（1）将最近提出的动量方法整合到攻击过程中;和（2）同时攻击整个网络。通过评估我们针对NIPS 2017对抗竞争中的顶级防御提交和正式基线的方法，此增强攻击的平均成功率达到73.0％，比NIPS竞争中提交的最高的1个攻击提高了6.6％。我们希望我们提出的攻击策略可以作为评估网络对敌手的鲁棒性以及未来不同防御方法的有效性的基准。该代码在此https URL处公开

##### URL
[https://arxiv.org/abs/1803.06978](https://arxiv.org/abs/1803.06978)

##### PDF
[https://arxiv.org/pdf/1803.06978](https://arxiv.org/pdf/1803.06978)

