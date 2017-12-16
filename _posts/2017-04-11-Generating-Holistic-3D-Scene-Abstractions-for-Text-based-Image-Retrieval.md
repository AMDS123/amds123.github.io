---
layout: post
title: "Generating Holistic 3D Scene Abstractions for Text-based Image Retrieval"
date: 2017-04-11 20:37:18
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Inference Detection Relation
author: Ang Li, Jin Sun, Joe Yue-Hei Ng, Ruichi Yu, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial relationships between objects provide important information for text-based image retrieval. As users are more likely to describe a scene from a real world perspective, using 3D spatial relationships rather than 2D relationships that assume a particular viewing direction, one of the main challenges is to infer the 3D structure that bridges images with users' text descriptions. However, direct inference of 3D structure from images requires learning from large scale annotated data. Since interactions between objects can be reduced to a limited set of atomic spatial relations in 3D, we study the possibility of inferring 3D structure from a text description rather than an image, applying physical relation models to synthesize holistic 3D abstract object layouts satisfying the spatial constraints present in a textual description. We present a generic framework for retrieving images from a textual description of a scene by matching images with these generated abstract object layouts. Images are ranked by matching object detection outputs (bounding boxes) to 2D layout candidates (also represented by bounding boxes) which are obtained by projecting the 3D scenes with sampled camera directions. We validate our approach using public indoor scene datasets and show that our method outperforms baselines built upon object occurrence histograms and learned 2D pairwise relations.

##### Abstract (translated by Google)
对象之间的空间关系为基于文本的图像检索提供了重要的信息。由于用户更可能从真实世界的角度来描述场景，使用3D空间关系而不是假设特定观看方向的2D关系，所以主要挑战之一是推断将图像与用户的文本描述桥接的3D结构。然而，从图像直接推断三维结构需要从大规模的注释数据中学习。由于物体之间的相互作用可以简化为三维空间关系的有限集合，我们研究从文本描述而不是图像推断三维结构的可能性，应用物理关系模型来合成满足空间约束的整体三维抽象物体布局以文字描述呈现。我们提出了一个通用框架，通过将图像与这些生成的抽象对象布局进行匹配来从场景的文本描述中检索图像。图像通过匹配对象检测输出（包围盒）到2D布局候选（也通过包围盒表示）来排序，所述2D布局候选通过投影具有采样相机方向的3D场景而获得。我们验证我们的方法使用公共室内场景数据集，并表明我们的方法胜过建立在对象发生直方图基础上，并学习二维配对关系。

##### URL
[https://arxiv.org/abs/1611.09392](https://arxiv.org/abs/1611.09392)

##### PDF
[https://arxiv.org/pdf/1611.09392](https://arxiv.org/pdf/1611.09392)

