---
layout: post
title: "Deep Defense: Training DNNs with Improved Adversarial Robustness"
date: 2018-12-20 01:53:51
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Optimization Classification Prediction
author: Ziang Yan, Yiwen Guo, Changshui Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the efficacy on a variety of computer vision tasks, deep neural networks (DNNs) are vulnerable to adversarial attacks, limiting their applications in security-critical systems. Recent works have shown the possibility of generating imperceptibly perturbed image inputs (a.k.a., adversarial examples) to fool well-trained DNN classifiers into making arbitrary predictions. To address this problem, we propose a training recipe named "deep defense". Our core idea is to integrate an adversarial perturbation-based regularizer into the classification objective, such that the obtained models learn to resist potential attacks, directly and precisely. The whole optimization problem is solved just like training a recursive network. Experimental results demonstrate that our method outperforms training with adversarial/Parseval regularizations by large margins on various datasets (including MNIST, CIFAR-10 and ImageNet) and different DNN architectures. Code and models for reproducing our results are available at https://github.com/ZiangYan/deepdefense.pytorch

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.00404](http://arxiv.org/abs/1803.00404)

##### PDF
[http://arxiv.org/pdf/1803.00404](http://arxiv.org/pdf/1803.00404)

