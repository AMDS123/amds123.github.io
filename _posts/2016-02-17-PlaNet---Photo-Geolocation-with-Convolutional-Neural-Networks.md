---
layout: post
title: "PlaNet - Photo Geolocation with Convolutional Neural Networks"
date: 2016-02-17 06:27:55
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Face CNN RNN Classification
author: Tobias Weyand, Ilya Kostrikov, James Philbin
mathjax: true
---

* content
{:toc}

##### Abstract
Is it possible to build a system to determine the location where a photo was taken using just its pixels? In general, the problem seems exceptionally difficult: it is trivial to construct situations where no location can be inferred. Yet images often contain informative cues such as landmarks, weather patterns, vegetation, road markings, and architectural details, which in combination may allow one to determine an approximate location and occasionally an exact location. Websites such as GeoGuessr and View from your Window suggest that humans are relatively good at integrating these cues to geolocate images, especially en-masse. In computer vision, the photo geolocation problem is usually approached using image retrieval methods. In contrast, we pose the problem as one of classification by subdividing the surface of the earth into thousands of multi-scale geographic cells, and train a deep network using millions of geotagged images. While previous approaches only recognize landmarks or perform approximate matching using global image descriptors, our model is able to use and integrate multiple visible cues. We show that the resulting model, called PlaNet, outperforms previous approaches and even attains superhuman levels of accuracy in some cases. Moreover, we extend our model to photo albums by combining it with a long short-term memory (LSTM) architecture. By learning to exploit temporal coherence to geolocate uncertain photos, we demonstrate that this model achieves a 50% performance improvement over the single-image model.

##### Abstract (translated by Google)
是否有可能建立一个系统，以确定使用其像素的照片拍摄的位置？一般来说，这个问题看起来非常困难：构建不能推断位置的情况是微不足道的。然而，图像通常包含信息提示，如地标，天气模式，植被，道路标记和建筑细节，这些信息组合可以允许人们确定大概的位置，偶尔确定确切的位置。诸如GeoGuessr之类的网站和来自你的窗口的视图表明，人类相对擅长整合这些线索来定位图像，尤其是集体的。在计算机视觉中，通常使用图像检索方法来处理照片地理定位问题。相反，我们将问题归结为将地球表面细分为数千个多尺度地理单元，并使用数以百万计的地理标记图像训练深度网络。虽然以前的方法只识别地标或使用全局图像描述符进行近似匹配，但是我们的模型能够使用并集成多个可见线索。我们表明，所产生的模型，称为PlaNet，胜过以前的方法，甚至在某些情况下达到超人的准确度。此外，我们将模型扩展到相册，将其与长期短期记忆（LSTM）架构相结合。通过学习利用时间一致性来定位不确定的照片，我们证明这个模型比单一图像模型的性能提高了50％。

##### URL
[https://arxiv.org/abs/1602.05314](https://arxiv.org/abs/1602.05314)

##### PDF
[https://arxiv.org/pdf/1602.05314](https://arxiv.org/pdf/1602.05314)

