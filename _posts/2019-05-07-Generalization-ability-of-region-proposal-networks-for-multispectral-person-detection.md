---
layout: post
title: "Generalization ability of region proposal networks for multispectral person detection"
date: 2019-05-07 18:29:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Kevin Fritz, Daniel K&#xf6;nig, Ulrich Klauck, Michael Teutsch
mathjax: true
---

* content
{:toc}

##### Abstract
Multispectral person detection aims at automatically localizing humans in images that consist of multiple spectral bands. Usually, the visual-optical (VIS) and the thermal infrared (IR) spectra are combined to achieve higher robustness for person detection especially in insufficiently illuminated scenes. This paper focuses on analyzing existing detection approaches for their generalization ability. Generalization is a key feature for machine learning based detection algorithms that are supposed to perform well across different datasets. Inspired by recent literature regarding person detection in the VIS spectrum, we perform a cross-validation study to empirically determine the most promising dataset to train a well-generalizing detector. Therefore, we pick one reference Deep Convolutional Neural Network (DCNN) architecture and three different multispectral datasets. The Region Proposal Network (RPN) originally introduced for object detection within the popular Faster R-CNN is chosen as a reference DCNN. The reason is that a stand-alone RPN is able to serve as a competitive detector for two-class problems such as person detection. Furthermore, current state-of-the-art approaches initially apply an RPN followed by individual classifiers. The three considered datasets are the KAIST Multispectral Pedestrian Benchmark including recently published improved annotations for training and testing, the Tokyo Multi-spectral Semantic Segmentation dataset, and the OSU Color-Thermal dataset including recently released annotations. The experimental results show that the KAIST Multispectral Pedestrian Benchmark with its improved annotations provides the best basis to train a DCNN with good generalization ability compared to the other two multispectral datasets. On average, this detection model achieves a log-average Miss Rate (MR) of 29.74 % evaluated on the reasonable test subsets of the three datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02758](http://arxiv.org/abs/1905.02758)

##### PDF
[http://arxiv.org/pdf/1905.02758](http://arxiv.org/pdf/1905.02758)

