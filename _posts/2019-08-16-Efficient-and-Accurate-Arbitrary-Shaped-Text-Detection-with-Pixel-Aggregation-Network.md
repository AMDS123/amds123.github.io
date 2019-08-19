---
layout: post
title: "Efficient and Accurate Arbitrary-Shaped Text Detection with Pixel Aggregation Network"
date: 2019-08-16 09:14:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Wenhai Wang, Enze Xie, Xiaoge Song, Yuhang Zang, Wenjia Wang, Tong Lu, Gang Yu, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text detection, an important step of scene text reading systems, has witnessed rapid development with convolutional neural networks. Nonetheless, two main challenges still exist and hamper its deployment to real-world applications. The first problem is the trade-off between speed and accuracy. The second one is to model the arbitrary-shaped text instance. Recently, some methods have been proposed to tackle arbitrary-shaped text detection, but they rarely take the speed of the entire pipeline into consideration, which may fall short in practical this http URL this paper, we propose an efficient and accurate arbitrary-shaped text detector, termed Pixel Aggregation Network (PAN), which is equipped with a low computational-cost segmentation head and a learnable post-processing. More specifically, the segmentation head is made up of Feature Pyramid Enhancement Module (FPEM) and Feature Fusion Module (FFM). FPEM is a cascadable U-shaped module, which can introduce multi-level information to guide the better segmentation. FFM can gather the features given by the FPEMs of different depths into a final feature for segmentation. The learnable post-processing is implemented by Pixel Aggregation (PA), which can precisely aggregate text pixels by predicted similarity vectors. Experiments on several standard benchmarks validate the superiority of the proposed PAN. It is worth noting that our method can achieve a competitive F-measure of 79.9% at 84.2 FPS on CTW1500.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05900](https://arxiv.org/abs/1908.05900)

##### PDF
[https://arxiv.org/pdf/1908.05900](https://arxiv.org/pdf/1908.05900)

