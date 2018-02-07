---
layout: post
title: "Multi-Temporal Land Cover Classification with Sequential Recurrent Encoders"
date: 2018-02-06 17:13:05
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition CNN Classification Recognition
author: Marc Ru&#xdf;wurm, Marco K&#xf6;rner
mathjax: true
---

* content
{:toc}

##### Abstract
Earth observation (EO) sensors deliver data with daily or weekly temporal resolution. Most land use and land cover (LULC) approaches, however, expect cloud-free and mono-temporal observations. The increasing temporal capabilities of today's sensors enables the use of temporal, along with spectral and spatial features. Domains, such as speech recognition or neural machine translation, work with inherently temporal data and, today, achieve impressive results using sequential encoder-decoder structures. Inspired by these sequence-to-sequence models, we adapt an encoder structure with convolutional recurrent layers in order to approximate a phenological model for vegetation classes based on a temporal sequence of Sentinel 2 (S2) images. In our experiments, we visualize internal activations over a sequence of cloudy and non-cloudy images and find several recurrent cells, which reduce the input activity for cloudy observations. Hence, we assume that our network has learned cloud-filtering schemes solely from input data, which could alleviate the need for tedious cloud-filtering as a preprocessing step for many EO approaches. Moreover, using unfiltered temporal series of top-of-atmosphere (TOA) reflectance data, we achieved in our experiments state-of-the-art classification accuracies on a large number of crop classes with minimal preprocessing compared to other classification approaches.

##### Abstract (translated by Google)
地球观测（EO）传感器以每日或每周时间分辨率传输数据。然而，大多数土地利用和土地覆盖（LULC）方法都期望无云和单一时间观测。当今传感器日益增长的时间能力使得时间的使用以及光谱和空间特征成为可能。语音识别或神经机器翻译等领域的工作与固有的时间数据，今天，使用顺序编码器 - 解码器结构，实现令人印象深刻的结果。受这些序列 - 序列模型的启发，我们使用卷积递归层来调整编码器结构，以基于Sentinel 2（S2）图像的时间序列逼近植被类别的物候模型。在我们的实验中，我们在一系列浑浊和不浑浊的图像上观察内部活化，并发现几个复发细胞，这些细胞降低了多云观察的输入活性。因此，我们假设我们的网络仅从输入数据中学习了云过滤方案，这可以减轻繁琐的云过滤作为许多EO方法的预处理步骤的需要。此外，使用未经过滤的时间序列的顶部大气（TOA）反射率数据，我们在实验中实现了与其他分类方法相比在最少预处理的情况下对大量作物类别的最新分类准确性。

##### URL
[http://arxiv.org/abs/1802.02080](http://arxiv.org/abs/1802.02080)

##### PDF
[http://arxiv.org/pdf/1802.02080](http://arxiv.org/pdf/1802.02080)

