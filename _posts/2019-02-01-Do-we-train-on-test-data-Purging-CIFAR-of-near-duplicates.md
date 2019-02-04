---
layout: post
title: "Do we train on test data? Purging CIFAR of near-duplicates"
date: 2019-02-01 16:00:34
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Bj&#xf6;rn Barz, Joachim Denzler
mathjax: true
---

* content
{:toc}

##### Abstract
We find that 3.3% and 10% of the images from the CIFAR-10 and CIFAR-100 test sets, respectively, have duplicates in the training set. This may incur a bias on the comparison of image recognition techniques with respect to their generalization capability on these heavily benchmarked datasets. To eliminate this bias, we provide the "fair CIFAR" (ciFAIR) dataset, where we replaced all duplicates in the test sets with new images sampled from the same domain. The training set remains unchanged, in order not to invalidate pre-trained models. We then re-evaluate the classification performance of various popular state-of-the-art CNN architectures on these new test sets to investigate whether recent research has overfitted to memorizing data instead of learning abstract concepts. Fortunately, this does not seem to be the case yet. The ciFAIR dataset and pre-trained models are available at https://cvjena.github.io/cifair/, where we also maintain a leaderboard.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00423](http://arxiv.org/abs/1902.00423)

##### PDF
[http://arxiv.org/pdf/1902.00423](http://arxiv.org/pdf/1902.00423)

