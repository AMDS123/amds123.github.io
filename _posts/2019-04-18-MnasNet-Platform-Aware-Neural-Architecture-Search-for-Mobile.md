---
layout: post
title: "MnasNet: Platform-Aware Neural Architecture Search for Mobile"
date: 2019-04-18 17:10:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Inference Classification Detection
author: Mingxing Tan, Bo Chen, Ruoming Pang, Vijay Vasudevan, Mark Sandler, Andrew Howard, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Designing convolutional neural networks (CNN) for mobile devices is challenging because mobile models need to be small and fast, yet still accurate. Although significant efforts have been dedicated to design and improve mobile CNNs on all dimensions, it is very difficult to manually balance these trade-offs when there are so many architectural possibilities to consider. In this paper, we propose an automated mobile neural architecture search (MNAS) approach, which explicitly incorporate model latency into the main objective so that the search can identify a model that achieves a good trade-off between accuracy and latency. Unlike previous work, where latency is considered via another, often inaccurate proxy (e.g., FLOPS), our approach directly measures real-world inference latency by executing the model on mobile phones. To further strike the right balance between flexibility and search space size, we propose a novel factorized hierarchical search space that encourages layer diversity throughout the network. Experimental results show that our approach consistently outperforms state-of-the-art mobile CNN models across multiple vision tasks. On the ImageNet classification task, our MnasNet achieves 75.2% top-1 accuracy with 78ms latency on a Pixel phone, which is 1.8x faster than MobileNetV2 [29] with 0.5% higher accuracy and 2.3x faster than NASNet [36] with 1.2% higher accuracy. Our MnasNet also achieves better mAP quality than MobileNets for COCO object detection. Code is at https://github.com/tensorflow/tpu/tree/master/models/official/mnasnet

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.11626](http://arxiv.org/abs/1807.11626)

##### PDF
[http://arxiv.org/pdf/1807.11626](http://arxiv.org/pdf/1807.11626)

