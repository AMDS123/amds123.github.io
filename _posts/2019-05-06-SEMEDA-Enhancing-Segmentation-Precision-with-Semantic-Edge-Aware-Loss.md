---
layout: post
title: "SEMEDA: Enhancing Segmentation Precision with Semantic Edge Aware Loss"
date: 2019-05-06 09:14:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction Detection
author: Yifu Chen, Arnaud Dapogny, Matthieu Cord
mathjax: true
---

* content
{:toc}

##### Abstract
While nowadays deep neural networks achieve impressive performances on semantic segmentation tasks, they are usually trained by optimizing pixel-wise losses such as cross-entropy. As a result, the predictions outputted by such networks usually struggle to accurately capture the object boundaries and exhibit holes inside the objects. In this paper, we propose a novel approach to improve the structure of the predicted segmentation masks. We introduce a novel semantic edge detection network, which allows to match the predicted and ground truth segmentation masks. This Semantic Edge-Aware strategy (SEMEDA) can be combined with any backbone deep network in an end-to-end training framework. Through thorough experimental validation on Pascal VOC 2012 and Cityscapes datasets, we show that the proposed SEMEDA approach enhances the structure of the predicted segmentation masks by enforcing sharp boundaries and avoiding discontinuities inside objects, improving the segmentation performance. In addition, our semantic edge-aware loss can be integrated into any popular segmentation network without requiring any additional annotation and with negligible computational load, as compared to standard pixel-wise cross-entropy loss.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01892](http://arxiv.org/abs/1905.01892)

##### PDF
[http://arxiv.org/pdf/1905.01892](http://arxiv.org/pdf/1905.01892)

