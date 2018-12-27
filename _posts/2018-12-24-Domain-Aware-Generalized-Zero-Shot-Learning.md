---
layout: post
title: "Domain-Aware Generalized Zero-Shot Learning"
date: 2018-12-24 11:54:41
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Yuval Atzmon, Gal Chechik
mathjax: true
---

* content
{:toc}

##### Abstract
Generalized zero-shot learning (GZSL) is the problem of learning a classifier where some classes have samples, and others are learned from side information, like semantic attributes or text description, in a zero-shot learning fashion (ZSL). A major challenge in GZSL is to learn consistently for those two different domains. Here we describe a probabilistic approach that breaks the model into three modular components, and then combines them in a consistent way. Specifically, our model consists of three classifiers: A "gating" model that softly decides if a sample is from a "seen" class and two experts: a ZSL expert, and an expert model for seen classes. We address two main difficulties in this approach: How to provide an accurate estimate of the gating probability without any training samples for unseen classes; and how to use an expert predictions when it observes samples outside of its domain. 
 The key insight in our approach is to pass information between the three models to improve each others accuracy, while keeping the modular structure. We test our approach, Domain-Aware GZSL (DAZL) on three standard GZSL benchmark datasets (AWA, CUB, SUN), and find that it largely outperforms state-of-the-art GZSL models. DAZL is also the first model that closes the gap and surpasses the performance of generative models for GZSL, even-though it is a light-weight model that is much easier to train and tune.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09903](http://arxiv.org/abs/1812.09903)

##### PDF
[http://arxiv.org/pdf/1812.09903](http://arxiv.org/pdf/1812.09903)

