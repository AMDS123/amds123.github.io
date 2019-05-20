---
layout: post
title: "Predicting Solar Flares Using a Long Short-Term Memory Network"
date: 2019-05-17 02:57:13
categories: arXiv_CV
tags: arXiv_CV Knowledge Survey RNN Prediction
author: Hao Liu, Chang Liu, Jason T. L. Wang, Haimin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a long short-term memory (LSTM) network for predicting whether an active region (AR) would produce a gamma-class flare within the next 24 hours. We consider three gamma classes, namely >=M5.0 class, >=M class, and >=C class, and build three LSTM models separately, each corresponding to a gamma class. Each LSTM model is used to make predictions of its corresponding gamma-class flares. The essence of our approach is to model data samples in an AR as time series and use LSTMs to capture temporal information of the data samples. Each data sample has 40 features including 25 magnetic parameters obtained from the Space-weather HMI Active Region Patches (SHARP) and related data products as well as 15 flare history parameters. We survey the flare events that occurred from 2010 May to 2018 May, using the GOES X-ray flare catalogs provided by the National Centers for Environmental Information (NCEI), and select flares with identified ARs in the NCEI flare catalogs. These flare events are used to build the labels (positive vs. negative) of the data samples. Experimental results show that (i) using only 14-22 most important features including both flare history and magnetic parameters can achieve better performance than using all the 40 features together; (ii) our LSTM network outperforms related machine learning methods in predicting the labels of the data samples. To our knowledge, this is the first time that LSTMs have been used for solar flare prediction.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.07095](https://arxiv.org/abs/1905.07095)

##### PDF
[https://arxiv.org/pdf/1905.07095](https://arxiv.org/pdf/1905.07095)

