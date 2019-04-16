---
layout: post
title: "Active Learning for Visual Question Answering: An Empirical Study"
date: 2017-11-06 05:28:38
categories: arXiv_CV
tags: arXiv_CV QA VQA
author: Xiao Lin, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
We present an empirical study of active learning for Visual Question Answering, where a deep VQA model selects informative question-image pairs from a pool and queries an oracle for answers to maximally improve its performance under a limited query budget. Drawing analogies from human learning, we explore cramming (entropy), curiosity-driven (expected model change), and goal-driven (expected error reduction) active learning approaches, and propose a fast and effective goal-driven active learning scoring function to pick question-image pairs for deep VQA models under the Bayesian Neural Network framework. We find that deep VQA models need large amounts of training data before they can start asking informative questions. But once they do, all three approaches outperform the random selection baseline and achieve significant query savings. For the scenario where the model is allowed to ask generic questions about images but is evaluated only on specific questions (e.g., questions whose answer is either yes or no), our proposed goal-driven scoring function performs the best.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.01732](https://arxiv.org/abs/1711.01732)

##### PDF
[https://arxiv.org/pdf/1711.01732](https://arxiv.org/pdf/1711.01732)

