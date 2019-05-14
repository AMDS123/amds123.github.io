---
layout: post
title: "Similarity Grouping-Guided Neural Network Modeling for Maritime Time Series Prediction"
date: 2019-05-13 06:13:27
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Yan Li, Ryan Wen Liu, Zhao Liu, Jingxian Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Reliable and accurate prediction of time series plays a crucial role in maritime industry, such as economic investment, transportation planning, port planning and design, etc. The dynamic growth of maritime time series has the predominantly complex, nonlinear and non-stationary properties. To guarantee high-quality prediction performance, we propose to first adopt the empirical mode decomposition (EMD) and ensemble EMD (EEMD) methods to decompose the original time series into high- and low-frequency components. The low-frequency components can be easily predicted directly through traditional neural network (NN) methods. It is more difficult to predict high-frequency components due to their properties of weak mathematical regularity. To take advantage of the inherent self-similarities within high-frequency components, these components will be divided into several continuous small (overlapping) segments. The grouped segments with high similarities are then selected to form more proper training datasets for traditional NN methods. This regrouping strategy can assist in enhancing the prediction accuracy of high-frequency components. The final prediction result is obtained by integrating the predicted high- and low-frequency components. Our proposed three-step prediction frameworks benefit from the time series decomposition and similar segments grouping. Experiments on both port cargo throughput and vessel traffic flow have illustrated its superior performance in terms of prediction accuracy and robustness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04872](http://arxiv.org/abs/1905.04872)

##### PDF
[http://arxiv.org/pdf/1905.04872](http://arxiv.org/pdf/1905.04872)

