---
layout: post
title: "Dynamic Demand Prediction for Expanding Electric Vehicle Sharing Systems: A Graph Sequence Learning Approach"
date: 2019-03-10 20:03:43
categories: arXiv_AI
tags: arXiv_AI CNN Prediction Relation
author: Man Luo, Hongkai Wen, Yi Luo, Bowen Du, Konstantin Klemmer, Hongming Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Electric Vehicle (EV) sharing systems have recently experienced unprecedented growth across the globe. During their fast expansion, one fundamental determinant for success is the capability of dynamically predicting the demand of stations as the entire system is evolving continuously. There are several challenges in this dynamic demand prediction problem. Firstly, unlike most of the existing work which predicts demand only for static systems or at few stages of expansion, in the real world we often need to predict the demand as or even before stations are being deployed or closed, to provide information and support for decision making. Secondly, for the stations to be deployed, there is no historical record or additional mobility data available to help the prediction of their demand. Finally, the impact of deploying/closing stations to the remaining stations in the system can be very complex. To address these challenges, in this paper we propose a novel dynamic demand prediction approach based on graph sequence learning, which is able to model the dynamics during the system expansion and predict demand accordingly. We use a local temporal encoding process to handle the available historical data at individual stations, and a dynamic spatial encoding process to take correlations between stations into account with graph convolutional neural networks. The encoded features are fed to a multi-scale prediction network, which forecasts both the long-term expected demand of the stations and their instant demand in the near future. We evaluate the proposed approach on real-world data collected from a major EV sharing platform in Shanghai for one year. Experimental results demonstrate that our approach significantly outperforms the state of the art, showing up to three-fold performance gain in predicting demand for the rapidly expanding EV sharing system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04051](http://arxiv.org/abs/1903.04051)

##### PDF
[http://arxiv.org/pdf/1903.04051](http://arxiv.org/pdf/1903.04051)

