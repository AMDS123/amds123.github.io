---
layout: post
title: "Weakly-supervised Disentangling with Recurrent Transformations for 3D View Synthesis"
date: 2016-01-05 00:08:09
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Prediction
author: Jimei Yang, Scott Reed, Ming-Hsuan Yang, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
An important problem for both graphics and vision is to synthesize novel views of a 3D object from a single image. This is particularly challenging due to the partial observability inherent in projecting a 3D object onto the image space, and the ill-posedness of inferring object shape and pose. However, we can train a neural network to address the problem if we restrict our attention to specific object categories (in our case faces and chairs) for which we can gather ample training data. In this paper, we propose a novel recurrent convolutional encoder-decoder network that is trained end-to-end on the task of rendering rotated objects starting from a single image. The recurrent structure allows our model to capture long-term dependencies along a sequence of transformations. We demonstrate the quality of its predictions for human faces on the Multi-PIE dataset and for a dataset of 3D chair models, and also show its ability to disentangle latent factors of variation (e.g., identity and pose) without using full supervision.

##### Abstract (translated by Google)
图形和视觉的一个重要问题是从单个图像合成3D对象的新视图。由于将3D对象投影到图像空间所固有的部分可观测性以及推断对象形状和姿势的不适宜性，这是特别具有挑战性的。但是，如果我们将注意力集中在特定的对象类别（在我们的例子中是面孔和椅子），我们可以训练一个神经网络来解决这个问题，我们可以收集足够的训练数据。在本文中，我们提出了一种新颖的循环卷积编码器 - 解码器网络，该网络在从单个图像开始渲染旋转对象的任务中被端对端地训练。循环结构允许我们的模型沿着一系列变换捕捉长期依赖关系。我们在Multi-PIE数据集和3D椅子模型的数据集上展示了它对人脸预测的质量，并且还显示了它能够在不使用全面监督的情况下分解变化的潜在因素（例如身份和姿势）。

##### URL
[https://arxiv.org/abs/1601.00706](https://arxiv.org/abs/1601.00706)

##### PDF
[https://arxiv.org/pdf/1601.00706](https://arxiv.org/pdf/1601.00706)

