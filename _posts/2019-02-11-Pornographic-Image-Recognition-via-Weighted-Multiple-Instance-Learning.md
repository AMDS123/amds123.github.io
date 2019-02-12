---
layout: post
title: "Pornographic Image Recognition via Weighted Multiple Instance Learning"
date: 2019-02-11 08:24:53
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative Recognition
author: Jin Xin, Wang Yuhui, Tan Xiaoyang
mathjax: true
---

* content
{:toc}

##### Abstract
In the era of Internet, recognizing pornographic images is of great significance for protecting children's physical and mental health. However, this task is very challenging as the key pornographic contents (e.g., breast and private part) in an image often lie in local regions of small size. In this paper, we model each image as a bag of regions, and follow a multiple instance learning (MIL) approach to train a generic region-based recognition model. Specifically, we take into account the region's degree of pornography, and make three main contributions. First, we show that based on very few annotations of the key pornographic contents in a training image, we can generate a bag of properly sized regions, among which the potential positive regions usually contain useful contexts that can aid recognition. Second, we present a simple quantitative measure of a region's degree of pornography, which can be used to weigh the importance of different regions in a positive image. Third, we formulate the recognition task as a weighted MIL problem under the convolutional neural network framework, with a bag probability function introduced to combine the importance of different regions. Experiments on our newly collected large scale dataset demonstrate the effectiveness of the proposed method, achieving an accuracy with 97.52% true positive rate at 1% false positive rate, tested on 100K pornographic images and 100K normal images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03771](http://arxiv.org/abs/1902.03771)

##### PDF
[http://arxiv.org/pdf/1902.03771](http://arxiv.org/pdf/1902.03771)

