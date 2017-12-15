---
layout: post
title: "Pairwise Decomposition of Image Sequences for Active Multi-View Recognition"
date: 2016-05-26 16:44:19
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation Recognition
author: Edward Johns, Stefan Leutenegger, Andrew J. Davison
mathjax: true
---

* content
{:toc}

##### Abstract
A multi-view image sequence provides a much richer capacity for object recognition than from a single image. However, most existing solutions to multi-view recognition typically adopt hand-crafted, model-based geometric methods, which do not readily embrace recent trends in deep learning. We propose to bring Convolutional Neural Networks to generic multi-view recognition, by decomposing an image sequence into a set of image pairs, classifying each pair independently, and then learning an object classifier by weighting the contribution of each pair. This allows for recognition over arbitrary camera trajectories, without requiring explicit training over the potentially infinite number of camera paths and lengths. Building these pairwise relationships then naturally extends to the next-best-view problem in an active recognition framework. To achieve this, we train a second Convolutional Neural Network to map directly from an observed image to next viewpoint. Finally, we incorporate this into a trajectory optimisation task, whereby the best recognition confidence is sought for a given trajectory length. We present state-of-the-art results in both guided and unguided multi-view recognition on the ModelNet dataset, and show how our method can be used with depth images, greyscale images, or both.

##### Abstract (translated by Google)
多视点图像序列提供了比单个图像更丰富的物体识别能力。然而，大多数现有的多视图识别解决方案通常采用手工制作的基于模型的几何方法，这些方法不容易接受最近的深度学习趋势。我们提出通过将图像序列分解成一组图像对，独立地对每一对进行分类，然后通过对每对的贡献进行加权来学习对象分类器，来将卷积神经网络引入通用多视图识别。这允许在任意摄像机轨迹上进行识别，而不需要对潜在的无限数量的摄像机路径和长度进行显式训练。建立这些成对的关系，自然会延伸到主动识别框架中的下一个最佳视图问题。为了达到这个目的，我们训练第二个卷积神经网络，从观察图像直接映射到下一个视点。最后，我们将其纳入到轨迹优化任务中，从而针对给定轨迹长度寻求最佳识别置信度。我们在ModelNet数据集中提供了引导式和非引导式多视图识别的最新成果，并展示了我们的方法如何与深度图像，灰度图像或两者一起使用。

##### URL
[https://arxiv.org/abs/1605.08359](https://arxiv.org/abs/1605.08359)

##### PDF
[https://arxiv.org/pdf/1605.08359](https://arxiv.org/pdf/1605.08359)

