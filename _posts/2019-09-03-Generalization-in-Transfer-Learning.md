---
layout: post
title: "Generalization in Transfer Learning"
date: 2019-09-03 17:57:07
categories: arXiv_AI
tags: arXiv_AI Regularization Adversarial Knowledge Reinforcement_Learning Transfer_Learning
author: Suzan Ece Ada, Emre Ugur, H. Levent Akin
mathjax: true
---

* content
{:toc}

##### Abstract
Agents trained with deep reinforcement learning algorithms are capable of performing highly complex tasks including locomotion in continuous environments. In order to attain a human-level performance, the next step of research should be to investigate the ability to transfer the learning acquired in one task to a different set of tasks. Concerns on generalization and overfitting in deep reinforcement learning are not usually addressed in current transfer learning research. This issue results in underperforming benchmarks and inaccurate algorithm comparisons due to rudimentary assessments. In this study, we primarily propose regularization techniques in deep reinforcement learning for continuous control through the application of sample elimination and early stopping. First, the importance of the inclusion of training iteration to the hyperparameters in deep transfer learning problems will be emphasized. Because source task performance is not indicative of the generalization capacity of the algorithm, we start by proposing various transfer learning evaluation methods that acknowledge the training iteration as a hyperparameter. In line with this, we introduce an additional step of resorting to earlier snapshots of policy parameters depending on the target task due to overfitting to the source task. Then, in order to generate robust policies,we discard the samples that lead to overfitting via strict clipping. Furthermore, we increase the generalization capacity in widely used transfer learning benchmarks by using entropy bonus, different critic methods and curriculum learning in an adversarial setup. Finally, we evaluate the robustness of these techniques and algorithms on simulated robots in target environments where the morphology of the robot, gravity and tangential friction of the environment are altered from the source environment.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01331](https://arxiv.org/abs/1909.01331)

##### PDF
[https://arxiv.org/pdf/1909.01331](https://arxiv.org/pdf/1909.01331)

