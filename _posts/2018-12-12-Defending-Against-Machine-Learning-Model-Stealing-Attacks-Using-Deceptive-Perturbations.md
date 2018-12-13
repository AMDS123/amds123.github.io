---
layout: post
title: "Defending Against Machine Learning Model Stealing Attacks Using Deceptive Perturbations"
date: 2018-12-12 17:13:47
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Taesung Lee, Benjamin Edwards, Ian Molloy, Dong Su
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models are vulnerable to simple model stealing attacks if the adversary can obtain output labels for chosen inputs. To protect against these attacks, it has been proposed to limit the information provided to the adversary by omitting probability scores, significantly impacting the utility of the provided service. In this work, we illustrate how a service provider can still provide useful, albeit misleading, class probability information, while significantly limiting the success of the attack. Our defense forces the adversary to discard the class probabilities, requiring significantly more queries before they can train a model with comparable performance. We evaluate several attack strategies, model architectures, and hyperparameters under varying adversarial models, and evaluate the efficacy of our defense against the strongest adversary. Finally, we quantify the amount of noise injected into the class probabilities to mesure the loss in utility, e.g., adding 1.26 nats per query on CIFAR-10 and 3.27 on MNIST. Our evaluation shows our defense can degrade the accuracy of the stolen model at least 20%, or require up to 64 times more queries while keeping the accuracy of the protected model almost intact.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.00054](http://arxiv.org/abs/1806.00054)

##### PDF
[http://arxiv.org/pdf/1806.00054](http://arxiv.org/pdf/1806.00054)

