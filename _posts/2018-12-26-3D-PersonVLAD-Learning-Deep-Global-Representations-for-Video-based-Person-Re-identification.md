---
layout: post
title: "3D PersonVLAD: Learning Deep Global Representations for Video-based Person Re-identification"
date: 2018-12-26 04:51:55
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification CNN
author: Lin Wu, Yang Wang, Ling Shao, Meng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a global video representation to video-based person re-identification (re-ID) that aggregates local 3D features across the entire video extent. Most of the existing methods rely on 2D convolutional networks (ConvNets) to extract frame-wise deep features which are pooled temporally to generate the video-level representations. However, 2D ConvNets lose temporal input information immediately after the convolution, and a separate temporal pooling is limited in capturing human motion in shorter sequences. To this end, we present a \textit{global} video representation (3D PersonVLAD), complementary to 3D ConvNets as a novel layer to capture the appearance and motion dynamics in full-length videos. However, encoding each video frame in its entirety and computing an aggregate global representation across all frames is tremendously challenging due to occlusions and misalignments. To resolve this, our proposed network is further augmented with 3D part alignment module to learn local features through soft-attention module. These attended features are statistically aggregated to yield identity-discriminative representations. Our global 3D features are demonstrated to achieve state-of-the-art results on three benchmark datasets: MARS \cite{MARS}, iLIDS-VID \cite{VideoRanking}, and PRID 2011

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10222](http://arxiv.org/abs/1812.10222)

##### PDF
[http://arxiv.org/pdf/1812.10222](http://arxiv.org/pdf/1812.10222)

