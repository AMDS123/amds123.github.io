---
layout: post
title: "Crowd Counting by Adaptively Fusing Predictions from an Image Pyramid"
date: 2018-05-16 03:27:02
categories: arXiv_CV
tags: arXiv_CV Attention CNN Prediction
author: Di Kang, Antoni Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Because of the powerful learning capability of deep neural networks, counting performance via density map estimation has improved significantly during the past several years. However, it is still very challenging due to severe occlusion, large scale variations, and perspective distortion. Scale variations (from image to image) coupled with perspective distortion (within one image) resulting in huge scale changes of the object size. Earlier methods based on convolutional neural networks (CNN) typically did not handle this scale variation explicitly, until Hydra-CNN and MCNN. MCNN uses three columns, each with different filter sizes, to extract features at different scales. In this paper, in contrast to using filters of different sizes, we utilize an image pyramid to deal with scale variations. It is more effective and efficient to resize the input fed into the network, as compared to using larger filter sizes. Secondly, we adaptively fuse the predictions from different scales (using adaptively changing per-pixel weights), which makes our method adapt to scale changes within an image. The adaptive fusing is achieved by generating an across-scale attention map, which softly selects a suitable scale for each pixel, followed by a 1x1 convolution. Extensive experiments on three popular datasets show very compelling results.

##### Abstract (translated by Google)
由于深度神经网络的强大学习能力，在过去几年中，通过密度图估计的计数性能得到了显着提高。但是，由于严重的遮挡，大范围变化和透视失真，它仍然非常具有挑战性。尺度变化（从图像到图像）与透视畸变（在一个图像内）相结合，导致对象尺寸的巨大变化。早期的基于卷积神经网络（CNN）的方法通常没有明确处理这种尺度变化，直到Hydra-CNN和MCNN。 MCNN使用三列，每列都具有不同的过滤器大小，以不同比例提取特征。在本文中，与使用不同尺寸的滤镜相比，我们利用图像金字塔来处理尺度变化。与使用更大的过滤器尺寸相比，调整馈送到网络中的输入的尺寸更有效和高效。其次，我们自适应地融合不同尺度的预测（使用自适应改变的每像素权重），这使得我们的方法适应图像内的尺度变化。自适应融合是通过生成跨尺度关注映射来实现的，该映射为每个像素轻松选择合适的尺度，然后进行1x1卷积。对三个流行数据集的广泛实验显示出非常令人信服的结果。

##### URL
[http://arxiv.org/abs/1805.06115](http://arxiv.org/abs/1805.06115)

##### PDF
[http://arxiv.org/pdf/1805.06115](http://arxiv.org/pdf/1805.06115)

