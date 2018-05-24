---
layout: post
title: "Robust Perception through Analysis by Synthesis"
date: 2018-05-23 14:16:22
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Lukas Schott, Jonas Rauber, Wieland Brendel, Matthias Bethge
mathjax: true
---

* content
{:toc}

##### Abstract
The intriguing susceptibility of deep neural networks to minimal input perturbations suggests that the gap between human and machine perception is still large. We here argue that despite much effort, even on MNIST the most successful defenses are still far away from the robustness of human perception. We here reconsider MNIST and establish a novel defense that is inspired by the abundant feedback connections present in the human visual cortex. We suggest that this feedback plays a role in estimating the likelihood of a sensory stimulus with respect to the hidden causes inferred by the cortex and allow the brain to mute distracting patterns. We implement this analysis by synthesis idea in the form of a discriminatively fine-tuned Bayesian classifier using a set of class-conditional variational autoe ncoders (VAEs). To evaluate model robustness we go to great length to find maximally effective adversarial attacks, including decision-based, score-based and gradient-based attacks. The results suggest that this ansatz yields state-of-the-art robustness on MNIST against L0, L2 and L infinity perturbations and we demonstrate that most adversarial examples are strongly perturbed towards the perceptual boundary between the original and the adversarial class.

##### Abstract (translated by Google)
深度神经网络对最小输入扰动的敏感性表明人类和机器感知之间的差距仍然很大。我们在这里争辩说，尽管付出了很多努力，即使在MNIST上，最成功的防御措施仍然远离人类感知的稳健性。我们在这里重新考虑MNIST并建立一种新颖的防御方式，它受到人类视觉皮层中丰富的反馈联系的启发。我们建议这种反馈在估计感觉刺激与由皮层推断的隐藏原因相关的可能性中发挥作用，并允许大脑静音分散注意力的模式。我们使用一组有条件的变分自动编码器（VAEs）以有区别的微调贝叶斯分类器的形式，通过综合思想来实现这种分析。为了评估模型的鲁棒性，我们将竭尽全力寻找最有效的敌对攻击，包括基于决策的，基于分数的和基于梯度的攻击。结果表明，这ansatz产生MNIST对L0，L2和L无穷大扰动的最先进的稳健性，我们证明，大多数敌对的例子强烈扰乱原始和对抗类之间的感知边界。

##### URL
[http://arxiv.org/abs/1805.09190](http://arxiv.org/abs/1805.09190)

##### PDF
[http://arxiv.org/pdf/1805.09190](http://arxiv.org/pdf/1805.09190)

