---
layout: post
title: "Variational Saccading: Efficient Inference for Large Resolution Images"
date: 2019-05-10 14:53:06
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification Relation
author: Jason Ramapuram, Frantzeska Lavda, Maurits Diephuis, Russ Webb, Alexandros Kalousis
mathjax: true
---

* content
{:toc}

##### Abstract
Image classification with deep neural networks is typically restricted to images of small dimensionality such as 224 x 244 in Resnet models [24]. This limitation excludes the 4000 x 3000 dimensional images that are taken by modern smartphone cameras and smart devices. In this work, we aim to mitigate the prohibitive inferential and memory costs of operating in such large dimensional spaces. To sample from the high-resolution original input distribution, we propose using a smaller proxy distribution to learn the co-ordinates that correspond to regions of interest in the high-dimensional space. We introduce a new principled variational lower bound that captures the relationship of the proxy distribution's posterior and the original image's co-ordinate space in a way that maximizes the conditional classification likelihood. We empirically demonstrate on one synthetic benchmark and one real world large resolution DSLR camera image dataset that our method produces comparable results with ~10x faster inference and lower memory consumption than a model that utilizes the entire original input distribution. Finally, we experiment with a more complex setting using mini-maps from Starcraft II [56] to infer the number of characters in a complex 3d-rendered scene. Even in such complicated scenes our model provides strong localization: a feature missing from traditional classification models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03170](http://arxiv.org/abs/1812.03170)

##### PDF
[http://arxiv.org/pdf/1812.03170](http://arxiv.org/pdf/1812.03170)

