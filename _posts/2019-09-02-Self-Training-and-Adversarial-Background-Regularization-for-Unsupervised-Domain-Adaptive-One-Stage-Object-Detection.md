---
layout: post
title: "Self-Training and Adversarial Background Regularization for Unsupervised Domain Adaptive One-Stage Object Detection"
date: 2019-09-02 08:37:27
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Object_Detection Knowledge Deep_Learning Detection
author: Seunghyeon Kim, Jaehoon Choi, Taekyung Kim, Changick Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning-based object detectors have shown remarkable improvements. However, supervised learning-based methods perform poorly when the train data and the test data have different distributions. To address the issue, domain adaptation transfers knowledge from the label-sufficient domain (source domain) to the label-scarce domain (target domain). Self-training is one of the powerful ways to achieve domain adaptation since it helps class-wise domain adaptation. Unfortunately, a naive approach that utilizes pseudo-labels as ground-truth degenerates the performance due to incorrect pseudo-labels. In this paper, we introduce a weak self-training (WST) method and adversarial background score regularization (BSR) for domain adaptive one-stage object detection. WST diminishes the adverse effects of inaccurate pseudo-labels to stabilize the learning procedure. BSR helps the network extract discriminative features for target backgrounds to reduce the domain shift. Two components are complementary to each other as BSR enhances discrimination between foregrounds and backgrounds, whereas WST strengthen class-wise discrimination. Experimental results show that our approach effectively improves the performance of the one-stage object detection in unsupervised domain adaptation setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00597](http://arxiv.org/abs/1909.00597)

##### PDF
[http://arxiv.org/pdf/1909.00597](http://arxiv.org/pdf/1909.00597)

