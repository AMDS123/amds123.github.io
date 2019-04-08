---
layout: post
title: "Video Classification with Channel-Separated Convolutional Networks"
date: 2019-04-04 22:28:24
categories: arXiv_AI
tags: arXiv_AI Regularization CNN Image_Classification Video_Classification Classification
author: Du Tran, Heng Wang, Lorenzo Torresani, Matt Feiszli
mathjax: true
---

* content
{:toc}

##### Abstract
Group convolution has been shown to offer great computational savings in various 2D convolutional architectures for image classification. It is natural to ask: 1) if group convolution can help to alleviate the high computational cost of video classification networks; 2) what factors matter the most in 3D group convolutional networks; and 3) what are good computation/accuracy trade-offs with 3D group convolutional networks. This paper studies different effects of group convolution in 3D convolutional networks for video classification. We empirically demonstrate that the amount of channel interactions plays an important role in the accuracy of group convolutional networks. Our experiments suggest two main findings. First, it is a good practice to factorize 3D convolutions by separating channel interactions and spatiotemporal interactions as this leads to improved accuracy and lower computational cost. Second, 3D channel-separated convolutions provide a form of regularization, yielding lower training accuracy but higher test accuracy compared to 3D convolutions. These two empirical findings lead us to design an architecture -- Channel-Separated Convolutional Network (CSN) -- which is simple, efficient, yet accurate. On Kinetics and Sports1M, our CSNs significantly outperform state-of-the-art models while being 11-times more efficient.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02811](https://arxiv.org/abs/1904.02811)

##### PDF
[https://arxiv.org/pdf/1904.02811](https://arxiv.org/pdf/1904.02811)

