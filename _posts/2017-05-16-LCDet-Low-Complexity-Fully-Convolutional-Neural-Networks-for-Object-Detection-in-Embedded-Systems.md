---
layout: post
title: "LCDet: Low-Complexity Fully-Convolutional Neural Networks for Object Detection in Embedded Systems"
date: 2017-05-16 21:05:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Image_Classification Classification Detection Face_Detection
author: Subarna Tripathi, Gokce Dane, Byeongkeun Kang, Vasudev Bhaskaran, Truong Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional Neural Networks (CNN) are the state-of-the-art performers for object detection task. It is well known that object detection requires more computation and memory than image classification. Thus the consolidation of a CNN-based object detection for an embedded system is more challenging. In this work, we propose LCDet, a fully-convolutional neural network for generic object detection that aims to work in embedded systems. We design and develop an end-to-end TensorFlow(TF)-based model. Additionally, we employ 8-bit quantization on the learned weights. We use face detection as a use case. Our TF-Slim based network can predict different faces of different shapes and sizes in a single forward pass. Our experimental results show that the proposed method achieves comparative accuracy comparing with state-of-the-art CNN-based face detection methods, while reducing the model size by 3x and memory-BW by ~4x comparing with one of the best real-time CNN-based object detector such as YOLO. TF 8-bit quantized model provides additional 4x memory reduction while keeping the accuracy as good as the floating point model. The proposed model thus becomes amenable for embedded implementations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.05922](https://arxiv.org/abs/1705.05922)

##### PDF
[https://arxiv.org/pdf/1705.05922](https://arxiv.org/pdf/1705.05922)

