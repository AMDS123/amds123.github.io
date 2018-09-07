---
layout: post
title: "3D Surface Reconstruction by Pointillism"
date: 2018-09-06 14:11:50
categories: arXiv_CV
tags: arXiv_CV Face
author: Olivia Wiles, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this work is to infer the 3D shape of an object from a single image. We use sculptures as our training and test bed, as these have great variety in shape and appearance. To achieve this we build on the success of multiple view geometry which is able to accurately provide correspondences between images of 3D objects under varying viewpoint and illumination conditions, and make the following contributions: first, we introduce a new loss function that can harness image-to-image correspondences to provide a supervisory signal to train a deep network to infer a depth map. The network is trained end-to-end by differentiating through the camera. Second, we develop a processing pipeline to automatically generate a very large scale multi-view set of correspondences for training the network. Finally, we demonstrate that we can indeed obtain a depth map of a novel object from a single image for a variety of sculptures with varying shape and texture, and that the network generalises at test time to new domains, such as synthetic data.

##### Abstract (translated by Google)
这项工作的目的是从单个图像推断对象的3D形状。我们使用雕塑作为我们的训练和测试床，因为它们在形状和外观上有很多种。为了实现这一目标，我们建立了多视图几何的成功，它能够在不同的视点和照明条件下准确地提供3D对象的图像之间的对应关系，并做出以下贡献：首先，我们引入了一个可以利用图像的新的损失函数 - 图像对应以提供监督信号以训练深度网络以推断深度图。通过相机进行区分，对网络进行端到端的培训。其次，我们开发了一个处理流水线，以自动生成一个非常大规模的多视图对应集，用于训练网络。最后，我们证明了我们确实可以从单个图像中获得具有不同形状和纹理的各种雕塑的新对象的深度图，并且网络在测试时将其推广到新的域，例如合成数据。

##### URL
[http://arxiv.org/abs/1809.02002](http://arxiv.org/abs/1809.02002)

##### PDF
[http://arxiv.org/pdf/1809.02002](http://arxiv.org/pdf/1809.02002)

