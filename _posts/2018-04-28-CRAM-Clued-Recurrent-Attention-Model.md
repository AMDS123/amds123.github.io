---
layout: post
title: "CRAM: Clued Recurrent Attention Model"
date: 2018-04-28 19:27:43
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Image_Classification Classification
author: Minki Chung, Sungzoon Cho
mathjax: true
---

* content
{:toc}

##### Abstract
To overcome the poor scalability of convolutional neural network, recurrent attention model(RAM) selectively choose what and where to look on the image. By directing recurrent attention model how to look the image, RAM can be even more successful in that the given clue narrow down the scope of the possible focus zone. In this perspective, this work proposes clued recurrent attention model (CRAM) which add clue or constraint on the RAM better problem solving. CRAM follows encoder-decoder framework, encoder utilizes recurrent attention model with spatial transformer network and decoder which varies depending on the task. To ensure the performance, CRAM tackles two computer vision task. One is the image classification task, with clue given as the binary image saliency which indicates the approximate location of object. The other is the inpainting task, with clue given as binary mask which indicates the occluded part. In both tasks, CRAM shows better performance than existing methods showing the successful extension of RAM.

##### Abstract (translated by Google)
为了克服卷积神经网络较差的可伸缩性，经常性注意模型（RAM）选择性地选择在图像上看什么和在哪里看。通过引导经常性关注模型如何看待图像，RAM可以更加成功，因为给定的线索缩小了可能关注区域的范围。从这个角度来看，这项工作提出了线索经常性注意模型（CRAM），它增加了对RAM更好的问题解决的线索或约束。 CRAM遵循编码器 - 解码器框架，编码器利用随着任务而变化的空间变换器网络和解码器的经常性关注模型。为确保性能，CRAM解决了两项计算机视觉任务。一个是图像分类任务，线索给出为二值图像显着性，表示对象的大致位置。另一个是修补任务，将线索作为表示被遮挡部分的二进制掩码给出。在这两项任务中，CRAM显示比现有方法更好的性能，显示RAM的成功扩展。

##### URL
[https://arxiv.org/abs/1804.10844](https://arxiv.org/abs/1804.10844)

##### PDF
[https://arxiv.org/pdf/1804.10844](https://arxiv.org/pdf/1804.10844)

