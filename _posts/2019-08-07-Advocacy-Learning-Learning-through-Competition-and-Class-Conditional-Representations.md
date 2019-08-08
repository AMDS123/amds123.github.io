---
layout: post
title: "Advocacy Learning: Learning through Competition and Class-Conditional Representations"
date: 2019-08-07 16:55:44
categories: arXiv_CV
tags: arXiv_CV Attention Classification
author: Ian Fox, Jenna Wiens
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce advocacy learning, a novel supervised training scheme for attention-based classification problems. Advocacy learning relies on a framework consisting of two connected networks: 1) $N$ Advocates (one for each class), each of which outputs an argument in the form of an attention map over the input, and 2) a Judge, which predicts the class label based on these arguments. Each Advocate produces a class-conditional representation with the goal of convincing the Judge that the input example belongs to their class, even when the input belongs to a different class. Applied to several different classification tasks, we show that advocacy learning can lead to small improvements in classification accuracy over an identical supervised baseline. Though a series of follow-up experiments, we analyze when and how such class-conditional representations improve discriminative performance. Though somewhat counter-intuitive, a framework in which subnetworks are trained to competitively provide evidence in support of their class shows promise, in many cases performing on par with standard learning approaches. This provides a foundation for further exploration into competition and class-conditional representations in supervised learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02723](http://arxiv.org/abs/1908.02723)

##### PDF
[http://arxiv.org/pdf/1908.02723](http://arxiv.org/pdf/1908.02723)

