---
layout: post
title: "Optimizing Taxi Carpool Policies via Reinforcement Learning and Spatio-Temporal Mining"
date: 2018-11-11 04:13:31
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Ishan Jindal, Zhiwei Qin, Xuewen Chen, Matthew Nokleby, Jieping Ye
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a reinforcement learning (RL) based system to learn an effective policy for carpooling that maximizes transportation efficiency so that fewer cars are required to fulfill the given amount of trip demand. For this purpose, first, we develop a deep neural network model, called ST-NN (Spatio-Temporal Neural Network), to predict taxi trip time from the raw GPS trip data. Secondly, we develop a carpooling simulation environment for RL training, with the output of ST-NN and using the NYC taxi trip dataset. In order to maximize transportation efficiency and minimize traffic congestion, we choose the effective distance covered by the driver on a carpool trip as the reward. Therefore, the more effective distance a driver achieves over a trip (i.e. to satisfy more trip demand) the higher the efficiency and the less will be the traffic congestion. We compared the performance of RL learned policy to a fixed policy (which always accepts carpool) as a baseline and obtained promising results that are interpretable and demonstrate the advantage of our RL approach. We also compare the performance of ST-NN to that of state-of-the-art travel time estimation methods and observe that ST-NN significantly improves the prediction performance and is more robust to outliers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04345](http://arxiv.org/abs/1811.04345)

##### PDF
[http://arxiv.org/pdf/1811.04345](http://arxiv.org/pdf/1811.04345)

