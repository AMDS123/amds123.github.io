---
layout: post
title: "A Two-Stage Method for Text Line Detection in Historical Documents"
date: 2019-07-11 09:45:21
categories: arXiv_CV
tags: arXiv_CV Prediction Detection
author: Tobias Gr&#xfc;ning, Gundram Leifert, Tobias Strau&#xdf;, Johannes Michael, Roger Labahn
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a two-stage text line detection method for historical documents. Each detected text line is represented by its baseline. In a first stage, a deep neural network called ARU-Net labels pixels to belong to one of the three classes: baseline, separator or other. The separator class marks beginning and end of each text line. The ARU-Net is trainable from scratch with manageably few manually annotated example images (less than 50). This is achieved by utilizing data augmentation strategies. The network predictions are used as input for the second stage which performs a bottom-up clustering to build baselines. The developed method is capable of handling complex layouts as well as curved and arbitrarily oriented text lines. It substantially outperforms current state-of-the-art approaches. For example, for the complex track of the cBAD: ICDAR2017 Competition on Baseline Detection the F-value is increased from 0.859 to 0.922. The framework to train and run the ARU-Net is open source.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.03345](http://arxiv.org/abs/1802.03345)

##### PDF
[http://arxiv.org/pdf/1802.03345](http://arxiv.org/pdf/1802.03345)

