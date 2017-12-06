---
layout: post
title: "SketchParse : Towards Rich Descriptions for Poorly Drawn Sketches using Multi-Task Hierarchical Deep Networks"
date: 2017-09-05 09:10:59
categories: arXiv_CV
tags: arXiv_CV Caption CNN
author: Ravi Kiran Sarvadevabhatla, Isht Dwivedi, Abhijat Biswas, Sahil Manocha, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to semantically interpret hand-drawn line sketches, although very challenging, can pave way for novel applications in multimedia. We propose SketchParse, the first deep-network architecture for fully automatic parsing of freehand object sketches. SketchParse is configured as a two-level fully convolutional network. The first level contains shared layers common to all object categories. The second level contains a number of expert sub-networks. Each expert specializes in parsing sketches from object categories which contain structurally similar parts. Effectively, the two-level configuration enables our architecture to scale up efficiently as additional categories are added. We introduce a router layer which (i) relays sketch features from shared layers to the correct expert (ii) eliminates the need to manually specify object category during inference. To bypass laborious part-level annotation, we sketchify photos from semantic object-part image datasets and use them for training. Our architecture also incorporates object pose prediction as a novel auxiliary task which boosts overall performance while providing supplementary information regarding the sketch. We demonstrate SketchParse's abilities (i) on two challenging large-scale sketch datasets (ii) in parsing unseen, semantically related object categories (iii) in improving fine-grained sketch-based image retrieval. As a novel application, we also outline how SketchParse's output can be used to generate caption-style descriptions for hand-drawn sketches.

##### Abstract (translated by Google)
语义上解释手绘线条草图的能力虽然非常具有挑战性，但可以为多媒体中的新颖应用铺平道路。我们提出了SketchParse，第一个深度网络体系结构，用于自由对象草图的全自动解析。 SketchParse被配置为一个两级完全卷积网络。第一级包含所有对象类别共有的共享层。第二层包含一些专家子网络。每位专家都专注于解析来自包含结构相似部分的对象类别的草图。实际上，两级配置使我们的体系结构能够随着其他类别的增加而有效地扩展。我们引入一个路由器层，它将（i）将共享层的草图特征传递给正确的专家;（ii）消除在推理期间手动指定对象类别的需要。为了避免费力的部分级注释，我们从语义对象部分图像数据集中描绘照片并将其用于训练。我们的架构还将对象姿态预测作为一项新辅助任务加以整合，同时提供关于草图的补充信息。我们演示了SketchParse的能力（一）在两个具有挑战性的大型草图数据集（二）解析看不见的，语义相关的对象类别（三）在改善细粒度的基于草图的图像检索。作为一个新颖的应用程序，我们还概述了SketchParse的输出如何用于为手绘草图生成字幕风格的描述。

##### URL
[https://arxiv.org/abs/1709.01295](https://arxiv.org/abs/1709.01295)

