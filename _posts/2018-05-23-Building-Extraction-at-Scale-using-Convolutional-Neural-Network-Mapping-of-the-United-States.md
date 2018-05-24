---
layout: post
title: "Building Extraction at Scale using Convolutional Neural Network: Mapping of the United States"
date: 2018-05-23 03:28:05
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Hsiuhan Lexie Yang, Jiangye Yuan, Dalton Lunga, Melanie Laverdiere, Amy Rose, Budhendra Bhaduri
mathjax: true
---

* content
{:toc}

##### Abstract
Establishing up-to-date large scale building maps is essential to understand urban dynamics, such as estimating population, urban planning and many other applications. Although many computer vision tasks has been successfully carried out with deep convolutional neural networks, there is a growing need to understand their large scale impact on building mapping with remote sensing imagery. Taking advantage of the scalability of CNNs and using only few areas with the abundance of building footprints, for the first time we conduct a comparative analysis of four state-of-the-art CNNs for extracting building footprints across the entire continental United States. The four CNN architectures namely: branch-out CNN, fully convolutional neural network (FCN), conditional random field as recurrent neural network (CRFasRNN), and SegNet, support semantic pixel-wise labeling and focus on capturing textural information at multi-scale. We use 1-meter resolution aerial images from National Agriculture Imagery Program (NAIP) as the test-bed, and compare the extraction results across the four methods. In addition, we propose to combine signed-distance labels with SegNet, the preferred CNN architecture identified by our extensive evaluations, to advance building extraction results to instance level. We further demonstrate the usefulness of fusing additional near IR information into the building extraction framework. Large scale experimental evaluations are conducted and reported using metrics that include: precision, recall rate, intersection over union, and the number of buildings extracted. With the improved CNN model and no requirement of further post-processing, we have generated building maps for the United States. The quality of extracted buildings and processing time demonstrated the proposed CNN-based framework fits the need of building extraction at scale.

##### Abstract (translated by Google)
建立最新的大型建筑地图对于了解城市动态，如估算人口，城市规划和许多其他应用程序非常重要。虽然许多计算机视觉任务已经成功地用深度卷积神经网络进行，但人们越来越需要了解它们对遥感影像建筑物映射的大规模影响。利用CNN的可扩展性以及只有少数几个地区有足够的建筑足迹，我们首次对四个最先进的CNN进行比较分析，以提取整个美国大陆的建筑物足迹。四种CNN体系结构即：分支CNN，完全卷积神经网络（FCN），作为递归神经网络的条件随机场（CRFasRNN）和SegNet，支持语义像素标记并专注于多尺度捕获纹理信息。我们使用国家农业影像计划（NAIP）提供的1米分辨率航拍图像作为实验台，并比较四种方法的提取结果。此外，我们建议将带符号距离标签与我们广泛评估确定的首选CNN架构SegNet相结合，以将建筑物提取结果推进到实例级别。我们进一步证明将附加近红外信息融入建筑物提取框架的实用性。进行大规模实验评估并使用度量进行报告，这些度量包括：精确度，召回率，联合交集和提取的建筑物数量。有了改进的CNN模型并且不需要进一步的后处理，我们为美国生成了建筑图。提取建筑物的质量和处理时间表明，提出的基于CNN的框架适合大规模提取建筑物的需求。

##### URL
[http://arxiv.org/abs/1805.08946](http://arxiv.org/abs/1805.08946)

##### PDF
[http://arxiv.org/pdf/1805.08946](http://arxiv.org/pdf/1805.08946)

