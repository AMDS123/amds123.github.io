---
layout: post
title: "Harmonic Unpaired Image-to-image Translation"
date: 2019-02-26 04:49:56
categories: arXiv_CV
tags: arXiv_CV GAN Image_Generation Quantitative
author: Rui Zhang, Tomas Pfister, Jia Li
mathjax: true
---

* content
{:toc}

##### Abstract
The recent direction of unpaired image-to-image translation is on one hand very exciting as it alleviates the big burden in obtaining label-intensive pixel-to-pixel supervision, but it is on the other hand not fully satisfactory due to the presence of artifacts and degenerated transformations. In this paper, we take a manifold view of the problem by introducing a smoothness term over the sample graph to attain harmonic functions to enforce consistent mappings during the translation. We develop HarmonicGAN to learn bi-directional translations between the source and the target domains. With the help of similarity-consistency, the inherent self-consistency property of samples can be maintained. Distance metrics defined on two types of features including histogram and CNN are exploited. Under an identical problem setting as CycleGAN, without additional manual inputs and only at a small training-time cost, HarmonicGAN demonstrates a significant qualitative and quantitative improvement over the state of the art, as well as improved interpretability. We show experimental results in a number of applications including medical imaging, object transfiguration, and semantic labeling. We outperform the competing methods in all tasks, and for a medical imaging task in particular our method turns CycleGAN from a failure to a success, halving the mean-squared error, and generating images that radiologists prefer over competing methods in 95% of cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09727](http://arxiv.org/abs/1902.09727)

##### PDF
[http://arxiv.org/pdf/1902.09727](http://arxiv.org/pdf/1902.09727)

