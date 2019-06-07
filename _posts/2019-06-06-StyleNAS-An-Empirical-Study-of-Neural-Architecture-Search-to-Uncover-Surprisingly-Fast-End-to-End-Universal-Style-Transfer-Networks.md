---
layout: post
title: "StyleNAS: An Empirical Study of Neural Architecture Search to Uncover Surprisingly Fast End-to-End Universal Style Transfer Networks"
date: 2019-06-06 08:21:04
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation NAS Style_Transfer Image_Classification Semantic_Segmentation Inference Classification Deep_Learning Detection
author: Jie An, Haoyi Xiong, Jinwen Ma, Jiebo Luo, Jun Huan
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Architecture Search (NAS) has been widely studied for designing discriminative deep learning models such as image classification, object detection, and semantic segmentation. As a large number of priors have been obtained through the manual design of architectures in the fields, NAS is usually considered as a supplement approach. In this paper, we have significantly expanded the application areas of NAS by performing an empirical study of NAS to search generative models, or specifically, auto-encoder based universal style transfer, which lacks systematic exploration, if any, from the architecture search aspect. In our work, we first designed a search space where common operators for image style transfer such as VGG-based encoders, whitening and coloring transforms (WCT), convolution kernels, instance normalization operators, and skip connections were searched in a combinatorial approach. With a simple yet effective parallel evolutionary NAS algorithm with multiple objectives, we derived the first group of end-to-end deep networks for universal photorealistic style transfer. Comparing to random search, a NAS method that is gaining popularity recently, we demonstrated that carefully designed search strategy leads to much better architecture design. Finally compared to existing universal style transfer networks for photorealistic rendering such as PhotoWCT that stacks multiple well-trained auto-encoders and WCT transforms in a non-end-to-end manner, the architectures designed by StyleNAS produce better style-transferred images with details preserving, using a tiny number of operators/parameters, and enjoying around 500x inference time speed-up.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.02470](https://arxiv.org/abs/1906.02470)

##### PDF
[https://arxiv.org/pdf/1906.02470](https://arxiv.org/pdf/1906.02470)

