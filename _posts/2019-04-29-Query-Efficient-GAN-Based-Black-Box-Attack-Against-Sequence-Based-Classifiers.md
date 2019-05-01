---
layout: post
title: "Query-Efficient GAN Based Black-Box Attack Against Sequence Based Classifiers"
date: 2019-04-29 23:21:25
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN RNN
author: Ishai Rosenberg, Asaf Shabtai, Yuval Elovici, Lior Rokach
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a generic and query-efficient black-box attack demonstrated against API call based machine learning malware classifiers. We generate adversarial examples combining sequences (API call sequences) and other features (e.g., printable strings) that will be misclassified by the classifier without affecting the malware functionality. Opposed to previous studies, our attack minimizes the number of target recurrent neural network (RNN) classifier queries and only requires access to the predicted label of the attacked model (with or without its confidence score). We evaluate the attack's effectiveness against a variety of classifiers, including RNN variants, deep neural networks, support vector machines, and gradient-boosted decision trees. Our attack success rate is about 98% when the confidence score is known and 88% when only the label is known. We implement four state of the art query-efficient attacks for sequence input and show that our attack requires fewer queries and less knowledge about the attacked model's architecture than other existing query-efficient attacks, making it practical for attacking cloud based models at a minimal cost.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.08778](https://arxiv.org/abs/1804.08778)

##### PDF
[https://arxiv.org/pdf/1804.08778](https://arxiv.org/pdf/1804.08778)

