---
layout: post
title: "Testing Robustness Against Unforeseen Adversaries"
date: 2019-08-21 17:36:48
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Daniel Kang, Yi Sun, Dan Hendrycks, Tom Brown, Jacob Steinhardt
mathjax: true
---

* content
{:toc}

##### Abstract
Considerable work on adversarial defense has studied robustness to a fixed, known family of adversarial distortions, most frequently L_p-bounded distortions. In reality, the specific form of attack will rarely be known and adversaries are free to employ distortions outside of any fixed set. The present work advocates measuring robustness against this much broader range of unforeseen attacks---attacks whose precise form is not known when designing a defense. 
 We propose a methodology for evaluating a defense against a diverse range of distortion types together with a summary metric UAR that measures the Unforeseen Attack Robustness against a distortion. We construct novel JPEG, Fog, Gabor, and Snow adversarial attacks to simulate unforeseen adversaries and perform a careful study of adversarial robustness against these and existing distortion types. We find that evaluation against existing L_p attacks yields highly correlated information that may not generalize to other attacks and identify a set of 4 attacks that yields more diverse information. We further find that adversarial training against either one or multiple distortions, including our novel ones, does not confer robustness to unforeseen distortions. These results underscore the need to study robustness against unforeseen distortions and provide a starting point for doing so.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08016](http://arxiv.org/abs/1908.08016)

##### PDF
[http://arxiv.org/pdf/1908.08016](http://arxiv.org/pdf/1908.08016)

