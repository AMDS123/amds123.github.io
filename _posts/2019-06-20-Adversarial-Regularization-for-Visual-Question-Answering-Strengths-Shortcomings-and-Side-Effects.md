---
layout: post
title: "Adversarial Regularization for Visual Question Answering: Strengths, Shortcomings, and Side Effects"
date: 2019-06-20 03:28:09
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial QA Inference VQA
author: Gabriel Grand, Yonatan Belinkov
mathjax: true
---

* content
{:toc}

##### Abstract
Visual question answering (VQA) models have been shown to over-rely on linguistic biases in VQA datasets, answering questions "blindly" without considering visual context. Adversarial regularization (AdvReg) aims to address this issue via an adversary sub-network that encourages the main model to learn a bias-free representation of the question. In this work, we investigate the strengths and shortcomings of AdvReg with the goal of better understanding how it affects inference in VQA models. Despite achieving a new state-of-the-art on VQA-CP, we find that AdvReg yields several undesirable side-effects, including unstable gradients and sharply reduced performance on in-domain examples. We demonstrate that gradual introduction of regularization during training helps to alleviate, but not completely solve, these issues. Through error analyses, we observe that AdvReg improves generalization to binary questions, but impairs performance on questions with heterogeneous answer distributions. Qualitatively, we also find that regularized models tend to over-rely on visual features, while ignoring important linguistic cues in the question. Our results suggest that AdvReg requires further refinement before it can be considered a viable bias mitigation technique for VQA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08430](http://arxiv.org/abs/1906.08430)

##### PDF
[http://arxiv.org/pdf/1906.08430](http://arxiv.org/pdf/1906.08430)

