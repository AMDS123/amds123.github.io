---
layout: post
title: "Query-Efficient GAN Based Black-Box Attack Against Sequence Based Machine and Deep Learning Classifiers"
date: 2018-11-23 09:59:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Deep_Learning
author: Ishai Rosenberg, Asaf Shabtai, Yuval Elovici, Lior Rokach
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present an efficient and generic black-box attack demonstrated against API call based machine learning malware classifiers. We generate adversarial examples combining sequences (API call sequences) and other features (e.g., printable strings) that will be misclassified by the classifier without affecting the malware functionality. Opposed to previous studies, our attack minimizes the number of target classifier queries and only requires access to the predicted label of the attacked model (without the confidence level). We evaluate the attack's effectiveness against a variety of classifiers, including recurrent neural network variants, deep neural networks, support vector machines, and gradient-boosted decision trees. We show that the attack requires fewer queries and less knowledge about the attacked model's architecture than other existing black-box attacks, making it practical for attacking cloud based models at a minimal cost. We also implement a software framework that can be used to recraft any malware binary so it will not be detected by classifiers, without access to the malware source code. Finally, we discuss the robustness of this attack to existing defense mechanisms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.08778](https://arxiv.org/abs/1804.08778)

##### PDF
[https://arxiv.org/pdf/1804.08778](https://arxiv.org/pdf/1804.08778)

