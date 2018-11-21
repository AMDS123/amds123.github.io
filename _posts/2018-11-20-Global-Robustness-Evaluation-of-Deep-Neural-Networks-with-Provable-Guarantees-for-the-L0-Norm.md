---
layout: post
title: "Global Robustness Evaluation of Deep Neural Networks with Provable Guarantees for the $L_0$ Norm"
date: 2018-11-20 16:57:22
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Wenjie Ruan, Min Wu, Youcheng Sun, Xiaowei Huang, Daniel Kroening, Marta Kwiatkowska
mathjax: true
---

* content
{:toc}

##### Abstract
Deployment of deep neural networks (DNNs) in safety- or security-critical systems requires provable guarantees on their correct behaviour. A common requirement is robustness to adversarial perturbations in a neighbourhood around an input. In this paper we focus on the $L_0$ norm and aim to compute, for a trained DNN and an input, the maximal radius of a safe norm ball around the input within which there are no adversarial examples. Then we define global robustness as an expectation of the maximal safe radius over a test data set. We first show that the problem is NP-hard, and then propose an approximate approach to iteratively compute lower and upper bounds on the network's robustness. The approach is \emph{anytime}, i.e., it returns intermediate bounds and robustness estimates that are gradually, but strictly, improved as the computation proceeds; \emph{tensor-based}, i.e., the computation is conducted over a set of inputs simultaneously, instead of one by one, to enable efficient GPU computation; and has \emph{provable guarantees}, i.e., both the bounds and the robustness estimates can converge to their optimal values. Finally, we demonstrate the utility of the proposed approach in practice to compute tight bounds by applying and adapting the anytime algorithm to a set of challenging problems, including global robustness evaluation, competitive $L_0$ attacks, test case generation for DNNs, and local robustness evaluation on large-scale ImageNet DNNs. We release the code of all case studies via GitHub.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.05805](http://arxiv.org/abs/1804.05805)

##### PDF
[http://arxiv.org/pdf/1804.05805](http://arxiv.org/pdf/1804.05805)

