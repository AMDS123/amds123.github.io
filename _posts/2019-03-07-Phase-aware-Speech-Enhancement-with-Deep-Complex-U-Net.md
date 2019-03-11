---
layout: post
title: "Phase-aware Speech Enhancement with Deep Complex U-Net"
date: 2019-03-07 10:41:37
categories: arXiv_SD
tags: arXiv_SD Deep_Learning Quantitative
author: Hyeong-Seok Choi, Jang-Hyun Kim, Jaesung Huh, Adrian Kim, Jung-Woo Ha, Kyogu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Most deep learning-based models for speech enhancement have mainly focused on estimating the magnitude of spectrogram while reusing the phase from noisy speech for reconstruction. This is due to the difficulty of estimating the phase of clean speech. To improve speech enhancement performance, we tackle the phase estimation problem in three ways. First, we propose Deep Complex U-Net, an advanced U-Net structured model incorporating well-defined complex-valued building blocks to deal with complex-valued spectrograms. Second, we propose a polar coordinate-wise complex-valued masking method to reflect the distribution of complex ideal ratio masks. Third, we define a novel loss function, weighted source-to-distortion ratio (wSDR) loss, which is designed to directly correlate with a quantitative evaluation measure. Our model was evaluated on a mixture of the Voice Bank corpus and DEMAND database, which has been widely used by many deep learning models for speech enhancement. Ablation experiments were conducted on the mixed dataset showing that all three proposed approaches are empirically valid. Experimental results show that the proposed method achieves state-of-the-art performance in all metrics, outperforming previous approaches by a large margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03107](http://arxiv.org/abs/1903.03107)

##### PDF
[http://arxiv.org/pdf/1903.03107](http://arxiv.org/pdf/1903.03107)

