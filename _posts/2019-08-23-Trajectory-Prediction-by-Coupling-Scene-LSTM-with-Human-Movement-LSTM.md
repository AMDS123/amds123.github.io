---
layout: post
title: "Trajectory Prediction by Coupling Scene-LSTM with Human Movement LSTM"
date: 2019-08-23 17:31:59
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Manh Huynh, Gita Alaghband
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a novel human trajectory prediction system that incorporates the scene information (Scene-LSTM) as well as individual pedestrian movement (Pedestrian-LSTM) trained simultaneously within static crowded scenes. We superimpose a two-level grid structure (grid cells and subgrids) on the scene to encode spatial granularity plus common human movements. The Scene-LSTM captures the commonly traveled paths that can be used to significantly influence the accuracy of human trajectory prediction in local areas (i.e. grid cells). We further design scene data filters, consisting of a hard filter and a soft filter, to select the relevant scene information in a local region when necessary and combine it with Pedestrian-LSTM for forecasting a pedestrian's future locations. The experimental results on several publicly available datasets demonstrate that our method outperforms related works and can produce more accurate predicted trajectories in different scene contexts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08908](http://arxiv.org/abs/1908.08908)

##### PDF
[http://arxiv.org/pdf/1908.08908](http://arxiv.org/pdf/1908.08908)

