---
layout: post
title: "Combating Adversarial Misspellings with Robust Word Recognition"
date: 2019-05-27 14:35:35
categories: arXiv_CL
tags: arXiv_CL Sentiment Adversarial RNN Recognition
author: Danish Pruthi, Bhuwan Dhingra, Zachary C. Lipton
mathjax: true
---

* content
{:toc}

##### Abstract
To combat adversarial spelling mistakes, we propose placing a word recognition model in front of the downstream classifier. Our word recognition models build upon the RNN semi-character architecture, introducing several new backoff strategies for handling rare and unseen words. Trained to recognize words corrupted by random adds, drops, swaps, and keyboard mistakes, our method achieves 32% relative (and 3.3% absolute) error reduction over the vanilla semi-character model. Notably, our pipeline confers robustness on the downstream classifier, outperforming both adversarial training and off-the-shelf spell checkers. Against a BERT model fine-tuned for sentiment analysis, a single adversarially-chosen character attack lowers accuracy from 90.3% to 45.8%. Our defense restores accuracy to 75%. Surprisingly, better word recognition does not always entail greater robustness. Our analysis reveals that robustness also depends upon a quantity that we denote the sensitivity.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11268](https://arxiv.org/abs/1905.11268)

##### PDF
[https://arxiv.org/pdf/1905.11268](https://arxiv.org/pdf/1905.11268)

