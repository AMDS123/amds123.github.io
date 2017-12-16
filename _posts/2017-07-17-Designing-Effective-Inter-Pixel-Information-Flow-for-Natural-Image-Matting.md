---
layout: post
title: "Designing Effective Inter-Pixel Information Flow for Natural Image Matting"
date: 2017-07-17 09:35:14
categories: arXiv_CV
tags: arXiv_CV Embedding Relation
author: Yağız Aksoy, Tunç Ozan Aydın, Marc Pollefeys
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel, purely affinity-based natural image matting algorithm. Our method relies on carefully defined pixel-to-pixel connections that enable effective use of information available in the image. We control the information flow from the known-opacity regions into the unknown region, as well as within the unknown region itself, by utilizing multiple definitions of pixel affinities. Among other forms of information flow, we introduce color-mixture flow, which builds upon local linear embedding and effectively encapsulates the relation between different pixel opacities. Our resulting novel linear system formulation can be solved in closed-form and is robust against several fundamental challenges of natural matting such as holes and remote intricate structures. Our evaluation using the alpha matting benchmark suggests a significant performance improvement over the current methods. While our method is primarily designed as a standalone matting tool, we show that it can also be used for regularizing mattes obtained by sampling-based methods. We extend our formulation to layer color estimation and show that the use of multiple channels of flow increases the layer color quality. We also demonstrate our performance in green-screen keying and further analyze the characteristics of the affinities used in our method.

##### Abstract (translated by Google)
我们提出了一种新颖的纯粹基于亲和力的自然图像抠像算法。我们的方法依赖于仔细定义的像素到像素的连接，可以有效地使用图像中可用的信息。我们通过利用像素亲和力的多重定义来控制从已知不透明区域到未知区域以及未知区域本身内的信息流。在其他形式的信息流中，我们引入了混合色彩流，它建立在局部线性嵌入的基础上，有效地封装了不同像素不透明度之间的关系。我们所得到的新颖的线性系统配方可以以封闭的形式解决，并且能够抵抗诸如孔和远程复杂结构等自然消光的几个基本挑战。我们使用alpha matting基准进行评估表明，与现有方法相比，显着提高了性能。虽然我们的方法主要是作为一个独立的消光工具设计的，但是我们证明它也可以用于规则化基于抽样的方法获得的消光。我们将我们的公式扩展到图层颜色估计，并显示使用多个流道来增加图层颜色质量。我们还展示了我们在绿屏键控方面的表现，并进一步分析了我们方法中使用的亲和性的特征。

##### URL
[https://arxiv.org/abs/1707.05055](https://arxiv.org/abs/1707.05055)

##### PDF
[https://arxiv.org/pdf/1707.05055](https://arxiv.org/pdf/1707.05055)

