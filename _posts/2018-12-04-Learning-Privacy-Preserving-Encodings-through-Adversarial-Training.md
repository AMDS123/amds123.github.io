---
layout: post
title: "Learning Privacy Preserving Encodings through Adversarial Training"
date: 2018-12-04 19:24:57
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Optimization Inference Detection
author: Francesco Pittaluga, Sanjeev J. Koppal, Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework to learn privacy-preserving encodings of images that inhibit inference of chosen private attributes, while allowing recovery of other desirable information. Rather than simply inhibiting a given fixed pre-trained estimator, our goal is that an estimator be unable to learn to accurately predict the private attributes even with knowledge of the encoding function. We use a natural adversarial optimization-based formulation for this---training the encoding function against a classifier for the private attribute, with both modeled as deep neural networks. The key contribution of our work is a stable and convergent optimization approach that is successful at learning an encoder with our desired properties---maintaining utility while inhibiting inference of private attributes, not just within the adversarial optimization, but also by classifiers that are trained after the encoder is fixed. We adopt a rigorous experimental protocol for verification wherein classifiers are trained exhaustively till saturation on the fixed encoders. We evaluate our approach on tasks of real-world complexity---learning high-dimensional encodings that inhibit detection of different scene categories---and find that it yields encoders that are resilient at maintaining privacy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.05214](http://arxiv.org/abs/1802.05214)

##### PDF
[http://arxiv.org/pdf/1802.05214](http://arxiv.org/pdf/1802.05214)

