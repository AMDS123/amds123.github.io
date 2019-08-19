---
layout: post
title: "TASED-Net: Temporally-Aggregating Spatial Encoder-Decoder Network for Video Saliency Detection"
date: 2019-08-15 22:30:50
categories: arXiv_CV
tags: arXiv_CV Salient CNN Prediction Detection
author: Kyle Min, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
TASED-Net is a 3D fully-convolutional network architecture for video saliency detection. It consists of two building blocks: first, the encoder network extracts low-resolution spatiotemporal features from an input clip of several consecutive frames, and then the following prediction network decodes the encoded features spatially while aggregating all the temporal information. As a result, a single prediction map is produced from an input clip of multiple frames. Frame-wise saliency maps can be predicted by applying TASED-Net in a sliding-window fashion to a video. The proposed approach assumes that the saliency map of any frame can be predicted by considering a limited number of past frames. The results of our extensive experiments on video saliency detection validate this assumption and demonstrate that our fully-convolutional model with temporal aggregation method is effective. TASED-Net significantly outperforms previous state-of-the-art approaches on all three major large-scale datasets of video saliency detection: DHF1K, Hollywood2, and UCFSports. After analyzing the results qualitatively, we observe that our model is especially better at attending to salient moving objects.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05786](https://arxiv.org/abs/1908.05786)

##### PDF
[https://arxiv.org/pdf/1908.05786](https://arxiv.org/pdf/1908.05786)

