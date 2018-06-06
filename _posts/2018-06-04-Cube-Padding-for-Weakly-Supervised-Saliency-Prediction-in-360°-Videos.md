---
layout: post
title: "Cube Padding for Weakly-Supervised Saliency Prediction in 360° Videos"
date: 2018-06-04 18:42:37
categories: arXiv_CV
tags: arXiv_CV Salient Face CNN RNN Prediction
author: Hsien-Tzu Cheng, Chun-Hung Chao, Jin-Dong Dong, Hao-Kai Wen, Tyng-Luh Liu, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic saliency prediction in 360{\deg} videos is critical for viewpoint guidance applications (e.g., Facebook 360 Guide). We propose a spatial-temporal network which is (1) weakly-supervised trained and (2) tailor-made for 360{\deg} viewing sphere. Note that most existing methods are less scalable since they rely on annotated saliency map for training. Most importantly, they convert 360{\deg} sphere to 2D images (e.g., a single equirectangular image or multiple separate Normal Field-of-View (NFoV) images) which introduces distortion and image boundaries. In contrast, we propose a simple and effective Cube Padding (CP) technique as follows. Firstly, we render the 360{\deg} view on six faces of a cube using perspective projection. Thus, it introduces very little distortion. Then, we concatenate all six faces while utilizing the connectivity between faces on the cube for image padding (i.e., Cube Padding) in convolution, pooling, convolutional LSTM layers. In this way, CP introduces no image boundary while being applicable to almost all Convolutional Neural Network (CNN) structures. To evaluate our method, we propose Wild-360, a new 360{\deg} video saliency dataset, containing challenging videos with saliency heatmap annotations. In experiments, our method outperforms baseline methods in both speed and quality.

##### Abstract (translated by Google)
360度视频中的自动显着性预测对视点引导应用（例如Facebook 360指南）至关重要。我们提出了一个时空网络，它是（1）弱监督训练和（2）为360度视角定制的。请注意，大多数现有方法的可伸缩性较差，因为它们依赖注释的显着图进行训练。最重要的是，它们将360°球变换成2D图像（例如，单个等轴矩形图像或多个单独的正常视场（NFoV）图像），其引入失真和图像边界。相反，我们提出了一种简单而有效的立方体填充（CP）技术，如下所示。首先，我们使用透视投影在立方体的六个面上渲染360 {\ deg}视图。因此，它引入了很少的失真。然后，我们连接所有六个面，同时利用立方体上的面之间的连通性进行卷积，合并，卷积LSTM层中的图像填充（即，立方体填充）。通过这种方式，CP不引入图像边界，同时适用于几乎所有的卷积神经网络（CNN）结构。为了评估我们的方法，我们提出了Wild 360，一个全新的360度视频显着数据集，其中包含带有显着热图注解的具有挑战性的视频。在实验中，我们的方法在速度和质量上均优于基准方法。

##### URL
[https://arxiv.org/abs/1806.01320](https://arxiv.org/abs/1806.01320)

##### PDF
[https://arxiv.org/pdf/1806.01320](https://arxiv.org/pdf/1806.01320)

