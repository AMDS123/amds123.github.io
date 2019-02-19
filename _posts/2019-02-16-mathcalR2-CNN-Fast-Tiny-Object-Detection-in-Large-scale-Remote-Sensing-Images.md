---
layout: post
title: "$mathcal{R}^2$-CNN: Fast Tiny Object Detection in Large-scale Remote Sensing Images"
date: 2019-02-16 04:59:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Attention CNN Detection
author: Jiangmiao Pang, Cong Li, Jianping Shi, Zhihai Xu, Huajun Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, convolutional neural network has brought impressive improvements for object detection. However, detecting tiny objects in large-scale remote sensing images still remains challenging. Firstly, the extreme large input size makes existing object detection solutions too slow for practical use. Secondly, the massive and complex backgrounds cause serious false alarms. Moreover, the ultra tiny objects increase the difficulty of accurate detection. To tackle these problems, we propose a unified and self-reinforced network called $\mathcal{R}^2$-CNN: Remote sensing Region-based Convolutional Neural Network, composing of backbone Tiny-Net, intermediate global attention block, and final classifier and detector. Tiny-Net is a lightweight residual structure which enables fast and powerful features extraction from inputs. Global attention block is built upon Tiny-Net to inhibit false positives. Classifier is then used to predict the existence of target in each patch, and detector is followed to locate them accurately if available. The classifier and detector are mutually reinforced with end-to-end training, which further speed-up the process and avoid false alarms. Effectiveness of $\mathcal{R}^2$-CNN is validated on hundreds of \emph{GF-1} images and \emph{GF-2} images, which are $18000 \times 18192$ pixels, 2.0m resolution, and $27620 \times 29200$ pixels, 0.8m resolution respectively. Specifically, we can process a GF-1 image in 29.4s on Titian X just with single thread. According to our knowledge, no previous solution can detect tiny object on such huge remote sensing images gracefully. We believe that it is a significant step towards practical real-time remote sensing systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06042](http://arxiv.org/abs/1902.06042)

##### PDF
[http://arxiv.org/pdf/1902.06042](http://arxiv.org/pdf/1902.06042)

