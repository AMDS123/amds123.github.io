---
layout: post
title: "Deep Neural Network Based Hyperspectral Pixel Classification With Factorized Spectral-Spatial Feature Representation"
date: 2019-04-16 04:52:19
categories: arXiv_AI
tags: arXiv_AI Image_Classification Classification Deep_Learning Relation
author: Jingzhou Chen, Siyu Chen, Peilin Zhou, Yuntao Qian
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has been widely used for hyperspectral pixel classification due to its ability of generating deep feature representation. However, how to construct an efficient and powerful network suitable for hyperspectral data is still under exploration. In this paper, a novel neural network model is designed for taking full advantage of the spectral-spatial structure of hyperspectral data. Firstly, we extract pixel-based intrinsic features from rich yet redundant spectral bands by a subnetwork with supervised pre-training scheme. Secondly, in order to utilize the local spatial correlation among pixels, we share the previous subnetwork as a spectral feature extractor for each pixel in a patch of image, after which the spectral features of all pixels in a patch are combined and feeded into the subsequent classification subnetwork. Finally, the whole network is further fine-tuned to improve its classification performance. Specially, the spectral-spatial factorization scheme is applied in our model architecture, making the network size and the number of parameters great less than the existing spectral-spatial deep networks for hyperspectral image classification. Experiments on the hyperspectral data sets show that, compared with some state-of-art deep learning methods, our method achieves better classification results while having smaller network size and less parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07461](http://arxiv.org/abs/1904.07461)

##### PDF
[http://arxiv.org/pdf/1904.07461](http://arxiv.org/pdf/1904.07461)

