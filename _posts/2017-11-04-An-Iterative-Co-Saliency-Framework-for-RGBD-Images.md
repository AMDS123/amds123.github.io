---
layout: post
title: "An Iterative Co-Saliency Framework for RGBD Images"
date: 2017-11-04 00:41:06
categories: arXiv_CV
tags: arXiv_CV Salient Detection
author: Runmin Cong, Jianjun Lei, Huazhu Fu, Weisi Lin, Qingming Huang, Xiaochun Cao, Chunping Hou
mathjax: true
---

* content
{:toc}

##### Abstract
As a newly emerging and significant topic in computer vision community, co-saliency detection aims at discovering the common salient objects in multiple related images. The existing methods often generate the co-saliency map through a direct forward pipeline which is based on the designed cues or initialization, but lack the refinement-cycle scheme. Moreover, they mainly focus on RGB image and ignore the depth information for RGBD images. In this paper, we propose an iterative RGBD co-saliency framework, which utilizes the existing single saliency maps as the initialization, and generates the final RGBD cosaliency map by using a refinement-cycle model. Three schemes are employed in the proposed RGBD co-saliency framework, which include the addition scheme, deletion scheme, and iteration scheme. The addition scheme is used to highlight the salient regions based on intra-image depth propagation and saliency propagation, while the deletion scheme filters the saliency regions and removes the non-common salient regions based on interimage constraint. The iteration scheme is proposed to obtain more homogeneous and consistent co-saliency map. Furthermore, a novel descriptor, named depth shape prior, is proposed in the addition scheme to introduce the depth information to enhance identification of co-salient objects. The proposed method can effectively exploit any existing 2D saliency model to work well in RGBD co-saliency scenarios. The experiments on two RGBD cosaliency datasets demonstrate the effectiveness of our proposed framework.

##### Abstract (translated by Google)
协同显着性检测作为计算机视觉领域新兴的重要课题，旨在发现多个相关图像中的常见显着对象。现有的方法往往是通过一个直接的前向流水线来生成协同显着图，该流水线基于设计的提示或初始化，但缺乏细化周期方案。此外，他们主要关注RGB图像，忽略RGBD图像的深度信息。在本文中，我们提出了一个迭代的RGBD协同显着性框架，它利用现有的单一显着性图作为初始化，并通过一个细化周期模型生成最终的RGBD协同性图。在所提出的RGBD协同显着框架中采用了三种方案，包括加法方案，删除方案和迭代方案。添加方案用于基于图像内部的深度传播和显着性传播来突出显着区域，而删除方案基于图像间约束来滤除显着区域并去除非共同显着区域。提出了迭代方案，以获得更加均匀一致的协同显着图。此外，在加法方案中提出了一种新的描述符，称为深度形状先验，以引入深度信息来增强对同位凸对象的识别。所提出的方法可以有效地利用任何现有的二维显着性模型在RGBD协同显着情况下良好地工作。两个RGBD余量数据集的实验证明了我们提出的框架的有效性。

##### URL
[https://arxiv.org/abs/1711.01371](https://arxiv.org/abs/1711.01371)

##### PDF
[https://arxiv.org/pdf/1711.01371](https://arxiv.org/pdf/1711.01371)

