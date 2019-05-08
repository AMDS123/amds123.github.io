---
layout: post
title: "Learning Spatio-Temporal Features with Two-Stream Deep 3D CNNs for Lipreading"
date: 2019-05-04 02:32:06
categories: arXiv_CV
tags: arXiv_CV CNN RNN Classification
author: Xinshuo Weng, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the word-level visual lipreading, which requires recognizing the word being spoken, given only the video but not the audio. State-of-the-art methods explore the use of end-to-end neural networks, including a shallow (up to three layers) 3D convolutional neural network (CNN) + a deep 2D CNN (\emph{e.g.}, ResNet) as the front-end to extract visual features, and a recurrent neural network (\emph{e.g.}, bidirectional LSTM) as the back-end for classification. In this work, we propose to replace the shallow 3D CNNs + deep 2D CNNs front-end with recent successful deep 3D CNNs --- two-stream (\emph{i.e.}, grayscale video and optical flow streams) I3D. We evaluate different combinations of front-end and back-end modules with the grayscale video and optical flow inputs on the LRW dataset. The experiments show that, compared to the shallow 3D CNNs + deep 2D CNNs front-end, the deep 3D CNNs front-end with pre-training on the large-scale image and video datasets (\emph{e.g.}, ImageNet and Kinetics) can improve the classification accuracy. On the other hand, we demonstrate that using the optical flow input alone can achieve comparable performance as using the grayscale video as input. Moreover, the two-stream network using both the grayscale video and optical flow inputs can further improve the performance. Overall, our two-stream I3D front-end with a Bi-LSTM back-end results in an absolute improvement of 5.3\% over the previous art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02540](https://arxiv.org/abs/1905.02540)

##### PDF
[https://arxiv.org/pdf/1905.02540](https://arxiv.org/pdf/1905.02540)

