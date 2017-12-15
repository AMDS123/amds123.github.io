---
layout: post
title: "Marr Revisited: 2D-3D Alignment via Surface Normal Prediction"
date: 2016-04-05 17:51:39
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction
author: Aayush Bansal, Bryan Russell, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an approach that leverages surface normal predictions, along with appearance cues, to retrieve 3D models for objects depicted in 2D still images from a large CAD object library. Critical to the success of our approach is the ability to recover accurate surface normals for objects in the depicted scene. We introduce a skip-network model built on the pre-trained Oxford VGG convolutional neural network (CNN) for surface normal prediction. Our model achieves state-of-the-art accuracy on the NYUv2 RGB-D dataset for surface normal prediction, and recovers fine object detail compared to previous methods. Furthermore, we develop a two-stream network over the input image and predicted surface normals that jointly learns pose and style for CAD model retrieval. When using the predicted surface normals, our two-stream network matches prior work using surface normals computed from RGB-D images on the task of pose prediction, and achieves state of the art when using RGB-D input. Finally, our two-stream network allows us to retrieve CAD models that better match the style and pose of a depicted object compared with baseline approaches.

##### Abstract (translated by Google)
我们引入一种方法，利用曲面法线预测以及外观线索，从大型CAD对象库中检索2D静态图像中描绘的对象的3D模型。我们的方法成功的关键是能够恢复所描绘场景中物体的精确表面法线。我们引入一个建立在预先训练的牛津VGG卷积神经网络（CNN）上的跳过网络模型，用于表面正态预测。我们的模型在NYUv2 RGB-D数据集上实现了表面法线预测的最新精度，并且与以前的方法相比，可以恢复出精细的物体细节。此外，我们在输入图像和预测表面法线上开发了一个双流网络，共同学习CAD模型检索的姿态和风格。当使用预测的表面法线时，我们的双流网络使用从姿态预测任务中的RGB-D图像计算的表面法线来匹配先前的工作，并且实现当使用RGB-D输入时的现有技术水平。最后，我们的双流网络允许我们检索CAD模型，与基准线方法相比，更好地匹配描述对象的风格和姿势。

##### URL
[https://arxiv.org/abs/1604.01347](https://arxiv.org/abs/1604.01347)

##### PDF
[https://arxiv.org/pdf/1604.01347](https://arxiv.org/pdf/1604.01347)

