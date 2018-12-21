---
layout: post
title: "SQuantizer: Simultaneous Learning for Both Sparse and Low-precision Neural Networks"
date: 2018-12-20 00:55:55
categories: arXiv_AI
tags: arXiv_AI Object_Detection Sparse Speech_Recognition Detection Recognition
author: Mi Sun Park, Xiaofan Xu, Cormac Brick
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved state-of-the-art accuracies in a wide range of computer vision, speech recognition, and machine translation tasks. However the limits of memory bandwidth and computational power constrain the range of devices capable of deploying these modern networks. To address this problem, we propose SQuantizer, a new training method that jointly optimizes for both sparse and low-precision neural networks while maintaining high accuracy and providing a high compression rate. This approach brings sparsification and low-bit quantization into a single training pass, employing these techniques in an order demonstrated to be optimal. Our method achieves state-of-the-art accuracies using 4-bit and 2-bit precision for ResNet18, MobileNet-v2 and ResNet50, even with high degree of sparsity. The compression rates of 18x for ResNet18 and 17x for ResNet50, and 9x for MobileNet-v2 are obtained when SQuantizing both weights and activations within 1% and 2% loss in accuracy for ResNets and MobileNet-v2 respectively. An extension of these techniques to object detection also demonstrates high accuracy on YOLO-v2. Additionally, our method allows for fast single pass training, which is important for rapid prototyping and neural architecture search techniques. Finally extensive results from this simultaneous training approach allows us to draw some useful insights into the relative merits of sparsity and quantization.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.08301](https://arxiv.org/abs/1812.08301)

##### PDF
[https://arxiv.org/pdf/1812.08301](https://arxiv.org/pdf/1812.08301)

