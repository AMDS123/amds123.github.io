---
layout: post
title: "Deep-Learning for Tidemark Segmentation in Human Osteochondral Tissues Imaged with Micro-computed Tomography"
date: 2019-07-11 10:20:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Deep_Learning Quantitative
author: Aleksei Tiulpin, Mikko Finnil&#xe4;, Petri Lehenkari, Heikki J. Nieminen, Simo Saarakkala
mathjax: true
---

* content
{:toc}

##### Abstract
Three-dimensional (3D) semi-quantitative grading of pathological features in articular cartilage (AC) offers significant improvements in basic research of osteoarthritis (OA). We have earlier developed the 3D protocol for imaging of AC and its structures which includes staining of the sample with a contrast agent (phosphotungstic acid, PTA) and a consequent scanning with micro-computed tomography. Such a protocol was designed to provide X-ray attenuation contrast to visualize AC structure. However, at the same time, this protocol has one major disadvantage: the loss of contrast at the tidemark (calcified cartilage interface, CCI). An accurate segmentation of CCI can be very important for understanding the etiology of OA and ex-vivo evaluation of tidemark condition at early OA stages. In this paper, we present the first application of Deep Learning to PTA-stained osteochondral samples that allows to perform tidemark segmentation in a fully-automatic manner. Our method is based on U-Net trained using a combination of binary cross-entropy and soft Jaccard loss. On cross-validation, this approach yielded intersection over the union of 0.59, 0.70, 0.79, 0.83 and 0.86 within 15 {\mu}m, 30 {\mu}m, 45 {\mu}m, 60 {\mu}m and 75 {\mu}m padded zones around the tidemark, respectively. Our codes and the dataset that consisted of 35 PTA-stained human AC samples are made publicly available together with the segmentation masks to facilitate the development of biomedical image segmentation methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05089](http://arxiv.org/abs/1907.05089)

##### PDF
[http://arxiv.org/pdf/1907.05089](http://arxiv.org/pdf/1907.05089)

