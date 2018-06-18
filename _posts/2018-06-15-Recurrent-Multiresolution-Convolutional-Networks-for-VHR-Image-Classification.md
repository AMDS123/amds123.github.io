---
layout: post
title: "Recurrent Multiresolution Convolutional Networks for VHR Image Classification"
date: 2018-06-15 03:01:43
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding CNN Image_Classification Classification Quantitative
author: John Ray Bergado, Claudio Persello, Alfred Stein
mathjax: true
---

* content
{:toc}

##### Abstract
Classification of very high resolution (VHR) satellite images has three major challenges: 1) inherent low intra-class and high inter-class spectral similarities, 2) mismatching resolution of available bands, and 3) the need to regularize noisy classification maps. Conventional methods have addressed these challenges by adopting separate stages of image fusion, feature extraction, and post-classification map regularization. These processing stages, however, are not jointly optimizing the classification task at hand. In this study, we propose a single-stage framework embedding the processing stages in a recurrent multiresolution convolutional network trained in an end-to-end manner. The feedforward version of the network, called FuseNet, aims to match the resolution of the panchromatic and multispectral bands in a VHR image using convolutional layers with corresponding downsampling and upsampling operations. Contextual label information is incorporated into FuseNet by means of a recurrent version called ReuseNet. We compared FuseNet and ReuseNet against the use of separate processing steps for both image fusion, e.g. pansharpening and resampling through interpolation, and map regularization such as conditional random fields. We carried out our experiments on a land cover classification task using a Worldview-03 image of Quezon City, Philippines and the ISPRS 2D semantic labeling benchmark dataset of Vaihingen, Germany. FuseNet and ReuseNet surpass the baseline approaches in both quantitative and qualitative results.

##### Abstract (translated by Google)
超高分辨率（VHR）卫星图像的分类存在三个主要挑战：1）固有的低阶内和高阶间光谱相似性，2）可用波段的不匹配分辨率，以及3）需要规则化噪声分类图。传统方法通过采用图像融合，特征提取和后分类图正则化的单独阶段来解决这些挑战。然而，这些处理阶段并未联合优化手头的分类任务。在这项研究中，我们提出了一个单阶段框架，将处理阶段嵌入到以端对端方式训练的循环多分辨率卷积网络中。该网络的前馈版本称为FuseNet，旨在匹配使用卷积层的VHR图像中的全色和多光谱波段的分辨率以及相应的下采样和上采样操作。上下文标签信息通过名为ReuseNet的复制版本并入FuseNet。我们比较了FuseNet和ReuseNet与图像融合的单独处理步骤的使用，例如，通过插值进行平滑和重采样，以及条件随机场等地图正则化。我们使用菲律宾奎松市的Worldview-03图像和德国Vaihingen的ISPRS 2D语义标注基准数据集进行了土地覆盖分类任务的实验。 FuseNet和ReuseNet超越了定量和定性结果的基准方法。

##### URL
[http://arxiv.org/abs/1806.05793](http://arxiv.org/abs/1806.05793)

##### PDF
[http://arxiv.org/pdf/1806.05793](http://arxiv.org/pdf/1806.05793)

