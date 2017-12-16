---
layout: post
title: "Material Editing Using a Physically Based Rendering Network"
date: 2017-08-09 17:28:54
categories: arXiv_CV
tags: arXiv_CV
author: Guilin Liu, Duygu Ceylan, Ersin Yumer, Jimei Yang, Jyh-Ming Lien
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to edit materials of objects in images is desirable by many content creators. However, this is an extremely challenging task as it requires to disentangle intrinsic physical properties of an image. We propose an end-to-end network architecture that replicates the forward image formation process to accomplish this task. Specifically, given a single image, the network first predicts intrinsic properties, i.e. shape, illumination, and material, which are then provided to a rendering layer. This layer performs in-network image synthesis, thereby enabling the network to understand the physics behind the image formation process. The proposed rendering layer is fully differentiable, supports both diffuse and specular materials, and thus can be applicable in a variety of problem settings. We demonstrate a rich set of visually plausible material editing examples and provide an extensive comparative study.

##### Abstract (translated by Google)
编辑图像中的对象材料的能力是许多内容创建者所希望的。然而，这是一个非常具有挑战性的任务，因为它需要分解图像的固有物理属性。我们提出了一个端到端的网络体系结构，复制正向图像形成过程来完成这项任务。具体而言，给定单个图像，网络首先预测内在属性，即形状，照明和材料，然后将其提供给渲染层。该层执行网内图像合成，从而使网络能够理解图像形成过程背后的物理。所提出的渲染层是完全可微分的，支持漫反射和镜面反射材料，因此可以应用于各种问题设置。我们展示了一套丰富的视觉上合理的材料编辑实例，并提供了一个广泛的比较研究。

##### URL
[https://arxiv.org/abs/1708.00106](https://arxiv.org/abs/1708.00106)

##### PDF
[https://arxiv.org/pdf/1708.00106](https://arxiv.org/pdf/1708.00106)

