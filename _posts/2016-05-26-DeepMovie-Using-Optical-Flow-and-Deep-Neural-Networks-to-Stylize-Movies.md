---
layout: post
title: "DeepMovie: Using Optical Flow and Deep Neural Networks to Stylize Movies"
date: 2016-05-26 05:52:10
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Optimization
author: Alexander G. Anderson, Cory P. Berg, Daniel P. Mossing, Bruno A. Olshausen
mathjax: true
---

* content
{:toc}

##### Abstract
A recent paper by Gatys et al. describes a method for rendering an image in the style of another image. First, they use convolutional neural network features to build a statistical model for the style of an image. Then they create a new image with the content of one image but the style statistics of another image. Here, we extend this method to render a movie in a given artistic style. The naive solution that independently renders each frame produces poor results because the features of the style move substantially from one frame to the next. The other naive method that initializes the optimization for the next frame using the rendered version of the previous frame also produces poor results because the features of the texture stay fixed relative to the frame of the movie instead of moving with objects in the scene. The main contribution of this paper is to use optical flow to initialize the style transfer optimization so that the texture features move with the objects in the video. Finally, we suggest a method to incorporate optical flow explicitly into the cost function.

##### Abstract (translated by Google)
Gatys等人最近的一篇论文描述了以另一图像的样式呈现图像的方法。首先，他们使用卷积神经网络功能来建立一个图像风格的统计模型。然后，他们创建一个图像的内容，但另一个图像的风格统计的新形象。在这里，我们扩展这种方法来呈现给定的艺术风格的电影。独立渲染每一帧的天真的解决方案产生不佳的结果，因为样式的特征基本上从一帧移动到下一帧。使用前一帧的渲染版本来初始化下一帧的优化的另一种幼稚方法也产生差的结果，因为纹理的特征相对于电影的帧保持固定，而不是与场景中的对象一起移动。本文的主要贡献是利用光流初始化样式转换优化，使纹理特征随视频中的物体移动。最后，我们建议一种将光流明确纳入成本函数的方法。

##### URL
[https://arxiv.org/abs/1605.08153](https://arxiv.org/abs/1605.08153)

##### PDF
[https://arxiv.org/pdf/1605.08153](https://arxiv.org/pdf/1605.08153)

