---
layout: post
title: "MX-LSTM: mixing tracklets and vislets to jointly forecast trajectories and head poses"
date: 2018-05-02 07:21:45
categories: arXiv_CV
tags: arXiv_CV Attention Pose_Estimation Optimization RNN
author: Irtiza Hasan, Francesco Setti, Theodore Tsesmelis, Alessio Del Bue, Fabio Galasso, Marco Cristani
mathjax: true
---

* content
{:toc}

##### Abstract
Recent approaches on trajectory forecasting use tracklets to predict the future positions of pedestrians exploiting Long Short Term Memory (LSTM) architectures. This paper shows that adding vislets, that is, short sequences of head pose estimations, allows to increase significantly the trajectory forecasting performance. We then propose to use vislets in a novel framework called MX-LSTM, capturing the interplay between tracklets and vislets thanks to a joint unconstrained optimization of full covariance matrices during the LSTM backpropagation. At the same time, MX-LSTM predicts the future head poses, increasing the standard capabilities of the long-term trajectory forecasting approaches. With standard head pose estimators and an attentional-based social pooling, MX-LSTM scores the new trajectory forecasting state-of-the-art in all the considered datasets (Zara01, Zara02, UCY, and TownCentre) with a dramatic margin when the pedestrians slow down, a case where most of the forecasting approaches struggle to provide an accurate solution.

##### Abstract (translated by Google)
最近的轨迹预测方法使用轨迹预测利用长期短期记忆（LSTM）体系结构的行人的未来位置。本文表明，添加小孔，即头部姿势估计的短序列，可以显着提高轨迹预测性能。然后，我们建议在一个名为MX-LSTM的新框架中使用vislets，由于LSTM反向传播期间完全协方差矩阵的联合无约束优化，捕获了tracklets和vislets之间的相互作用。同时，MX-LSTM可以预测未来的头部姿势，提高长期轨迹预测方法的标准能力。使用标准的头部姿势估计器和基于注意力的社交池，MX-LSTM在所有考虑的数据集（Zara01，Zara02，UCY和TownCentre）中评分为新的轨迹预测最新技术，当行人放慢速度，这是大多数预测方法难以提供准确解决方案的情况。

##### URL
[https://arxiv.org/abs/1805.00652](https://arxiv.org/abs/1805.00652)

##### PDF
[https://arxiv.org/pdf/1805.00652](https://arxiv.org/pdf/1805.00652)

