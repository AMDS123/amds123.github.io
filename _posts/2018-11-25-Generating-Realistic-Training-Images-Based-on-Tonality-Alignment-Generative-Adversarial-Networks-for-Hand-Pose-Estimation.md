---
layout: post
title: "Generating Realistic Training Images Based on Tonality-Alignment Generative Adversarial Networks for Hand Pose Estimation"
date: 2018-11-25 01:18:13
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Pose_Estimation
author: Liangjian Chen, Shih-Yao Lin, Yusheng Xie, Hui Tang, Yufan Xue, Xiaohui Xie, Yen-Yu Lin, Wei Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Hand pose estimation from a monocular RGB image is an important but challenging task. The main factor affecting its performance is the lack of a sufficiently large training dataset with accurate hand-keypoint annotations. In this work, we circumvent this problem by proposing an effective method for generating realistic hand poses and show that state-of-the-art algorithms for hand pose estimation can be greatly improved by utilizing the generated hand poses as training data. Specifically, we first adopt an augmented reality (AR) simulator to synthesize hand poses with accurate hand-keypoint labels. Although the synthetic hand poses come with precise joint labels, eliminating the need of manual annotations, they look unnatural and are not the ideal training data. To produce more realistic hand poses, we propose to blend a synthetic hand pose with a real background, such as arms and sleeves. To this end, we develop tonality-alignment generative adversarial networks (TAGANs), which align the tonality and color distributions between synthetic hand poses and real backgrounds, and can generate high quality hand poses. We evaluate TAGAN on three benchmarks, including the RHP, STB, and CMU-PS hand pose datasets. With the aid of the synthesized poses, our method performs favorably against the state-of-the-arts in both $2$D and $3$D hand pose estimations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09916](https://arxiv.org/abs/1811.09916)

##### PDF
[https://arxiv.org/pdf/1811.09916](https://arxiv.org/pdf/1811.09916)

