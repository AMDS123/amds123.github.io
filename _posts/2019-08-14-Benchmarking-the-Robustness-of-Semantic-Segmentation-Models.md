---
layout: post
title: "Benchmarking the Robustness of Semantic Segmentation Models"
date: 2019-08-14 07:51:56
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Semantic_Segmentation Classification Prediction
author: Christoph Kamann, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
When designing a semantic segmentation module for a practical application, such as autonomous driving, it is crucial to understand the robustness of the module with respect to a wide range of image corruptions. While there are recent robustness studies for full-image classification, we are the first to present an exhaustive study for semantic segmentation, based on the state-of-the-art model DeepLabv3$+$. To increase the realism of our study, we utilize almost 200,000 images generated from Cityscapes and PASCAL VOC 2012, and we furthermore present a realistic noise model, imitating HDR camera noise. Based on the benchmark study we gain several new insights. Firstly, model robustness increases with model performance, in most cases. Secondly, some architecture properties affect robustness significantly, such as a Dense Prediction Cell which was designed to maximize performance on clean data only. Thirdly, to achieve good generalization with respect to various types of image noise, it is recommended to train DeepLabv3+ with our realistic noise model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05005](http://arxiv.org/abs/1908.05005)

##### PDF
[http://arxiv.org/pdf/1908.05005](http://arxiv.org/pdf/1908.05005)

