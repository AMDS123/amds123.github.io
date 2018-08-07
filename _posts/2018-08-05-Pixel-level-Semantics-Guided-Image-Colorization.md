---
layout: post
title: "Pixel-level Semantics Guided Image Colorization"
date: 2018-08-05 11:20:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference
author: Jiaojiao Zhao, Li Liu, Cees G.M. Snoek, Jungong Han, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
While many image colorization algorithms have recently shown the capability of producing plausible color versions from gray-scale photographs, they still suffer from the problems of context confusion and edge color bleeding. To address context confusion, we propose to incorporate the pixel-level object semantics to guide the image colorization. The rationale is that human beings perceive and distinguish colors based on the object's semantic categories. We propose a hierarchical neural network with two branches. One branch learns what the object is while the other branch learns the object's colors. The network jointly optimizes a semantic segmentation loss and a colorization loss. To attack edge color bleeding we generate more continuous color maps with sharp edges by adopting a joint bilateral upsamping layer at inference. Our network is trained on PASCAL VOC2012 and COCO-stuff with semantic segmentation labels and it produces more realistic and finer results compared to the colorization state-of-the-art.

##### Abstract (translated by Google)
虽然许多图像着色算法最近显示出从灰度照片产生合理的彩色版本的能力，但它们仍然存在上下文混淆和边缘颜色渗色的问题。为了解决上下文混淆，我们建议结合像素级对象语义来指导图像着色。理由是人类根据对象的语义类别来感知和区分颜色。我们提出了一个有两个分支的分层神经网络。一个分支学习对象是什么，而另一个分支学习对象的颜色。网络联合优化语义分段丢失和着色损失。为了攻击边缘颜色渗透，我们通过在推理中采用联合双边上采样层来生成具有锐边的更连续的彩色图。我们的网络使用语义分段标签培训PASCAL VOC2012和COCO-stuff，与最先进的着色相比，它可以产生更真实，更精细的结果。

##### URL
[https://arxiv.org/abs/1808.01597](https://arxiv.org/abs/1808.01597)

##### PDF
[https://arxiv.org/pdf/1808.01597](https://arxiv.org/pdf/1808.01597)

