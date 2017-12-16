---
layout: post
title: "A Generative Model of People in Clothing"
date: 2017-07-31 16:09:17
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Christoph Lassner, Gerard Pons-Moll, Peter V. Gehler
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first image-based generative model of people in clothing for the full body. We sidestep the commonly used complex graphics rendering pipeline and the need for high-quality 3D scans of dressed people. Instead, we learn generative models from a large image database. The main challenge is to cope with the high variance in human pose, shape and appearance. For this reason, pure image-based approaches have not been considered so far. We show that this challenge can be overcome by splitting the generating process in two parts. First, we learn to generate a semantic segmentation of the body and clothing. Second, we learn a conditional model on the resulting segments that creates realistic images. The full model is differentiable and can be conditioned on pose, shape or color. The result are samples of people in different clothing items and styles. The proposed model can generate entirely new people with realistic clothing. In several experiments we present encouraging results that suggest an entirely data-driven approach to people generation is possible.

##### Abstract (translated by Google)
我们展示了第一个基于图像的人体服装生成模型。我们避开了常用的复杂图形渲染流水线，并需要高质量的3D打印人员扫描。相反，我们从大型图像数据库中学习生成模型。主要的挑战是应对人体姿势，形状和外观的高度差异。出于这个原因，目前还没有考虑纯粹的基于图像的方法。我们表明，这个挑战可以通过将生成过程分为两部分来克服。首先，我们学习生成身体和服装的语义分割。其次，我们学习了一个条件模型的结果段创建逼真的图像。完整的模型是可区分的，可以根据姿势，形状或颜色进行调整。结果是不同服装项目和风格的人的样本。所提出的模型可以生成具有逼真服装的全新人物。在一些实验中，我们提出了令人鼓舞的结果，表明完全以数据为导向的方法对于人的生成是可能的

##### URL
[https://arxiv.org/abs/1705.04098](https://arxiv.org/abs/1705.04098)

##### PDF
[https://arxiv.org/pdf/1705.04098](https://arxiv.org/pdf/1705.04098)

