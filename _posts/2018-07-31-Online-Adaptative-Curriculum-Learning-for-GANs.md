---
layout: post
title: "Online Adaptative Curriculum Learning for GANs"
date: 2018-07-31 18:34:56
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Optimization
author: Thang Doan, Joao Monteiro, Isabela Albuquerque, Bogdan Mazoure, Audrey Durand, Joelle Pineau, R Devon Hjelm
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) can successfully learn a probability distribution and produce realistic samples. However, open questions such as sufficient convergence conditions and mode collapse still persist. In this paper, we build on existing work in the area by proposing a novel framework for training the generator against an ensemble of discriminator networks, which can be seen as a one-student/multiple-teachers setting. We formalize this problem within the non-stationary Multi-Armed Bandit (MAB) framework, where we evaluate the capability of a bandit algorithm to select discriminators for providing the generator with feedback during learning. To this end, we propose a reward function which reflects the amount of knowledge learned by the generator and dynamically selects the optimal discriminator network. Finally, we connect our algorithm to stochastic optimization methods and show that existing methods using multiple discriminators in literature can be recovered from our parametric model. Experimental results based on the Fr\'echet Inception Distance (FID) demonstrates faster convergence than existing baselines and show that our method learns a curriculum.

##### Abstract (translated by Google)
生成性对抗网络（GAN）可以成功地学习概率分布并生成真实的样本。然而，诸如充分收敛条件和模式崩溃等悬而未决的问题仍然存在。在本文中，我们建立了一个新的框架，用于培训发电机对抗一系列鉴别网络，这可以被视为一个学生/多个教师的环境。我们在非固定多武装强盗（MAB）框架中正式化了这个问题，我们评估了强盗算法选择鉴别器的能力，以便在学习过程中为发生器提供反馈。为此，我们提出了一种奖励函数，它反映了生成器学到的知识量并动态选择最佳鉴别器网络。最后，我们将算法与随机优化方法联系起来，并表明在文献中使用多个鉴别器的现有方法可以从我们的参数模型中恢复。基于Fr \'echet初始距离（FID）的实验结果表明，比现有基线更快收敛，并表明我们的方法学习课程。

##### URL
[https://arxiv.org/abs/1808.00020](https://arxiv.org/abs/1808.00020)

##### PDF
[https://arxiv.org/pdf/1808.00020](https://arxiv.org/pdf/1808.00020)

