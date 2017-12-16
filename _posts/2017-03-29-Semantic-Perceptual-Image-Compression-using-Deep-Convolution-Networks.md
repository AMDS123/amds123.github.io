---
layout: post
title: "Semantic Perceptual Image Compression using Deep Convolution Networks"
date: 2017-03-29 16:29:54
categories: arXiv_CV
tags: arXiv_CV Image_Caption Salient Object_Detection Deep_Learning Detection Recognition
author: Aaditya Prakash, Nick Moran, Solomon Garber, Antonella DiLillo, James Storer
mathjax: true
---

* content
{:toc}

##### Abstract
It has long been considered a significant problem to improve the visual quality of lossy image and video compression. Recent advances in computing power together with the availability of large training data sets has increased interest in the application of deep learning cnns to address image recognition and image processing tasks. Here, we present a powerful cnn tailored to the specific task of semantic image understanding to achieve higher visual quality in lossy compression. A modest increase in complexity is incorporated to the encoder which allows a standard, off-the-shelf jpeg decoder to be used. While jpeg encoding may be optimized for generic images, the process is ultimately unaware of the specific content of the image to be compressed. Our technique makes jpeg content-aware by designing and training a model to identify multiple semantic regions in a given image. Unlike object detection techniques, our model does not require labeling of object positions and is able to identify objects in a single pass. We present a new cnn architecture directed specifically to image compression, which generates a map that highlights semantically-salient regions so that they can be encoded at higher quality as compared to background regions. By adding a complete set of features for every class, and then taking a threshold over the sum of all feature activations, we generate a map that highlights semantically-salient regions so that they can be encoded at a better quality compared to background regions. Experiments are presented on the Kodak PhotoCD dataset and the MIT Saliency Benchmark dataset, in which our algorithm achieves higher visual quality for the same compressed size.

##### Abstract (translated by Google)
长期以来一直被认为是提高有损图像和视频压缩的视觉质量的重要问题。计算能力的最新进展以及大量训练数据集的可用性已经使深度学习cnns应用于图像识别和图像处理任务的兴趣增加。在这里，我们提出了一个强大的cnn量身定制的语义图像理解的具体任务，以达到更高的视觉质量在有损压缩。编码器中增加了适度的复杂性，允许使用标准的现成的jpeg解码器。尽管jpeg编码可以针对通用图像进行优化，但是该过程最终不知道要压缩的图像的具体内容。我们的技术通过设计和训练模型来识别给定图像中的多个语义区域，从而使jpeg内容感知。与对象检测技术不同，我们的模型不需要标记对象位置，并且能够一次识别对象。我们提出了一个专门针对图像压缩的新的cnn体系结构，该体系结构生成一个突出显示语义突出区域的地图，以便与背景区域相比，可以以更高的质量对其进行编码。通过为每个类添加一组完整的特征，然后对所有特征激活的总和进行阈值处理，我们生成一个突出显示语义突出区域的地图，以便与背景区域相比可以以更好的质量进行编码。柯达PhotoCD数据集和麻省理工学院显着性基准数据集提供了实验，其中我们的算法在相同压缩尺寸下获得更高的视觉质量。

##### URL
[https://arxiv.org/abs/1612.08712](https://arxiv.org/abs/1612.08712)

##### PDF
[https://arxiv.org/pdf/1612.08712](https://arxiv.org/pdf/1612.08712)

