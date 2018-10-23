---
layout: post
title: "Improving the Generalization of Adversarial Training with Domain Adaptation"
date: 2018-10-20 09:00:02
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning
author: Chuanbiao Song, Kun He, Liwei Wang, John E. Hopcroft
mathjax: true
---

* content
{:toc}

##### Abstract
By injecting adversarial examples into training data, the adversarial training method is promising for improving the robustness of deep learning models. However, most existing adversarial training approaches are based on a specific type of adversarial attack. It may not provide sufficiently representative samples from the adversarial domain, leading to a weak generalization ability on adversarial examples from other attacks. To scale to large datasets, perturbations on inputs to generate adversarial examples are usually crafted using fast single-step attacks. This work is mainly focused on the adversarial training with the single-step yet efficient FGSM adversary. In this scenario, it is difficult to train a model with great generalization due to the lack of representative adversarial samples, aka the samples are unable to accurately reflect the adversarial domain. To address this problem, we propose a novel Adversarial Training with Domain Adaptation (ATDA) method by regarding the adversarial training with FGSM adversary as a domain adaption task with limited number of target domain samples. The main idea is to learn a representation that is semantically meaningful and domain invariant on the clean domain as well as the adversarial domain. Empirical evaluations demonstrate that ATDA can greatly improve the generalization of adversarial training and achieves state-of-the-art results on standard benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00740](http://arxiv.org/abs/1810.00740)

##### PDF
[http://arxiv.org/pdf/1810.00740](http://arxiv.org/pdf/1810.00740)

