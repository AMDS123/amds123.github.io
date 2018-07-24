---
layout: post
title: "Dual Refinement Network for Single-Shot Object Detection"
date: 2018-07-23 14:29:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection
author: Xingyu Chen, Zhengxing Wu, Junzhi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection methods fall into two categories, i.e., two-stage and single-stage detectors. The former is characterized by high detection accuracy while the latter usually has considerable inference speed. Hence, it is imperative to fuse their metrics for a better accuracy vs. speed trade-off. To this end, we propose a dual refinement network (Dual-RefineDet) to boost the performance of the single-stage detector. Inheriting from advantages of the two-stage approach (i.e., two-step regression and accurate features for detection), anchor refinement and feature offset refinement are conducted in anchor-offset detection, where the detection head is comprised of deformable convolutions. Moreover, to leverage contextual information for describing objects, we design a multi-deformable head, in which multiple detection paths with different respective field sizes devote themselves to detecting objects. Extensive experiments on PASCAL VOC datasets are conducted, and we achieve the state-of-the-art results and a better accuracy vs. speed trade-off, i.e., $81.3\%$ mAP vs. $42.3$ FPS with $320\times 320$ input image on VOC2007 dataset. Codes will be made publicly available.

##### Abstract (translated by Google)
物体检测方法分为两类，即两级和单级检测器。前者的特征在于高检测精度，而后者通常具有相当大的推理速度。因此，必须融合其指标，以获得更好的准确性与速度权衡。为此，我们提出了一种双精化网络（Dual-RefineDet）来提高单级探测器的性能。继承两阶段方法的优点（即，两步回归和用于检测的精确特征），在锚偏移检测中进行锚定细化和特征偏移细化，其中检测头由可变形卷积组成。此外，为了利用上下文信息来描述对象，我们设计了一个多变形头，其中具有不同相应字段大小的多个检测路径专用于检测对象。在PASCAL VOC数据集上进行了大量实验，我们获得了最先进的结果和更好的准确性与速度权衡，即$ 81.3 \％$ mAP vs. $ 42.3 $ FPS $ 320 \ times 320 $在VOC2007数据集上输入图像。代码将公开发布。

##### URL
[http://arxiv.org/abs/1807.08638](http://arxiv.org/abs/1807.08638)

##### PDF
[http://arxiv.org/pdf/1807.08638](http://arxiv.org/pdf/1807.08638)

