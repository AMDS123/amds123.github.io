---
layout: post
title: "Multi-scale deep neural networks for real image super-resolution"
date: 2019-04-24 08:43:18
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Shangqi Gao, Xiahai Zhuang
mathjax: true
---

* content
{:toc}

##### Abstract
Single image super-resolution (SR) is extremely difficult if the upscaling factors of image pairs are unknown and different from each other, which is common in real image SR. To tackle the difficulty, we develop two multi-scale deep neural networks (MsDNN) in this work. Firstly, due to the high computation complexity in high-resolution spaces, we process an input image mainly in two different downscaling spaces, which could greatly lower the usage of GPU memory. Then, to reconstruct the details of an image, we design a multi-scale residual network (MsRN) in the downscaling spaces based on the residual blocks. Besides, we propose a multi-scale dense network based on the dense blocks to compare with MsRN. Finally, our empirical experiments show the robustness of MsDNN for image SR when the upscaling factor is unknown. According to the preliminary results of NTIRE 2019 image SR challenge, our team (ZXHresearch@fudan) ranks 21-st among all participants. The implementation of MsDNN is released https://github.com/shangqigao/gsq-image-SR

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10698](http://arxiv.org/abs/1904.10698)

##### PDF
[http://arxiv.org/pdf/1904.10698](http://arxiv.org/pdf/1904.10698)

