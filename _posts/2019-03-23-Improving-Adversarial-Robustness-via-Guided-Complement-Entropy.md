---
layout: post
title: "Improving Adversarial Robustness via Guided Complement Entropy"
date: 2019-03-23 11:14:59
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Hao-Yun Chen, Jhao-Hong Liang, Shih-Chieh Chang, Jia-Yu Pan, Yu-Ting Chen, Wei Wei, Da-Cheng Juan
mathjax: true
---

* content
{:toc}

##### Abstract
Model robustness has been an important issue, since adding small adversarial perturbations to images is sufficient to drive the model accuracy down to nearly zero. In this paper, we propose a new training objective "Guided Complement Entropy" (GCE) that has dual desirable effects: (a) neutralizing the predicted probabilities of incorrect classes, and (b) maximizing the predicted probability of the ground-truth class, particularly when (a) is achieved. Training with GCE encourages models to learn latent representations where samples of different classes form distinct clusters, which we argue, improves the model robustness against adversarial perturbations. Furthermore, compared with the state-of-the-arts trained with cross-entropy, same models trained with GCE achieve significant improvements on the robustness against white-box adversarial attacks, both with and without adversarial training. When no attack is present, training with GCE also outperforms cross-entropy in terms of model accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09799](http://arxiv.org/abs/1903.09799)

##### PDF
[http://arxiv.org/pdf/1903.09799](http://arxiv.org/pdf/1903.09799)

