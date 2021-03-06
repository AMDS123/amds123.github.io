---
layout: post
title: "Multi-Channel CNN-based Object Detection for Enhanced Situation Awareness"
date: 2017-11-30 20:54:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Transfer_Learning Deep_Learning Detection
author: Shuo Liu, Zheng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Object Detection is critical for automatic military operations. However, the performance of current object detection algorithms is deficient in terms of the requirements in military scenarios. This is mainly because the object presence is hard to detect due to the indistinguishable appearance and dramatic changes of object's size which is determined by the distance to the detection sensors. Recent advances in deep learning have achieved promising results in many challenging tasks. The state-of-the-art in object detection is represented by convolutional neural networks (CNNs), such as the fast R-CNN algorithm. These CNN-based methods improve the detection performance significantly on several public generic object detection datasets. However, their performance on detecting small objects or undistinguishable objects in visible spectrum images is still insufficient. In this study, we propose a novel detection algorithm for military objects by fusing multi-channel CNNs. We combine spatial, temporal and thermal information by generating a three-channel image, and they will be fused as CNN feature maps in an unsupervised manner. The backbone of our object detection framework is from the fast R-CNN algorithm, and we utilize cross-domain transfer learning technique to fine-tune the CNN model on generated multi-channel images. In the experiments, we validated the proposed method with the images from SENSIAC (Military Sensing Information Analysis Centre) database and compared it with the state-of-the-art. The experimental results demonstrated the effectiveness of the proposed method on both accuracy and computational efficiency.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.00075](https://arxiv.org/abs/1712.00075)

##### PDF
[https://arxiv.org/pdf/1712.00075](https://arxiv.org/pdf/1712.00075)

