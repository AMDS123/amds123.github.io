---
layout: post
title: "On-the-fly Network Pruning for Object Detection"
date: 2016-05-11 15:27:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Marc Masana, Joost van de Weijer, Andrew D. Bagdanov
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection with deep neural networks is often performed by passing a few thousand candidate bounding boxes through a deep neural network for each image. These bounding boxes are highly correlated since they originate from the same image. In this paper we investigate how to exploit feature occurrence at the image scale to prune the neural network which is subsequently applied to all bounding boxes. We show that removing units which have near-zero activation in the image allows us to significantly reduce the number of parameters in the network. Results on the PASCAL 2007 Object Detection Challenge demonstrate that up to 40% of units in some fully-connected layers can be entirely eliminated with little change in the detection result.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1605.03477](https://arxiv.org/abs/1605.03477)

##### PDF
[https://arxiv.org/pdf/1605.03477](https://arxiv.org/pdf/1605.03477)

