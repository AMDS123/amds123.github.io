---
layout: post
title: "Deep Griffin-Lim Iteration"
date: 2019-03-10 11:27:34
categories: arXiv_SD
tags: arXiv_SD Knowledge
author: Yoshiki Masuyama, Kohei Yatabe, Yuma Koizumi, Yasuhiro Oikawa, Noboru Harada
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel phase reconstruction method (only from a given amplitude spectrogram) by combining a signal-processing-based approach and a deep neural network (DNN). To retrieve a time-domain signal from its amplitude spectrogram, the corresponding phase is required. One of the popular phase reconstruction methods is the Griffin-Lim algorithm (GLA), which is based on the redundancy of the short-time Fourier transform. However, GLA often involves many iterations and produces low-quality signals owing to the lack of prior knowledge of the target signal. In order to address these issues, in this study, we propose an architecture which stacks a sub-block including two GLA-inspired fixed layers and a DNN. The number of stacked sub-blocks is adjustable, and we can trade the performance and computational load based on requirements of applications. The effectiveness of the proposed method is investigated by reconstructing phases from amplitude spectrograms of speeches.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03971](https://arxiv.org/abs/1903.03971)

##### PDF
[https://arxiv.org/pdf/1903.03971](https://arxiv.org/pdf/1903.03971)

