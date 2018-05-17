---
layout: post
title: "Automated Vision-based Bridge Component Extraction Using Multiscale Convolutional Neural Networks"
date: 2018-05-15 21:40:34
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection Recognition
author: Yasutaka Narazaki, Vedhus Hoskere, Tu A. Hoang, Billie F. Spencer Jr
mathjax: true
---

* content
{:toc}

##### Abstract
Image data has a great potential of helping post-earthquake visual inspections of civil engineering structures due to the ease of data acquisition and the advantages in capturing visual information. A variety of techniques have been applied to detect damages automatically from a close-up image of a structural component. However, the application of the automatic damage detection methods become increasingly difficult when the image includes multiple components from different structures. To reduce the inaccurate false positive alarms, critical structural components need to be recognized first, and the damage alarms need to be cleaned using the component recognition results. To achieve the goal, this study aims at recognizing and extracting bridge components from images of urban scenes. The bridge component recognition begins with pixel-wise classifications of an image into 10 scene classes. Then, the original image and the scene classification results are combined to classify the image pixels into five component classes. The multi-scale convolutional neural networks (multi-scale CNNs) are used to perform pixel-wise classification, and the classification results are post-processed by averaging within superpixels and smoothing by conditional random fields (CRFs). The performance of the bridge component extraction is tested in terms of accuracy and consistency.

##### Abstract (translated by Google)
由于数据采集的简便性和捕获视觉信息的优势，图像数据很有可能帮助土木工程结构进行震后视觉检查。已应用各种技术从结构部件的特写图像中自动检测损坏。然而，当图像包含来自不同结构的多个部件时，自动损伤检测方法的应用变得越来越困难。为了减少不准确的误报警，首先需要识别关键结构部件，并且需要使用部件识别结果来清理损坏报警。为了实现这一目标，本研究旨在从城市场景图像中识别和提取桥梁组件。桥组件识别开始于一个图像按像素分类为10个场景类。然后，将原始图像和场景分类结果组合以将图像像素分类为五个组分类别。多尺度卷积神经网络（多尺度CNN）被用于执行逐像素分类，并且通过在超像素内进行平均并且通过条件随机场（CRF）进行平滑来对分类结果进行后处理。根据准确性和一致性测试桥梁构件提取的性能。

##### URL
[http://arxiv.org/abs/1805.06042](http://arxiv.org/abs/1805.06042)

##### PDF
[http://arxiv.org/pdf/1805.06042](http://arxiv.org/pdf/1805.06042)

