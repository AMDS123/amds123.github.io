---
layout: post
title: "Unsupervised Video Interpolation Using Cycle Consistency"
date: 2019-06-13 21:04:10
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Fitsum A. Reda, Deqing Sun, Aysegul Dundar, Mohammad Shoeybi, Guilin Liu, Kevin J. Shih, Andrew Tao, Jan Kautz, Bryan Catanzaro
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to synthesize high frame rate videos via interpolation requires large quantities of high frame rate training videos, which, however, are scarce, especially at high resolutions. Here, we propose unsupervised techniques to synthesize high frame rate videos directly from low frame rate videos using cycle consistency. For a triplet of consecutive frames, we optimize models to minimize the discrepancy between the center frame and its cycle reconstruction, obtained by interpolating back from interpolated intermediate frames. This simple unsupervised constraint alone achieves results comparable with supervision using the ground truth intermediate frames. We further introduce a pseudo supervised loss term that enforces the interpolated frames to be consistent with predictions of a pre-trained interpolation model. The pseudo supervised loss term, used together with cycle consistency, can effectively adapt a pre-trained model to a new target domain. With no additional data and in a completely unsupervised fashion, our techniques significantly improve pre-trained models on new target domains, increasing PSNR values from 32.84dB to 33.05dB on the Slowflow and from 31.82dB to 32.53dB on the Sintel evaluation datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05928](https://arxiv.org/abs/1906.05928)

##### PDF
[https://arxiv.org/pdf/1906.05928](https://arxiv.org/pdf/1906.05928)

