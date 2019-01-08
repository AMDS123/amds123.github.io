---
layout: post
title: "Microscopy Cell Segmentation via Convolutional LSTM Networks"
date: 2019-01-06 19:19:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN RNN
author: Assaf Arbelle, Tammy Riklin Raviv
mathjax: true
---

* content
{:toc}

##### Abstract
Live cell microscopy sequences exhibit complex spatial structures and complicated temporal behaviour, making their analysis a challenging task. Considering cell segmentation problem, which plays a significant role in the analysis, the spatial properties of the data can be captured using Convolutional Neural Networks (CNNs). Recent approaches show promising segmentation results using convolutional encoder-decoders such as the U-Net. Nevertheless, these methods are limited by their inability to incorporate temporal information, that can facilitate segmentation of individual touching cells or of cells that are partially visible. In order to exploit cell dynamics we propose a novel segmentation architecture which integrates Convolutional Long Short Term Memory (C-LSTM) with the U-Net. The network's unique architecture allows it to capture multi-scale, compact, spatio-temporal encoding in the C-LSTMs memory units. The method was evaluated on the Cell Tracking Challenge and achieved state-of-the-art results (1st on Fluo-N2DH-SIM+ and 2nd on DIC-C2DL-HeLa datasets) The code is freely available at: https://github.com/arbellea/LSTM-UNet.git

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.11247](http://arxiv.org/abs/1805.11247)

##### PDF
[http://arxiv.org/pdf/1805.11247](http://arxiv.org/pdf/1805.11247)

