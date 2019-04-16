---
layout: post
title: "Optimizing Long Short-Term Memory Recurrent Neural Networks Using Ant Colony Optimization to Predict Turbine Engine Vibration"
date: 2017-10-10 14:09:22
categories: arXiv_CV
tags: arXiv_CV Face Optimization RNN Prediction
author: AbdElRahman ElSaid, Travis Desell, Fatima El Jamiy, James Higgins, Brandon Wild
mathjax: true
---

* content
{:toc}

##### Abstract
This article expands on research that has been done to develop a recurrent neural network (RNN) capable of predicting aircraft engine vibrations using long short-term memory (LSTM) neurons. LSTM RNNs can provide a more generalizable and robust method for prediction over analytical calculations of engine vibration, as analytical calculations must be solved iteratively based on specific empirical engine parameters, making this approach ungeneralizable across multiple engines. In initial work, multiple LSTM RNN architectures were proposed, evaluated and compared. This research improves the performance of the most effective LSTM network design proposed in the previous work by using a promising neuroevolution method based on ant colony optimization (ACO) to develop and enhance the LSTM cell structure of the network. A parallelized version of the ACO neuroevolution algorithm has been developed and the evolved LSTM RNNs were compared to the previously used fixed topology. The evolved networks were trained on a large database of flight data records obtained from an airline containing flights that suffered from excessive vibration. Results were obtained using MPI (Message Passing Interface) on a high performance computing (HPC) cluster, evolving 1000 different LSTM cell structures using 168 cores over 4 days. The new evolved LSTM cells showed an improvement of 1.35%, reducing prediction error from 5.51% to 4.17% when predicting excessive engine vibrations 10 seconds in the future, while at the same time dramatically reducing the number of weights from 21,170 to 11,810.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.03753](https://arxiv.org/abs/1710.03753)

##### PDF
[https://arxiv.org/pdf/1710.03753](https://arxiv.org/pdf/1710.03753)

