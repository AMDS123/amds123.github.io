---
layout: post
title: "Real time Traffic Flow Parameters Prediction with Basic Safety Messages at Low Penetration of Connected Vehicles"
date: 2019-05-21 15:25:34
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Mizanur Rahman, Mashrur Chowdhury, Jerome McClendon
mathjax: true
---

* content
{:toc}

##### Abstract
The expected low market penetration of connected vehicles (CVs) in the near future could be a constraint in estimating traffic flow parameters, such as average travel speed of a roadway segment and average space headway between vehicles from the CV broadcasted data. This estimated traffic flow parameters from low penetration of connected vehicles become noisy compared to 100 percent penetration of CVs, and such noise reduces the real time prediction accuracy of a machine learning model, such as the accuracy of long short term memory (LSTM) model in terms of predicting traffic flow parameters. The accurate prediction of the parameters is important for future traffic condition assessment. To improve the prediction accuracy using noisy traffic flow parameters, which is constrained by limited CV market penetration and limited CV data, we developed a real time traffic data prediction model that combines LSTM with Kalman filter based Rauch Tung Striebel (RTS) noise reduction model. We conducted a case study using the Enhanced Next Generation Simulation (NGSIM) dataset, which contains vehicle trajectory data for every one tenth of a second, to evaluate the performance of this prediction model. Compared to a baseline LSTM model performance, for only 5 percent penetration of CVs, the analyses revealed that combined LSTM and RTS model reduced the mean absolute percentage error (MAPE) from 19 percent to 5 percent for speed prediction and from 27 percent to 9 percent for space-headway prediction. The statistical significance test with a 95 percent confidence interval confirmed no significant difference in predicted average speed and average space headway using this LSTM and RTS combination with only 5 percent CV penetration rate.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.03562](https://arxiv.org/abs/1811.03562)

##### PDF
[https://arxiv.org/pdf/1811.03562](https://arxiv.org/pdf/1811.03562)

