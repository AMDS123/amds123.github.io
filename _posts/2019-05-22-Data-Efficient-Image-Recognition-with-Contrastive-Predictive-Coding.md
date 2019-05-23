---
layout: post
title: "Data-Efficient Image Recognition with Contrastive Predictive Coding"
date: 2019-05-22 17:57:49
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Detection Recognition
author: Olivier J. H&#xe9;naff, Ali Razavi, Carl Doersch, S. M. Ali Eslami, Aaron van den Oord
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale deep learning excels when labeled images are abundant, yet data-efficient learning remains a longstanding challenge. While biological vision is thought to leverage vast amounts of unlabeled data to solve classification problems with limited supervision, computer vision has so far not succeeded in this `semi-supervised' regime. Our work tackles this challenge with Contrastive Predictive Coding, an unsupervised objective which extracts stable structure from still images. The result is a representation which, equipped with a simple linear classifier, separates ImageNet categories better than all competing methods, and surpasses the performance of a fully-supervised AlexNet model. When given a small number of labeled images (as few as 13 per class), this representation retains a strong classification performance, outperforming state-of-the-art semi-supervised methods by 10% Top-5 accuracy and supervised methods by 20%. Finally, we find our unsupervised representation to serve as a useful substrate for image detection on the PASCAL-VOC 2007 dataset, approaching the performance of representations trained with a fully annotated ImageNet dataset. We expect these results to open the door to pipelines that use scalable unsupervised representations as a drop-in replacement for supervised ones for real-world vision tasks where labels are scarce.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09272](http://arxiv.org/abs/1905.09272)

##### PDF
[http://arxiv.org/pdf/1905.09272](http://arxiv.org/pdf/1905.09272)

