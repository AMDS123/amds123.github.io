---
layout: post
title: "Wide Field Imaging. I. Applications of Neural Networks to object detection and star/galaxy classification"
date: 2000-06-08 16:34:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: S. Andreon (1), G. Gargiulo (2,3), G. Longo (1), R. Tagliaferri (4,5), N. Capuano (2) ((1) Oss. Astron. Capodimonte, (2) Univ. Salerno, (3) IIASS, (4) DMI, Univ. Salerno, (5) INFM, Univ. Salerno)
mathjax: true
---

* content
{:toc}

##### Abstract
[Abriged] Astronomical Wide Field Imaging performed with new large format CCD detectors poses data reduction problems of unprecedented scale which are difficult to deal with traditional interactive tools. We present here NExt (Neural Extractor): a new Neural Network (NN) based package capable to detect objects and to perform both deblending and star/galaxy classification in an automatic way. Traditionally, in astronomical images, objects are first discriminated from the noisy background by searching for sets of connected pixels having brightnesses above a given threshold and then they are classified as stars or as galaxies through diagnostic diagrams having variables choosen accordingly to the astronomer's taste and experience. In the extraction step, assuming that images are well sampled, NExt requires only the simplest a priori definition of "what an object is" (id est, it keeps all structures composed by more than one pixels) and performs the detection via an unsupervised NN approaching detection as a clustering problem which has been thoroughly studied in the artificial intelligence literature. In order to obtain an objective and reliable classification, instead of using an arbitrarily defined set of features, we use a NN to select the most significant features among the large number of measured ones, and then we use their selected features to perform the classification task. In order to optimise the performances of the system we implemented and tested several different models of NN. The comparison of the NExt performances with those of the best detection and classification package known to the authors (SExtractor) shows that NExt is at least as effective as the best traditional packages.

##### Abstract (translated by Google)
天文学研究表明，新型大尺寸CCD探测器的天文宽视场成像技术具有前所未有的数据缩减问题，难以处理传统的互动工具。我们在这里介绍NExt（神经提取器）：一个新的基于神经网络（NN）的包能够检测对象，并执行deblending和星/银河分类自动的方式。传统上，在天文图像中，首先通过搜索具有高于给定阈值的亮度的连接像素集来区分噪声背景，然后通过具有根据天文学家的口味和体验选择的变量的诊断图将其分类为恒星或星系。在提取步骤中，假设图像被很好地采样，NExt只需要最简单的“什么是对象”的先验定义（id est，它保留由多于一个像素组成的所有结构），并且通过无监督的NN接近检测作为一个已经在人工智能文献中被彻底研究过的聚类问题。为了得到一个客观可靠的分类结果，我们使用一个神经网络来选择大量测量数据中的最重要的特征，而不是使用任意定义的特征集合，然后用他们选择的特征来执行分类任务。为了优化系统的性能，我们实现并测试了几种不同的神经网络模型。 NExt性能与作者所知的最佳检测和分类软件包（SExtractor）的性能比较表明，NExt至少和最好的传统软件包一样有效。

##### URL
[https://arxiv.org/abs/astro-ph/0006115](https://arxiv.org/abs/astro-ph/0006115)

##### PDF
[https://arxiv.org/pdf/astro-ph/0006115](https://arxiv.org/pdf/astro-ph/0006115)

