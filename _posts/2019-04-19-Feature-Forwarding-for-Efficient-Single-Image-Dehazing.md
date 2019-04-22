---
layout: post
title: "Feature Forwarding for Efficient Single Image Dehazing"
date: 2019-04-19 03:20:52
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Peter Morales, Tzofi Klinghoffer, Seung Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Haze degrades content and obscures information of images, which can negatively impact vision-based decision-making in real-time systems. In this paper, we propose an efficient fully convolutional neural network (CNN) image dehazing method designed to run on edge graphical processing units (GPUs). We utilize three variants of our architecture to explore the dependency of dehazed image quality on parameter count and model design. The first two variants presented, a small and big version, make use of a single efficient encoder--decoder convolutional feature extractor. The final variant utilizes a pair of encoder--decoders for atmospheric light and transmission map estimation. Each variant ends with an image refinement pyramid pooling network to form the final dehazed image. For the big variant of the single-encoder network, we demonstrate state-of-the-art performance on the NYU Depth dataset. For the small variant, we maintain competitive performance on the super-resolution O/I-HAZE datasets without the need for image cropping. Finally, we examine some challenges presented by the Dense-Haze dataset when leveraging CNN architectures for dehazing of dense haze imagery and examine the impact of loss function selection on image quality. Benchmarks are included to show the feasibility of introducing this approach into real-time systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09059](http://arxiv.org/abs/1904.09059)

##### PDF
[http://arxiv.org/pdf/1904.09059](http://arxiv.org/pdf/1904.09059)

