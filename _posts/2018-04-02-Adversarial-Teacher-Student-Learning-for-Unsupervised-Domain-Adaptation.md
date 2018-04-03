---
layout: post
title: "Adversarial Teacher-Student Learning for Unsupervised Domain Adaptation"
date: 2018-04-02 17:45:57
categories: arXiv_CL
tags: arXiv_CL Adversarial Knowledge Transfer_Learning Classification Recognition
author: Zhong Meng, Jinyu Li, Yifan Gong, Biing-Hwang (Fred) Juang
mathjax: true
---

* content
{:toc}

##### Abstract
The teacher-student (T/S) learning has been shown effective in unsupervised domain adaptation [1]. It is a form of transfer learning, not in terms of the transfer of recognition decisions, but the knowledge of posteriori probabilities in the source domain as evaluated by the teacher model. It learns to handle the speaker and environment variability inherent in and restricted to the speech signal in the target domain without proactively addressing the robustness to other likely conditions. Performance degradation may thus ensue. In this work, we advance T/S learning by proposing adversarial T/S learning to explicitly achieve condition-robust unsupervised domain adaptation. In this method, a student acoustic model and a condition classifier are jointly optimized to minimize the Kullback-Leibler divergence between the output distributions of the teacher and student models, and simultaneously, to min-maximize the condition classification loss. A condition-invariant deep feature is learned in the adapted student model through this procedure. We further propose multi-factorial adversarial T/S learning which suppresses condition variabilities caused by multiple factors simultaneously. Evaluated with the noisy CHiME-3 test set, the proposed methods achieve relative word error rate improvements of 44.60% and 5.38%, respectively, over a clean source model and a strong T/S learning baseline model.

##### Abstract (translated by Google)
在无监督的领域适应中，师生（T / S）学习已被证明是有效的[1]。它是一种转移学习的形式，而不是转移识别决策的方式，而是由教师模型评估的源域中后验概率的知识。它学会处理目标域中固有的和限制于语音信号的说话人和环境变化性，而不主动解决对其他可能情况的鲁棒性。这样可能会导致性能下降。在这项工作中，我们提出T / S学习，提出敌对T / S学习以明确实现条件稳健的无监督域自适应。在这种方法中，学生声学模型和条件分类器被联合优化以最小化教师和学生模型的输出分布之间的Kullback-Leibler分歧，并且同时最小化条件分类损失的最大化。通过这个过程在适应的学生模型中学习一个条件不变的深层特征。我们进一步提出了多因子对抗T / S学习，它可以同时抑制多因素引起的条件变化。对于干净的源模型和强大的T / S学习基线模型，使用嘈杂的CHiME-3测试集进行评估，所提出的方法分别实现了44.60％和5.38％的相对误字率改进。

##### URL
[http://arxiv.org/abs/1804.00644](http://arxiv.org/abs/1804.00644)

##### PDF
[http://arxiv.org/pdf/1804.00644](http://arxiv.org/pdf/1804.00644)

