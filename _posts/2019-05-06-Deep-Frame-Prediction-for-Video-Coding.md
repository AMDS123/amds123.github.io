---
layout: post
title: "Deep Frame Prediction for Video Coding"
date: 2019-05-06 17:19:47
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Hyomin Choi, Ivan V. Bajic
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel frame prediction method using a deep neural network (DNN), with the goal of improving video coding efficiency. The proposed DNN makes use of decoded frames, at both encoder and decoder, to predict textures of the current coding block. Unlike conventional inter-prediction, the proposed method does not require any motion information to be transferred between the encoder and the decoder. Still, both uni-directional and bi-directional prediction are possible using the proposed DNN, which is enabled by the use of the temporal index channel, in addition to color channels. In this study, we developed a jointly trained DNN for both uni- and bi- directional prediction, as well as separate networks for uni- and bi-directional prediction, and compared the efficacy of both approaches. The proposed DNNs were compared with the conventional motion-compensated prediction in the latest video coding standard, HEVC, in terms of BD-Bitrate. The experiments show that the proposed joint DNN (for both uni- and bi-directional prediction) reduces the luminance bitrate by about 4.4%, 2.4%, and 2.3% in the Low delay P, Low delay, and Random access configurations, respectively. In addition, using the separately trained DNNs brings further bit savings of about 0.3%-0.5%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.00062](http://arxiv.org/abs/1901.00062)

##### PDF
[http://arxiv.org/pdf/1901.00062](http://arxiv.org/pdf/1901.00062)

