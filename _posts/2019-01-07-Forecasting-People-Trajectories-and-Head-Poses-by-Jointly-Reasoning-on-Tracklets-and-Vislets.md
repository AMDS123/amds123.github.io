---
layout: post
title: "Forecasting People Trajectories and Head Poses by Jointly Reasoning on Tracklets and Vislets"
date: 2019-01-07 10:15:17
categories: arXiv_CV
tags: arXiv_CV Attention Optimization RNN Prediction Relation
author: Irtiza Hasan, Francesco Setti, Theodore Tsesmelis, Vasileios Belagiannis, Sikandar Amin, Alessio Del Bue, Marco Cristani, Fabio Galasso
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we explore the correlation between people trajectories and their head orientations. We argue that people trajectory and head pose forecasting can be modelled as a joint problem. Recent approaches on trajectory forecasting leverage short-term trajectories (aka tracklets) of pedestrians to predict their future paths. In addition, sociological cues, such as expected destination or pedestrian interaction, are often combined with tracklets. In this paper, we propose MiXing-LSTM (MX-LSTM) to capture the interplay between positions and head orientations (vislets) thanks to a joint unconstrained optimization of full covariance matrices during the LSTM backpropagation. We additionally exploit the head orientations as a proxy for the visual attention, when modeling social interactions. MX-LSTM predicts future pedestrians location and head pose, increasing the standard capabilities of the current approaches on long-term trajectory forecasting. Compared to the state-of-the-art, our approach shows better performances on an extensive set of public benchmarks. MX-LSTM is particularly effective when people move slowly, i.e. the most challenging scenario for all other models. The proposed approach also allows for accurate predictions on a longer time horizon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02000](http://arxiv.org/abs/1901.02000)

##### PDF
[http://arxiv.org/pdf/1901.02000](http://arxiv.org/pdf/1901.02000)

