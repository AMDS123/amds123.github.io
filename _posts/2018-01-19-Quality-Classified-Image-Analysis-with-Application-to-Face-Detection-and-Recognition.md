---
layout: post
title: "Quality Classified Image Analysis with Application to Face Detection and Recognition"
date: 2018-01-19 15:18:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection Recognition
author: Fei Yang, Qian Zhang, Miaohui Wang, Guoping Qiu
mathjax: true
---

* content
{:toc}

##### Abstract
Motion blur, out of focus, insufficient spatial resolution, lossy compression and many other factors can all cause an image to have poor quality. However, image quality is a largely ignored issue in traditional pattern recognition literature. In this paper, we use face detection and recognition as case studies to show that image quality is an essential factor which will affect the performances of traditional algorithms. We demonstrated that it is not the image quality itself that is the most important, but rather the quality of the images in the training set should have similar quality as those in the testing set. To handle real-world application scenarios where images with different kinds and severities of degradation can be presented to the system, we have developed a quality classified image analysis framework to deal with images of mixed qualities adaptively. We use deep neural networks first to classify images based on their quality classes and then design a separate face detector and recognizer for images in each quality class. We will present experimental results to show that our quality classified framework can accurately classify images based on the type and severity of image degradations and can significantly boost the performances of state-of-the-art face detector and recognizer in dealing with image datasets containing mixed quality images.

##### Abstract (translated by Google)
运动模糊，失焦，空间分辨率不足，有损压缩等诸多因素都可能导致图像质量差。然而，图像质量在传统的模式识别文献中是一个很大的忽略问题。本文以人脸检测和识别为例，说明图像质量是影响传统算法性能的关键因素。我们证明，最重要的不是图像质量本身，而是训练集中图像的质量应该与测试集中的图像具有相似的质量。为了处理现实世界的应用场景，将具有不同种类和不同严重程度的图像呈现给系统，我们开发了一个质量分类图像分析框架，以自适应地处理混合图像。我们首先使用深度神经网络来根据图像的质量类别对图像进行分类，然后为每个质量类别的图像设计一个单独的人脸检测器和识别器。我们将给出实验结果，表明我们的质量分类框架可以根据图像劣化的类型和严重程度准确地对图像进行分类，并且可以显着提高最先进的人脸检测器和识别器在处理包含混合的图像数据集时的性能质量的图像。

##### URL
[http://arxiv.org/abs/1801.06445](http://arxiv.org/abs/1801.06445)

##### PDF
[http://arxiv.org/pdf/1801.06445](http://arxiv.org/pdf/1801.06445)

