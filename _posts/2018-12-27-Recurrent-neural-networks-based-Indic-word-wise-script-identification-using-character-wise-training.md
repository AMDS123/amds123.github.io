---
layout: post
title: "Recurrent neural networks based Indic word-wise script identification using character-wise training"
date: 2018-12-27 15:01:36
categories: arXiv_CV
tags: arXiv_CV RNN Prediction Recognition
author: Rohun Tripathi, Aman Gill, Riccha Tripati
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel methodology of Indic handwritten script recognition using Recurrent Neural Networks and addresses the problem of script recognition in poor data scenarios, such as when only character level online data is available. It is based on the hypothesis that curves of online character data comprise sufficient information for prediction at the word level. Online character data is used to train RNNs using BLSTM architecture which are then used to make predictions of online word level data. These prediction results on the test set are at par with prediction results of models trained with online word data, while the training of the character level model is much less data intensive and takes much less time. Performance for binary-script models and then 5 Indic script models are reported, along with comparison with HMM models.The system is extended for offline data prediction. Raw offline data lacks the temporal information available in online data and required for prediction using models trained with online data. To overcome this, stroke recovery is implemented and the strokes are utilized for predicting using the online character level models. The performance on character and word level offline data is reported.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.03209](http://arxiv.org/abs/1709.03209)

##### PDF
[http://arxiv.org/pdf/1709.03209](http://arxiv.org/pdf/1709.03209)

