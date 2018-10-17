---
layout: post
title: "Deep Photovoltaic Nowcasting"
date: 2018-10-15 13:00:31
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Prediction Quantitative Relation
author: Jinsong Zhang, Rodrigo Verschae, Shohei Nobuhara, Jean-François Lalonde
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting the short-term power output of a photovoltaic panel is an important task for the efficient management of smart grids. Short-term forecasting at the minute scale, also known as nowcasting, can benefit from sky images captured by regular cameras and installed close to the solar panel. However, estimating the weather conditions from these images---sun intensity, cloud appearance and movement, etc.---is a very challenging task that the community has yet to solve with traditional computer vision techniques. In this work, we propose to learn the relationship between sky appearance and the future photovoltaic power output using deep learning. We train several variants of convolutional neural networks which take historical photovoltaic power values and sky images as input and estimate photovoltaic power in a very short term future. In particular, we compare three different architectures based on: a multi-layer perceptron (MLP), a convolutional neural network (CNN), and a long short term memory (LSTM) module. We evaluate our approach quantitatively on a dataset of photovoltaic power values and corresponding images gathered in Kyoto, Japan. Our experiments reveal that the MLP network, already used similarly in previous work, achieves an RMSE skill score of 7% over the commonly-used persistence baseline on the 1-minute future photovoltaic power prediction task. Our CNN-based network improves upon this with a 12% skill score. In contrast, our LSTM-based model, which can learn the temporal dependencies in the data, achieves a 21% RMSE skill score, thus outperforming all other approaches.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.06327](https://arxiv.org/abs/1810.06327)

##### PDF
[https://arxiv.org/pdf/1810.06327](https://arxiv.org/pdf/1810.06327)

