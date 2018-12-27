---
layout: post
title: "Noise Flooding for Detecting Audio Adversarial Examples Against Automatic Speech Recognition"
date: 2018-12-25 08:02:01
categories: arXiv_CL
tags: arXiv_CL Adversarial Speech_Recognition Classification Deep_Learning Recognition
author: Krishan Rajaratnam, Jugal Kalita
mathjax: true
---

* content
{:toc}

##### Abstract
Neural models enjoy widespread use across a variety of tasks and have grown to become crucial components of many industrial systems. Despite their effectiveness and extensive popularity, they are not without their exploitable flaws. Initially applied to computer vision systems, the generation of adversarial examples is a process in which seemingly imperceptible perturbations are made to an image, with the purpose of inducing a deep learning based classifier to misclassify the image. Due to recent trends in speech processing, this has become a noticeable issue in speech recognition models. In late 2017, an attack was shown to be quite effective against the Speech Commands classification model. Limited-vocabulary speech classifiers, such as the Speech Commands model, are used quite frequently in a variety of applications, particularly in managing automated attendants in telephony contexts. As such, adversarial examples produced by this attack could have real-world consequences. While previous work in defending against these adversarial examples has investigated using audio preprocessing to reduce or distort adversarial noise, this work explores the idea of flooding particular frequency bands of an audio signal with random noise in order to detect adversarial examples. This technique of flooding, which does not require retraining or modifying the model, is inspired by work done in computer vision and builds on the idea that speech classifiers are relatively robust to natural noise. A combined defense incorporating 5 different frequency bands for flooding the signal with noise outperformed other existing defenses in the audio space, detecting adversarial examples with 91.8% precision and 93.5% recall.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10061](http://arxiv.org/abs/1812.10061)

##### PDF
[http://arxiv.org/pdf/1812.10061](http://arxiv.org/pdf/1812.10061)

