---
layout: post
title: "Clothing Co-Parsing by Joint Image Segmentation and Labeling"
date: 2015-02-03 04:59:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference Recognition
author: Wei Yang, Ping Luo, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at developing an integrated system of clothing co-parsing, in order to jointly parse a set of clothing images (unsegmented but annotated with tags) into semantic configurations. We propose a data-driven framework consisting of two phases of inference. The first phase, referred as "image co-segmentation", iterates to extract consistent regions on images and jointly refines the regions over all images by employing the exemplar-SVM (E-SVM) technique [23]. In the second phase (i.e. "region co-labeling"), we construct a multi-image graphical model by taking the segmented regions as vertices, and incorporate several contexts of clothing configuration (e.g., item location and mutual interactions). The joint label assignment can be solved using the efficient Graph Cuts algorithm. In addition to evaluate our framework on the Fashionista dataset [30], we construct a dataset called CCP consisting of 2098 high-resolution street fashion photos to demonstrate the performance of our system. We achieve 90.29% / 88.23% segmentation accuracy and 65.52% / 63.89% recognition rate on the Fashionista and the CCP datasets, respectively, which are superior compared with state-of-the-art methods.

##### Abstract (translated by Google)
本文旨在开发一个服装协同解析的集成系统，以便将一组服装图像（非分割但是标签注释）联合解析为语义配置。我们提出一个由两个推理阶段组成的数据驱动框架。第一个阶段称为“图像协同分割”，通过采用样本 - 支持向量机（E-SVM）技术[23]进行迭代，以提取图像上的一致区域，并共同细化所有图像上的区域。在第二阶段（即“区域共同标注”），我们通过将分割区域作为顶点来构建多图像图形模型，并且包含服装配置的多个上下文（例如，物品位置和相互作用）。联合标签分配可以使用高效的图形切割算法来解决。除了评估我们的Fashionista数据集框架[30]，我们还构建了一个由2098张高分辨率街头时尚照片组成的数据集，以展示我们系统的性能。分别对Fashionista和CCP数据集分别获得90.29％/ 88.23％的分割准确率和65.52％/ 63.89％的识别率，这些都比现有技术更好。

##### URL
[https://arxiv.org/abs/1502.00739](https://arxiv.org/abs/1502.00739)

##### PDF
[https://arxiv.org/pdf/1502.00739](https://arxiv.org/pdf/1502.00739)

