---
layout: post
title: "Stochastic Substitute Training: A Gray-box Approach to Craft Adversarial Examples Against Gradient Obfuscation Defenses"
date: 2018-10-23 18:14:47
categories: arXiv_AI
tags: arXiv_AI Adversarial Object_Detection Knowledge Detection
author: Mohammad Hashemi, Greg Cusack, Eric Keller
mathjax: true
---

* content
{:toc}

##### Abstract
It has been shown that adversaries can craft example inputs to neural networks which are similar to legitimate inputs but have been created to purposely cause the neural network to misclassify the input. These adversarial examples are crafted, for example, by calculating gradients of a carefully defined loss function with respect to the input. As a countermeasure, some researchers have tried to design robust models by blocking or obfuscating gradients, even in white-box settings. Another line of research proposes introducing a separate detector to attempt to detect adversarial examples. This approach also makes use of gradient obfuscation techniques, for example, to prevent the adversary from trying to fool the detector. In this paper, we introduce stochastic substitute training, a gray-box approach that can craft adversarial examples for defenses which obfuscate gradients. For those defenses that have tried to make models more robust, with our technique, an adversary can craft adversarial examples with no knowledge of the defense. For defenses that attempt to detect the adversarial examples, with our technique, an adversary only needs very limited information about the defense to craft adversarial examples. We demonstrate our technique by applying it against two defenses which make models more robust and two defenses which detect adversarial examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10031](http://arxiv.org/abs/1810.10031)

##### PDF
[http://arxiv.org/pdf/1810.10031](http://arxiv.org/pdf/1810.10031)

