---
layout: post
title: "Defending against Adversarial Attacks through Resilient Feature Regeneration"
date: 2019-06-08 12:18:13
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Prediction
author: Tejas Borkar, Felix Heide, Lina Karam
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network (DNN) predictions have been shown to be vulnerable to carefully crafted adversarial perturbations. Specifically, so-called universal adversarial perturbations are image-agnostic perturbations that can be added to any image and can fool a target network into making erroneous predictions. Departing from existing adversarial defense strategies, which work in the image domain, we present a novel defense which operates in the DNN feature domain and effectively defends against such universal adversarial attacks. Our approach identifies pre-trained convolutional features that are most vulnerable to adversarial noise and deploys defender units which transform (regenerate) these DNN filter activations into noise-resilient features, guarding against unseen adversarial perturbations. The proposed defender units are trained using a target loss on synthetic adversarial perturbations, which we generate with a novel efficient synthesis method. We validate the proposed method for different DNN architectures, and demonstrate that it outperforms existing defense strategies across network architectures by more than 10% in restored accuracy. Moreover, we demonstrate that the approach also improves resilience of DNNs to other unseen adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03444](http://arxiv.org/abs/1906.03444)

##### PDF
[http://arxiv.org/pdf/1906.03444](http://arxiv.org/pdf/1906.03444)

