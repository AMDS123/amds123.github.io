---
layout: post
title: "Danish Stance Classification and Rumour Resolution"
date: 2019-07-02 11:44:31
categories: arXiv_CL
tags: arXiv_CL RNN Classification Prediction
author: Anders Edelbo Lillie, Emil Refsgaard Middelboe
mathjax: true
---

* content
{:toc}

##### Abstract
The Internet is rife with flourishing rumours that spread through microblogs and social media. Recent work has shown that analysing the stance of the crowd towards a rumour is a good indicator for its veracity. One state-of-the-art system uses an LSTM neural network to automatically classify stance for posts on Twitter by considering the context of a whole branch, while another, more simple Decision Tree classifier, performs at least as well by performing careful feature engineering. One approach to predict the veracity of a rumour is to use stance as the only feature for a Hidden Markov Model (HMM). This thesis generates a stance-annotated Reddit dataset for the Danish language, and implements various models for stance classification. Out of these, a Linear Support Vector Machine provides the best results with an accuracy of 0.76 and macro F1 score of 0.42. Furthermore, experiments show that stance labels can be used across languages and platforms with a HMM to predict the veracity of rumours, achieving an accuracy of 0.82 and F1 score of 0.67. Even higher scores are achieved by relying only on the Danish dataset. In this case veracity prediction scores an accuracy of 0.83 and an F1 of 0.68. Finally, when using automatic stance labels for the HMM, only a small drop in performance is observed, showing that the implemented system can have practical applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01304](http://arxiv.org/abs/1907.01304)

##### PDF
[http://arxiv.org/pdf/1907.01304](http://arxiv.org/pdf/1907.01304)

