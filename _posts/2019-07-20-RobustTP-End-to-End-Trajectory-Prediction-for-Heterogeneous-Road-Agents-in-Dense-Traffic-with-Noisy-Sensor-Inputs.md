---
layout: post
title: "RobustTP: End-to-End Trajectory Prediction for Heterogeneous Road-Agents in Dense Traffic with Noisy Sensor Inputs"
date: 2019-07-20 04:21:22
categories: arXiv_RO
tags: arXiv_RO Segmentation Tracking RNN Deep_Learning Prediction
author: Rohan Chandra, Uttaran Bhattacharya, Christian Roncal, Aniket Bera, Dinesh Manocha
mathjax: true
---

* content
{:toc}

##### Abstract
We present RobustTP, an end-to-end algorithm for predicting future trajectories of road-agents in dense traffic with noisy sensor input trajectories obtained from RGB cameras (either static or moving) through a tracking algorithm. In this case, we consider noise as the deviation from the ground truth trajectory. The amount of noise depends on the accuracy of the tracking algorithm. Our approach is designed for dense heterogeneous traffic, where the road agents corresponding to a mixture of buses, cars, scooters, bicycles, or pedestrians. RobustTP is an approach that first computes trajectories using a combination of a non-linear motion model and a deep learning-based instance segmentation algorithm. Next, these noisy trajectories are trained using an LSTM-CNN neural network architecture that models the interactions between road-agents in dense and heterogeneous traffic. Our trajectory prediction algorithm outperforms state-of-the-art methods for end-to-end trajectory prediction using sensor inputs. We achieve an improvement of upto 18% in average displacement error and an improvement ofup to 35.5% in final displacement error at the end of the prediction window (5 seconds) over the next best method. All experiments were set up on an Nvidia TiTan Xp GPU. Additionally, we release a software framework, TrackNPred. The framework consists of implementations of state-of-the-art tracking and trajectory prediction methods and tools to benchmark and evaluate them on real-world dense traffic datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08752](http://arxiv.org/abs/1907.08752)

##### PDF
[http://arxiv.org/pdf/1907.08752](http://arxiv.org/pdf/1907.08752)

