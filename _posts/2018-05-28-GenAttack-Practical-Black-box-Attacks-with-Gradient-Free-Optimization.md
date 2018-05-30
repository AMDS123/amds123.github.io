---
layout: post
title: "GenAttack: Practical Black-box Attacks with Gradient-Free Optimization"
date: 2018-05-28 06:40:55
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization Recognition
author: Moustafa Alzantot, Yash Sharma, Supriyo Chakraborty, Mani Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) are vulnerable to adversarial examples, even in the black-box case, where the attacker is limited to solely query access. Existing blackbox approaches to generating adversarial examples typically require a significant amount of queries, either for training a substitute network or estimating gradients from the output scores. We introduce GenAttack, a gradient-free optimization technique which uses genetic algorithms for synthesizing adversarial examples in the black-box setting. Our experiments on the MNIST, CIFAR-10, and ImageNet datasets show that GenAttack can successfully generate visually imperceptible adversarial examples against state-of-the-art image recognition models with orders of magnitude fewer queries than existing approaches. For example, in our CIFAR-10 experiments, GenAttack required roughly 2,568 times less queries than the current state-of-the-art black-box attack. Furthermore, we show that GenAttack can successfully attack both the state-of-the-art ImageNet defense, ensemble adversarial training, and non-differentiable, randomized input transformation defenses. GenAttack's success against ensemble adversarial training demonstrates that its query efficiency enables it to exploit the defense's weakness to direct black-box attacks. GenAttack's success against non-differentiable input transformations indicates that its gradient-free nature enables it to be applicable against defenses which perform gradient masking/obfuscation to confuse the attacker. Our results suggest that population-based optimization opens up a promising area of research into effective gradient-free black-box attacks.

##### Abstract (translated by Google)
深度神经网络（DNN）容易受到对抗性例子的攻击，即使在黑客案例中，攻击者仅限于查询访问。现有的黑盒子方法产生敌对的例子通常需要大量的查询，用于培训替代网络或从输出分数估计梯度。我们介绍GenAttack，一种无梯度优化技术，它使用遗传算法在黑盒子设置中合成对抗示例。我们在MNIST，CIFAR-10和ImageNet数据集上进行的实验表明，GenAttack可以成功地产生视觉上难以察觉的对抗性示例，比现有技术的图像识别模型少数量级，比现有方法少。例如，在我们的CIFAR-10实验中，GenAttack比当前最先进的黑盒攻击所需的查询少了大约2,568倍。此外，我们证明GenAttack可以成功攻击最先进的ImageNet防御系统，集成对抗训练以及不可区分的随机输入转换防御。 GenAttack的成功对抗集合对抗训练表明，其查询效率使其能够利用防御的弱点来指导黑盒攻击。 GenAttack成功地针对非可微分输入转换，表明它的无梯度特性使其适用于执行梯度掩蔽/混淆以混淆攻击者的防御。我们的研究结果表明，基于人口的优化为有效的无梯度黑盒攻击开辟了一个有前途的研究领域。

##### URL
[http://arxiv.org/abs/1805.11090](http://arxiv.org/abs/1805.11090)

##### PDF
[http://arxiv.org/pdf/1805.11090](http://arxiv.org/pdf/1805.11090)

