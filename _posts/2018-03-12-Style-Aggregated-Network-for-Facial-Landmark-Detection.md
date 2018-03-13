---
layout: post
title: "Style Aggregated Network for Facial Landmark Detection"
date: 2018-03-12 03:46:12
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Face Detection
author: Xuanyi Dong, Yan Yan, Wanli Ouyang, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in facial landmark detection achieve success by learning discriminative features from rich deformation of face shapes and poses. Besides the variance of faces themselves, the intrinsic variance of image styles, e.g., grayscale vs. color images, light vs. dark, intense vs. dull, and so on, has constantly been overlooked. This issue becomes inevitable as increasing web images are collected from various sources for training neural networks. In this work, we propose a style-aggregated approach to deal with the large intrinsic variance of image styles for facial landmark detection. Our method transforms original face images to style-aggregated images by a generative adversarial module. The proposed scheme uses the style-aggregated image to maintain face images that are more robust to environmental changes. Then the original face images accompanying with style-aggregated ones play a duet to train a landmark detector which is complementary to each other. In this way, for each face, our method takes two images as input, i.e., one in its original style and the other in the aggregated style. In experiments, we observe that the large variance of image styles would degenerate the performance of facial landmark detectors. Moreover, we show the robustness of our method to the large variance of image styles by comparing to a variant of our approach, in which the generative adversarial module is removed, and no style-aggregated images are used. Our approach is demonstrated to perform well when compared with state-of-the-art algorithms on benchmark datasets AFLW and 300-W. Code is publicly available on GitHub: this https URL

##### Abstract (translated by Google)
通过从脸部形状和姿势的丰富变形中学习辨别特征来实现面部标志检测的最新进展。除了脸部本身的变化之外，图像风格的固有变化（例如，灰度与彩色图像，光与黑，强与钝等）一直被忽视。随着越来越多的Web图像从各种来源收集用于训练神经网络，这个问题变得不可避免。在这项工作中，我们提出了一种风格聚合方法来处理面部标志检测的图像样式的大内在变化。我们的方法通过生成对抗模块将原始人脸图像转换为风格聚合图像。所提出的方案使用风格聚合图像来维护对环境变化更稳健的人脸图像。然后，伴随着风格聚合的原始人脸图像进行二重奏训练，以训练彼此互补的具有里程碑意义的探测器。通过这种方式，对于每张脸，我们的方法以两张图像作为输入，即一张为原始样式，另一张为汇总样式。在实验中，我们观察到图像样式的大变化会使面部标志检测器的性能退化。此外，我们通过与我们的方法的变体进行比较，显示了我们的方法对图像样式的巨大变化的鲁棒性，其中生成的对抗模块被移除，并且不使用样式聚集的图像。与基准数据集AFLW和300-W的最新算法相比，我们的方法表现出色。代码在GitHub上公开发布：此https网址

##### URL
[https://arxiv.org/abs/1803.04108](https://arxiv.org/abs/1803.04108)

##### PDF
[https://arxiv.org/pdf/1803.04108](https://arxiv.org/pdf/1803.04108)

