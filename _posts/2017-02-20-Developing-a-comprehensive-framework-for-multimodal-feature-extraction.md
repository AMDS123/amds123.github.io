---
layout: post
title: "Developing a comprehensive framework for multimodal feature extraction"
date: 2017-02-20 19:22:21
categories: arXiv_CV
tags: arXiv_CV Sentiment Face
author: Quinten McNamara, Alejandro de la Vega, Tal Yarkoni
mathjax: true
---

* content
{:toc}

##### Abstract
Feature extraction is a critical component of many applied data science workflows. In recent years, rapid advances in artificial intelligence and machine learning have led to an explosion of feature extraction tools and services that allow data scientists to cheaply and effectively annotate their data along a vast array of dimensions---ranging from detecting faces in images to analyzing the sentiment expressed in coherent text. Unfortunately, the proliferation of powerful feature extraction services has been mirrored by a corresponding expansion in the number of distinct interfaces to feature extraction services. In a world where nearly every new service has its own API, documentation, and/or client library, data scientists who need to combine diverse features obtained from multiple sources are often forced to write and maintain ever more elaborate feature extraction pipelines. To address this challenge, we introduce a new open-source framework for comprehensive multimodal feature extraction. Pliers is an open-source Python package that supports standardized annotation of diverse data types (video, images, audio, and text), and is expressly with both ease-of-use and extensibility in mind. Users can apply a wide range of pre-existing feature extraction tools to their data in just a few lines of Python code, and can also easily add their own custom extractors by writing modular classes. A graph-based API enables rapid development of complex feature extraction pipelines that output results in a single, standardized format. We describe the package's architecture, detail its major advantages over previous feature extraction toolboxes, and use a sample application to a large functional MRI dataset to illustrate how pliers can significantly reduce the time and effort required to construct sophisticated feature extraction workflows while increasing code clarity and maintainability.

##### Abstract (translated by Google)
特征提取是许多应用数据科学工作流程的重要组成部分。近年来，人工智能和机器学习的迅速发展导致了特征提取工具和服务的迅猛发展，使得数据科学家能够便宜有效地对数据进行大量的维度检测 - 从检测图像中的人脸到分析连贯文本表达的情感。不幸的是，强大的特征提取服务的激增已经反映在特征提取服务的不同接口的数量的相应扩展中。在几乎所有新服务都有自己的API，文档和/或客户端库的世界中，需要结合从多个来源获得的各种功能的数据科学家经常被迫编写和维护更加复杂的特征提取管道。为了应对这一挑战，我们引入了一个全新的多模态特征提取的开源框架。 Pliers是一个开放源代码的Python软件包，支持各种数据类型（视频，图像，音频和文本）的标准化注释，并且明确地兼顾易用性和可扩展性。用户只需几行Python代码即可将大量预先存在的特征提取工具应用到其数据中，还可以通过编写模块化类来轻松添加自己的自定义提取器。基于图形的API能够快速开发复杂的特征提取流水线，以单一的标准格式输出结果。我们描述软件包的体系结构，详细说明它比以前的特征提取工具箱的主要优点，并将示例应用程序用于大型功能性MRI数据集，以说明钳子如何显着减少构建复杂特征提取工作流所需的时间和精力，可维护性。

##### URL
[https://arxiv.org/abs/1702.06151](https://arxiv.org/abs/1702.06151)

##### PDF
[https://arxiv.org/pdf/1702.06151](https://arxiv.org/pdf/1702.06151)

