---
layout: post
title: "A Convex Relaxation Barrier to Tight Robust Verification of Neural Networks"
date: 2019-02-23 03:01:51
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge
author: Hadi Salman, Greg Yang, Huan Zhang, Cho-Jui Hsieh, Pengchuan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Verification of neural networks enables us to gauge their robustness against adversarial attacks. Verification algorithms fall into two categories: exact verifiers that run in exponential time and relaxed verifiers that are efficient but incomplete. In this paper, we unify all existing LP-relaxed verifiers, to the best of our knowledge, under a general convex relaxation framework. This framework works for neural networks with diverse architectures and nonlinearities and covers both primal and dual views of robust verification. We further prove strong duality between the primal and dual problems under very mild conditions. Next, we perform large-scale experiments, amounting to more than 22 CPU-years, to obtain exact solution to the convex-relaxed problem that is optimal within our framework for ReLU networks. We find the exact solution does not significantly improve upon the gap between PGD and existing relaxed verifiers for various networks trained normally or robustly on MNIST and CIFAR datasets. Our results suggest there is an inherent barrier to tight verification for the large class of methods captured by our framework. We discuss possible causes of this barrier and potential future directions for bypassing it.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08722](http://arxiv.org/abs/1902.08722)

##### PDF
[http://arxiv.org/pdf/1902.08722](http://arxiv.org/pdf/1902.08722)

