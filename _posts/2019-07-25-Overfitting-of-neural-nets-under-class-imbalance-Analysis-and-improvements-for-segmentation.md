---
layout: post
title: "Overfitting of neural nets under class imbalance: Analysis and improvements for segmentation"
date: 2019-07-25 11:47:12
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Embedding Deep_Learning Relation
author: Zeju Li, Konstantinos Kamnitsas, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
Overfitting in deep learning has been the focus of a number of recent works, yet its exact impact on the behavior of neural networks is not well understood. This study analyzes overfitting by examining how the distribution of logits alters in relation to how much the model overfits. Specifically, we find that when training with few data samples, the distribution of logit activations when processing unseen test samples of an under-represented class tends to shift towards and even across the decision boundary, while the over-represented class seems unaffected. In image segmentation, foreground samples are often heavily under-represented. We observe that sensitivity of the model drops as a result of overfitting, while precision remains mostly stable. Based on our analysis, we derive asymmetric modifications of existing loss functions and regularizers including a large margin loss, focal loss, adversarial training and mixup, which specifically aim at reducing the shift observed when embedding unseen samples of the under-represented class. We study the case of binary segmentation of brain tumor core and show that our proposed simple modifications lead to significantly improved segmentation performance over the symmetric variants.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10982](http://arxiv.org/abs/1907.10982)

##### PDF
[http://arxiv.org/pdf/1907.10982](http://arxiv.org/pdf/1907.10982)

