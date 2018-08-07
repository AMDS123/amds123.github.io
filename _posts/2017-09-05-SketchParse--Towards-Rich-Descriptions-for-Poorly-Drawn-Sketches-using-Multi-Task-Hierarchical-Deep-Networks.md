---
layout: post
title: "SketchParse : Towards Rich Descriptions for Poorly Drawn Sketches using Multi-Task Hierarchical Deep Networks"
date: 2017-09-05 09:10:59
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Caption CNN Inference Prediction
author: Ravi Kiran Sarvadevabhatla, Isht Dwivedi, Abhijat Biswas, Sahil Manocha, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to semantically interpret hand-drawn line sketches, although very challenging, can pave way for novel applications in multimedia. We propose SketchParse, the first deep-network architecture for fully automatic parsing of freehand object sketches. SketchParse is configured as a two-level fully convolutional network. The first level contains shared layers common to all object categories. The second level contains a number of expert sub-networks. Each expert specializes in parsing sketches from object categories which contain structurally similar parts. Effectively, the two-level configuration enables our architecture to scale up efficiently as additional categories are added. We introduce a router layer which (i) relays sketch features from shared layers to the correct expert (ii) eliminates the need to manually specify object category during inference. To bypass laborious part-level annotation, we sketchify photos from semantic object-part image datasets and use them for training. Our architecture also incorporates object pose prediction as a novel auxiliary task which boosts overall performance while providing supplementary information regarding the sketch. We demonstrate SketchParse's abilities (i) on two challenging large-scale sketch datasets (ii) in parsing unseen, semantically related object categories (iii) in improving fine-grained sketch-based image retrieval. As a novel application, we also outline how SketchParse's output can be used to generate caption-style descriptions for hand-drawn sketches.

##### Abstract (translated by Google)
语义解释手绘线条草图的能力虽然非常具有挑战性，但它可以为多媒体中的新颖应用铺平道路。我们提出了SketchParse，这是第一个用于全自动解析手绘对象草图的深度网络架构。 SketchParse配置为两级完全卷积网络。第一级包含所有对象类别共有的共享层。第二级包含许多专家子网。每个专家都专门从包含结构相似部分的对象类别中解析草图。实际上，两级配置使我们的架构能够在添加其他类别时有效扩展。我们引入了一个路由器层，它（i）将共享层的草图特征传递给正确的专家（ii）消除了在推理过程中手动指定对象类别的需要。为了绕过繁琐的部分级注释，我们从语义对象 - 部分图像数据集中描绘照片并将其用于训练。我们的架构还将对象姿态预测作为一种新颖的辅助任务，在提供有关草图的补充信息的同时提高整体性能。我们展示了SketchParse的能力（i）在两个具有挑战性的大型草图数据集（ii）中解析了看不见的，语义相关的对象类别（iii），以改进细粒度的基于草图的图像检索。作为一个新颖的应用程序，我们还概述了SketchParse的输出如何用于为手绘草图生成字幕样式描述。

##### URL
[https://arxiv.org/abs/1709.01295](https://arxiv.org/abs/1709.01295)

##### PDF
[https://arxiv.org/pdf/1709.01295](https://arxiv.org/pdf/1709.01295)

