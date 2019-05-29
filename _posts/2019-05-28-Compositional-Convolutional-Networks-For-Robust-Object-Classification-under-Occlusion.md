---
layout: post
title: "Compositional Convolutional Networks For Robust Object Classification under Occlusion"
date: 2019-05-28 14:03:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Deep_Learning Prediction Detection
author: Adam Kortylewski, Qing Liu, Huiyu Wang, Zhishuai Zhang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (DCNNs) are powerful models that yield impressive results at object classification. However, recent work has shown that they do not generalize well to partially occluded objects and to mask attacks. In contrast to DCNNs, compositional models are robust to partial occlusion, however, they are not as discriminative as deep this http URL this work, we integrate DCNNs and compositional object models to retain the best of both approaches: a discriminative model that is robust to partial occlusion and mask attacks. Our model is learned in two steps. First, a standard DCNN is trained for image classification. Subsequently, we cluster the DCNN features into dictionaries. We show that the dictionary components resemble object part detectors and learn the spatial distribution of parts for each object class. We propose mixtures of compositional models to account for large changes in the spatial activation patterns (e.g. due to changes in the 3D pose of an object). At runtime, an image is first classified by the DCNN in a feedforward manner. The prediction uncertainty is used to detect partially occluded objects, which in turn are classified by the compositional model. Our experimental results demonstrate that such compositional convolutional networks resolve a fundamental problem of current deep learning approaches to computer vision: They recognize occluded objects with exceptional performance, even when they have not been exposed to occluded objects during training, while at the same time maintaining high discriminative performance for non-occluded objects.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11826](https://arxiv.org/abs/1905.11826)

##### PDF
[https://arxiv.org/pdf/1905.11826](https://arxiv.org/pdf/1905.11826)

