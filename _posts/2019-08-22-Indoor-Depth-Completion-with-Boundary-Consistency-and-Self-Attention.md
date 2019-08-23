---
layout: post
title: "Indoor Depth Completion with Boundary Consistency and Self-Attention"
date: 2019-08-22 12:58:43
categories: arXiv_CV
tags: arXiv_CV Attention Face Recognition
author: Yu-Kai Huang, Tsung-Han Wu, Yueh-Cheng Liu, Winston H. Hsu
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation features are helpful for 3D recognition. Commodity-grade depth cameras are able to capture depth and color image in real-time. However, glossy, transparent or distant surface cannot be scanned properly by the sensor. As a result, enhancement and restoration from sensing depth is an important task. Depth completion aims at filling the holes that sensors fail to detect, which is still a complex task for machine to learn. Traditional hand-tuned methods have reached their limits, while neural network based methods tend to copy and interpolate the output from surrounding depth values. This leads to blurred boundaries, and structures of the depth map are lost. Consequently, our main work is to design an end-to-end network improving completion depth maps while maintaining edge clarity. We utilize self-attention mechanism, previously used in image inpainting fields, to extract more useful information in each layer of convolution so that the complete depth map is enhanced. In addition, we propose boundary consistency concept to enhance the depth map quality and structure. Experimental results validate the effectiveness of our self-attention and boundary consistency schema, which outperforms previous state-of-the-art depth completion work on Matterport3D dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08344](https://arxiv.org/abs/1908.08344)

##### PDF
[https://arxiv.org/pdf/1908.08344](https://arxiv.org/pdf/1908.08344)

