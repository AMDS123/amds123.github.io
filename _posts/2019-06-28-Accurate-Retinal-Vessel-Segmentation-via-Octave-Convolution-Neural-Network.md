---
layout: post
title: "Accurate Retinal Vessel Segmentation via Octave Convolution Neural Network"
date: 2019-06-28 13:07:36
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Zhun Fan, Jiajie Mo, Benzhang Qiu
mathjax: true
---

* content
{:toc}

##### Abstract
Retinal vessel segmentation is a crucial step in diagnosing and screening various diseases, including diabetes, ophthalmologic diseases, and cardiovascular diseases. In this paper, we proposed an effective and efficient method for accurate vessel segmentation in color fundus images using encoder-decoder based octave convolution network. Comparing to other convolution network based methods that utilize vanilla convolution for feature extraction, the proposed method adopts octave convolution for multiple-spatial-frequency features learning, thus can better capture retinal vasculature with varying size and shape. We empirically demonstrate that the feature map of low-frequency kernels responds focus on the major vascular tree, whereas the high-frequency feature map can better captures the minor details of low contrasted thin vessels. To provide the network capability of learning how to decode multifrequency features, we extended octave convolution and proposed a novel operation named octave transposed convolution with the same multifrequency approach. We also proposed a novel encoder-decoder based fully convolution network named Octave UNet that generates high resolution vessel segmentation in single forward feeding. The proposed method is evaluated on four publicly available datasets, DRIVE, STARE, CHASE_DB1, and HRF datasets. Extensive experimental results demonstrate the proposed method achieves better or compatible performance to state-of-the-art methods with fast processing speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12193](http://arxiv.org/abs/1906.12193)

##### PDF
[http://arxiv.org/pdf/1906.12193](http://arxiv.org/pdf/1906.12193)

