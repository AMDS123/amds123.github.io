---
layout: post
title: "Generalizing Fingerprint Spoof Detector: Learning a One-Class Classifier"
date: 2019-01-13 00:29:06
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Classification Detection Recognition
author: Joshua J. Engelsma, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
Prevailing fingerprint recognition systems are vulnerable to spoof attacks. To mitigate these attacks, automated spoof detectors are trained to distinguish a set of live or bona fide fingerprints from a set of known spoof fingerprints. However, spoof detectors remain vulnerable when exposed to attacks from spoofs made with materials not seen during training of the detector. To alleviate this shortcoming, we approach spoof detection as a one-class classification problem. The goal is to train a spoof detector on only the live fingerprints such that once the concept of "live" has been learned, spoofs of any material can be rejected. We accomplish this through training multiple generative adversarial networks (GANS) on live fingerprint images acquired with the open source, dual-camera, 1900 ppi RaspiReader fingerprint reader. Our experimental results, conducted on 5.5K spoof images (from 12 materials) and 11.8K live images show that the proposed approach improves the cross-material spoof detection performance over state-of-the-art one-class and binary class spoof detectors TDR = 84.4% vs. TDR = 40.3% (both @ FDR = 0.2%).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03918](http://arxiv.org/abs/1901.03918)

##### PDF
[http://arxiv.org/pdf/1901.03918](http://arxiv.org/pdf/1901.03918)

