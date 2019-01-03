---
layout: post
title: "Deep Frame Prediction for Video Coding"
date: 2018-12-31 23:41:50
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Hyomin Choi, Ivan V. Bajic
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel frame prediction method using a deep neural network (DNN), with the goal of improving video coding efficiency. The proposed DNN makes use of decoded frames, at both encoder and decoder, to predict textures of the current coding block. Unlike conventional inter-prediction, the proposed method does not require any motion information to be transferred between the encoder and the decoder. Still, both uni-directional and bi-directional prediction are possible using the proposed DNN, which is enabled by the use of the temporal index channel, in addition to color channels. In this study, we developed a jointly trained DNN for both uni- and bi-directional prediction, as well as separate networks for uni- and bi-directional prediction, and compared the efficacy of both approaches. The proposed DNNs were compared with the conventional motion-compensated prediction in the latest video coding standard, HEVC, in terms of BD-Bitrate. The experiments show that the proposed joint DNN (for both uni- and bi-directional prediction) reduces the luminance bitrate by about 3.9%, 2.2%, and 2.2% in the Low delay P, Low delay, and Random access configurations, respectively. In addition, using the separately trained DNNs brings further bit savings of about 0.4%-0.8%.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.00062](https://arxiv.org/abs/1901.00062)

##### PDF
[https://arxiv.org/pdf/1901.00062](https://arxiv.org/pdf/1901.00062)

