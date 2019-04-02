---
layout: post
title: "Understanding Unconventional Preprocessors in Deep Convolutional Neural Networks for Face Identification"
date: 2019-03-27 13:05:55
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Transfer_Learning Recognition Face_Recognition
author: Chollette C. Olisah, Lyndon Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Deep networks have achieved huge successes in application domains like object and face recognition. The performance gain is attributed to different facets of the network architecture such as: depth of the convolutional layers, activation function, pooling, batch normalization, forward and back propagation and many more. However, very little emphasis is made on the preprocessors. Therefore, in this paper, the network's preprocessing module is varied across different preprocessing approaches while keeping constant other facets of the network architecture, to investigate the contribution preprocessing makes to the network. Commonly used preprocessors are the data augmentation and normalization and are termed conventional preprocessors. Others are termed the unconventional preprocessors, they are: color space converters; HSV, CIE L*a*b* and YCBCR, grey-level resolution preprocessors; full-based and plane-based image quantization, illumination normalization and insensitive feature preprocessing using: histogram equalization (HE), local contrast normalization (LN) and complete face structural pattern (CFSP). To achieve fixed network parameters, CNNs with transfer learning is employed. Knowledge from the high-level feature vectors of the Inception-V3 network is transferred to offline preprocessed LFW target data; and features trained using the SoftMax classifier for face identification. The experiments show that the discriminative capability of the deep networks can be improved by preprocessing RGB data with HE, full-based and plane-based quantization, rgbGELog, and YCBCR, preprocessors before feeding it to CNNs. However, for best performance, the right setup of preprocessed data with augmentation and/or normalization is required. The plane-based image quantization is found to increase the homogeneity of neighborhood pixels and utilizes reduced bit depth for better storage efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00815](http://arxiv.org/abs/1904.00815)

##### PDF
[http://arxiv.org/pdf/1904.00815](http://arxiv.org/pdf/1904.00815)

