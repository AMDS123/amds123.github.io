---
layout: post
title: "Towards Image Understanding from Deep Compression without Decoding"
date: 2018-03-16 09:51:09
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation Inference Classification
author: Robert Torfason, Fabian Mentzer, Eirikur Agustsson, Michael Tschannen, Radu Timofte, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by recent work on deep neural network (DNN)-based image compression methods showing potential improvements in image quality, savings in storage, and bandwidth reduction, we propose to perform image understanding tasks such as classification and segmentation directly on the compressed representations produced by these compression methods. Since the encoders and decoders in DNN-based compression methods are neural networks with feature-maps as internal representations of the images, we directly integrate these with architectures for image understanding. This bypasses decoding of the compressed representation into RGB space and reduces computational cost. Our study shows that accuracies comparable to networks that operate on compressed RGB images can be achieved while reducing the computational complexity up to $2\times$. Furthermore, we show that synergies are obtained by jointly training compression networks with classification networks on the compressed representations, improving image quality, classification accuracy, and segmentation performance. We find that inference from compressed representations is particularly advantageous compared to inference from compressed RGB images for aggressive compression rates.

##### Abstract (translated by Google)
基于深度神经网络（DNN）的图像压缩方法在图像质量，存储和存储带宽等方面的潜力得到改善，我们提出直接对图像进行分类和分割等任务，这些压缩方法。由于基于DNN的压缩方法中的编码器和解码器是具有特征映射作为图像内部表示的神经网络，因此我们直接将这些与架构进行整合以便于图像理解。这绕过了将压缩表示解码成RGB空间并降低了计算成本。我们的研究表明，与在压缩的RGB图像上运行的网络相比，精度可以达到，同时将计算复杂度降低到$ 2 \ times $。此外，我们表明，通过联合训练压缩网络和压缩表示的分类网络，提高图像质量，分类准确性和分割性能，可以获得协同效应。我们发现，与压缩的RGB图像对激进压缩率的推断相比，压缩表示的推理特别有利。

##### URL
[https://arxiv.org/abs/1803.06131](https://arxiv.org/abs/1803.06131)

##### PDF
[https://arxiv.org/pdf/1803.06131](https://arxiv.org/pdf/1803.06131)

