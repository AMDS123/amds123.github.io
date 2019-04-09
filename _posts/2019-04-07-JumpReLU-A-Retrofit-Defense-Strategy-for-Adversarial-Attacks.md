---
layout: post
title: "JumpReLU: A Retrofit Defense Strategy for Adversarial Attacks"
date: 2019-04-07 21:47:45
categories: arXiv_CV
tags: arXiv_CV Adversarial Prediction
author: N. Benjamin Erichson, Zhewei Yao, Michael W. Mahoney
mathjax: true
---

* content
{:toc}

##### Abstract
It has been demonstrated that very simple attacks can fool highly-sophisticated neural network architectures. In particular, so-called adversarial examples, constructed from perturbations of input data that are small or imperceptible to humans but lead to different predictions, may lead to an enormous risk in certain critical applications. In light of this, there has been a great deal of work on developing adversarial training strategies to improve model robustness. These training strategies are very expensive, in both human and computational time. To complement these approaches, we propose a very simple and inexpensive strategy which can be used to ``retrofit'' a previously-trained network to improve its resilience to adversarial attacks. More concretely, we propose a new activation function---the JumpReLU---which, when used in place of a ReLU in an already-trained model, leads to a trade-off between predictive accuracy and robustness. This trade-off is controlled by the jump size, a hyper-parameter which can be tuned during the validation stage. Our empirical results demonstrate that this increases model robustness, protecting against adversarial attacks with substantially increased levels of perturbations. This is accomplished simply by retrofitting existing networks with our JumpReLU activation function, without the need for retraining the model. Additionally, we demonstrate that adversarially trained (robust) models can greatly benefit from retrofitting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03750](http://arxiv.org/abs/1904.03750)

##### PDF
[http://arxiv.org/pdf/1904.03750](http://arxiv.org/pdf/1904.03750)

