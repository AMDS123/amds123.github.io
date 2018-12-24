---
layout: post
title: "Densely Semantically Aligned Person Re-Identification"
date: 2018-12-21 06:23:34
categories: arXiv_CV
tags: arXiv_CV Re-identification Knowledge Person_Re-identification Inference Detection
author: Zhizheng Zhang, Cuiling Lan, Wenjun Zeng, Zhibo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a densely semantically aligned person re-identification (re-ID) framework. It fundamentally addresses the body misalignment problem caused by pose/viewpoint variations, imperfect person detection, occlusion,etc.. By leveraging the estimation of the dense semantics of a person image, we construct a set of densely semantically aligned part images (DSAP-images), where the same spatial positions have the same semantics across different person images. We design a two-stream network that consists of a main full image stream (MF-Stream) and a densely semantically-aligned guiding stream (DSAG-Stream). The DSAG-Stream, with the DSAP-images as input, acts as a regulator to guide the MF-Stream to learn densely semantically aligned features from the original image. In the inference, the DSAG-Stream is discarded and only the MF-Stream is needed, which makes the inference system computationally efficient and robust. To our best knowledge, we are the first to make use of fine grained semantics for addressing misalignment problems for re-ID. Our method achieves rank-1 accuracy of 78.9% (new protocol) on the CUHK03 dataset, 90.4% on the CUHK01 dataset, and 95.7% on the Market1501 dataset, outperforming state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08967](http://arxiv.org/abs/1812.08967)

##### PDF
[http://arxiv.org/pdf/1812.08967](http://arxiv.org/pdf/1812.08967)

