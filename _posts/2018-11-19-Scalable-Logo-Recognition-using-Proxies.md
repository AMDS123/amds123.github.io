---
layout: post
title: "Scalable Logo Recognition using Proxies"
date: 2018-11-19 22:28:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Recognition
author: Istvan Fehervari, Srikar Appalaraju
mathjax: true
---

* content
{:toc}

##### Abstract
Logo recognition is the task of identifying and classifying logos. Logo recognition is a challenging problem as there is no clear definition of a logo and there are huge variations of logos, brands and re-training to cover every variation is impractical. In this paper, we formulate logo recognition as a few-shot object detection problem. The two main components in our pipeline are universal logo detector and few-shot logo recognizer. The universal logo detector is a class-agnostic deep object detector network which tries to learn the characteristics of what makes a logo. It predicts bounding boxes on likely logo regions. These logo regions are then classified by logo recognizer using nearest neighbor search, trained by triplet loss using proxies. We also annotated a first of its kind product logo dataset containing 2000 logos from 295K images collected from Amazon called PL2K. Our pipeline achieves 97% recall with 0.6 mAP on PL2K test dataset and state-of-the-art 0.565 mAP on the publicly available FlickrLogos-32 test set without fine-tuning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08009](http://arxiv.org/abs/1811.08009)

##### PDF
[http://arxiv.org/pdf/1811.08009](http://arxiv.org/pdf/1811.08009)

