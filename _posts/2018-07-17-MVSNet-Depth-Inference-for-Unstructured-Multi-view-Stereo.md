---
layout: post
title: "MVSNet: Depth Inference for Unstructured Multi-view Stereo"
date: 2018-07-17 12:44:13
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning
author: Yao Yao, Zixin Luo, Shiwei Li, Tian Fang, Long Quan
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end deep learning architecture for depth map inference from multi-view images. In the network, we first extract deep visual image features, and then build the 3D cost volume upon the reference camera frustum via the differentiable homography warping. Next, we apply 3D convolutions to regularize and regress the initial depth map, which is then refined with the reference image to generate the final output. Our framework flexibly adapts arbitrary N-view inputs using a variance-based cost metric that maps multiple features into one cost feature. The proposed MVSNet is demonstrated on the large-scale indoor DTU dataset. With simple post-processing, our method not only significantly outperforms previous state-of-the-arts, but also is several times faster in runtime. We also evaluate MVSNet on the complex outdoor Tanks and Temples dataset, where our method ranks first before April 18, 2018 without any fine-tuning, showing the strong generalization ability of MVSNet.

##### Abstract (translated by Google)
我们提出了一种端到端深度学习架构，用于从多视图图像中进行深度图推理。在网络中，我们首先提取深度可视图像特征，然后通过可微分的单应性扭曲在参考相机平截头体上构建3D成本量。接下来，我们应用3D卷积来规范和回归初始深度图，然后使用参考图像对其进行细化以生成最终输出。我们的框架使用基于方差的成本度量灵活地适应任意N视图输入，该成本度量将多个特征映射到一个成本特征。拟议的MVSNet在大型室内DTU数据集上进行了演示。通过简单的后处理，我们的方法不仅明显优于以前的技术水平，而且在运行时也快了几倍。我们还在复杂的室外Tanks和Temples数据集上评估MVSNet，我们的方法在2018年4月18日之前排名第一，没有任何微调，显示出MVSNet强大的泛化能力。

##### URL
[http://arxiv.org/abs/1804.02505](http://arxiv.org/abs/1804.02505)

##### PDF
[http://arxiv.org/pdf/1804.02505](http://arxiv.org/pdf/1804.02505)

