---
layout: post
title: "On-line Adaptative Curriculum Learning for GANs"
date: 2018-09-12 15:52:10
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Thang Doan, Joao Monteiro, Isabela Albuquerque, Bogdan Mazoure, Audrey Durand, Joelle Pineau, R Devon Hjelm
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) can successfully approximate a probability distribution and produce realistic samples. However, open questions such as sufficient convergence conditions and mode collapse still persist. In this paper, we build on existing work in the area by proposing a novel framework for training the generator against an ensemble of discriminator networks, which can be seen as a one-student/multiple-teachers setting. We formalize this problem within the full-information adversarial bandit framework, where we evaluate the capability of an algorithm to select mixtures of discriminators for providing the generator with feedback during learning. To this end, we propose a reward function which reflects the progress made by the generator and dynamically update the mixture weights allocated to each discriminator. We also draw connections between our algorithm and stochastic optimization methods and then show that existing approaches using multiple discriminators in literature can be recovered from our framework. We argue that less expressive discriminators are smoother and have a general coarse grained view of the modes map, which enforces the generator to cover a wide portion of the data distribution support. On the other hand, highly expressive discriminators ensure samples quality. Finally, experimental results show that our approach improves samples quality and diversity over existing baselines by effectively learning a curriculum. These results also support the claim that weaker discriminators have higher entropy improving modes coverage.

##### Abstract (translated by Google)
生成对抗网络（GAN）可以成功地近似概率分布并产生真实的样本。然而，诸如充分收敛条件和模式崩溃等悬而未决的问题仍然存在。在本文中，我们建立了一个新的框架，用于培训发电机对抗一系列鉴别网络，这可以被视为一个学生/多个教师的环境。我们在全信息对抗强盗框架中正式化了这个问题，我们评估算法选择判别器混合的能力，以便在学习过程中为发生器提供反馈。为此，我们提出了一个奖励函数，它反映了生成器所取得的进展并动态更新分配给每个鉴别器的混合权重。我们还在算法和随机优化方法之间建立联系，然后表明在文献中使用多个鉴别器的现有方法可以从我们的框架中恢复。我们认为不那么富有表现力的鉴别器更平滑，并且具有模式映射的一般粗粒度视图，这强制生成器覆盖了大部分数据分布支持。另一方面，高度表达的鉴别器确保样品质量。最后，实验结果表明，我们的方法通过有效地学习课程来提高现有基线的样本质量和多样性。这些结果也支持了较弱的鉴别器具有较高的熵改善模式覆盖率的说法。

##### URL
[https://arxiv.org/abs/1808.00020](https://arxiv.org/abs/1808.00020)

##### PDF
[https://arxiv.org/pdf/1808.00020](https://arxiv.org/pdf/1808.00020)

