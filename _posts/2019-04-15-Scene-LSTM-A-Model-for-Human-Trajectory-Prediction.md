---
layout: post
title: "Scene-LSTM: A Model for Human Trajectory Prediction"
date: 2019-04-15 16:10:52
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Huynh Manh, Gita Alaghband
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a human movement trajectory prediction system that incorporates the scene information (Scene-LSTM) as well as human movement trajectories (Pedestrian movement LSTM) in the prediction process within static crowded scenes. We superimpose a two-level grid structure (scene is divided into grid cells each modeled by a scene-LSTM, which are further divided into smaller sub-grids for finer spatial granularity) and explore common human trajectories occurring in the grid cell (e.g., making a right or left turn onto sidewalks coming out of an alley; or standing still at bus/train stops). Two coupled LSTM networks, Pedestrian movement LSTMs (one per target) and the corresponding Scene-LSTMs (one per grid-cell) are trained simultaneously to predict the next movements. We show that such common path information greatly influences prediction of future movement. We further design a scene data filter that holds important non-linear movement information. The scene data filter allows us to select the relevant parts of the information from the grid cell's memory relative to a target's state. We evaluate and compare two versions of our method with the Linear and several existing LSTM-based methods on five crowded video sequences from the UCY [1] and ETH [2] datasets. The results show that our method reduces the location displacement errors compared to related methods and specifically about 80% reduction compared to social interaction methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.04018](http://arxiv.org/abs/1808.04018)

##### PDF
[http://arxiv.org/pdf/1808.04018](http://arxiv.org/pdf/1808.04018)

