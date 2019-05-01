---
layout: post
title: "Adversarial Teacher-Student Learning for Unsupervised Domain Adaptation"
date: 2019-04-30 15:43:09
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


##### URL
[http://arxiv.org/abs/1804.00644](http://arxiv.org/abs/1804.00644)

##### PDF
[http://arxiv.org/pdf/1804.00644](http://arxiv.org/pdf/1804.00644)

