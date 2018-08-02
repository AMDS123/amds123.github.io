---
layout: post
title: "WeedMap: A large-scale semantic weed mapping framework using aerial multispectral imaging and deep neural network for precision farming"
date: 2018-07-31 22:45:11
categories: arXiv_RO
tags: arXiv_RO Segmentation Semantic_Segmentation Classification Quantitative
author: Inkyu Sa, Marija Popovic, Raghav Khanna, Zetao Chen, Philipp Lottes, Frank Liebisch, Juan Nieto, Cyrill Stachniss, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel weed segmentation and mapping framework that processes multispectral images obtained from an unmanned aerial vehicle (UAV) using a deep neural network (DNN). Most studies on crop/weed semantic segmentation only consider single images for processing and classification. Images taken by UAVs often cover only a few hundred square meters with either color only or color and near-infrared (NIR) channels. Computing a single large and accurate vegetation map (e.g., crop/weed) using a DNN is non-trivial due to difficulties arising from: (1) limited ground sample distances (GSDs) in high-altitude datasets, (2) sacrificed resolution resulting from downsampling high-fidelity images, and (3) multispectral image alignment. To address these issues, we adopt a stand sliding window approach that operates on only small portions of multispectral orthomosaic maps (tiles), which are channel-wise aligned and calibrated radiometrically across the entire map. We define the tile size to be the same as that of the DNN input to avoid resolution loss. Compared to our baseline model (i.e., SegNet with 3 channel RGB inputs) yielding an area under the curve (AUC) of [background=0.607, crop=0.681, weed=0.576], our proposed model with 9 input channels achieves [0.839, 0.863, 0.782]. Additionally, we provide an extensive analysis of 20 trained models, both qualitatively and quantitatively, in order to evaluate the effects of varying input channels and tunable network hyperparameters. Furthermore, we release a large sugar beet/weed aerial dataset with expertly guided annotations for further research in the fields of remote sensing, precision agriculture, and agricultural robotics.

##### Abstract (translated by Google)
我们提出了一种新颖的杂草分割和绘图框架，使用深度神经网络（DNN）处理从无人驾驶飞行器（UAV）获得的多光谱图像。大多数关于作物/杂草语义分割的研究仅考虑单个图像进行处理和分类。无人机拍摄的图像通常只覆盖几百平方米，只有彩色或彩色和近红外（NIR）通道。使用DNN计算单个大而精确的植被图（例如，作物/杂草）是非常重要的，因为以下方面的困难：（1）高海拔数据集中的地面样本距离（GSD）有限，（2）牺牲了分辨率从下采样高保真图像，和（3）多光谱图像对齐。为了解决这些问题，我们采用了一种立式滑动窗口方法，该方法仅对多光谱正射马赛克地图（瓦片）的一小部分进行操作，这些地图在整个地图上以通道方式对齐和校准。我们将磁贴大小定义为与DNN输入的大小相同，以避免分辨率丢失。与我们的基线模型（即具有3通道RGB输入的SegNet）相比，产生[背景= 0.607，作物= 0.681，杂草= 0.576]的曲线下面积（AUC），我们提出的具有9个输入通道的模型达到[0.839， 0.863,0.782]。此外，我们提供了20个训练模型的广泛分析，包括定性和定量，以评估不同输入通道和可调网络超参数的影响。此外，我们还发布了一个大型甜菜/杂草航空数据集，其中包含专业指导注释，可用于遥感，精准农业和农业机器人领域的进一步研究。

##### URL
[https://arxiv.org/abs/1808.00100](https://arxiv.org/abs/1808.00100)

##### PDF
[https://arxiv.org/pdf/1808.00100](https://arxiv.org/pdf/1808.00100)

