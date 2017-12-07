---
layout: post
title: "Beyond Part Models: Person Retrieval with Refined Part Pooling"
date: 2017-12-02 04:34:28
categories: arXiv_CV
tags: arXiv_CV Image_Caption Pose_Estimation CNN
author: Yifan Sun, Liang Zheng, Yi Yang, Qi Tian, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Employing part-level features for pedestrian image description offers fine-grained information and has been verified as beneficial for person retrieval in very recent literature. A prerequisite of part discovery is that each part should be well located. Instead of using external cues, e.g., pose estimation, to directly locate parts, this paper lays emphasis on the content consistency within each part. </p> <p>Specifically, we target at learning discriminative part-informed features for person retrieval and make two contributions. (i) A network named Part-based Convolutional Baseline (PCB). Given an image input, it outputs a convolutional descriptor consisting of several part-level features. With a uniform partition strategy, PCB achieves competitive results with the state-of-the-art methods, proving itself as a strong convolutional baseline for person retrieval. </p> <p>(ii) A refined part pooling (RPP) method. Uniform partition inevitably incurs outliers in each part, which are in fact more similar to other parts. RPP re-assigns these outliers to the parts they are closest to, resulting in refined parts with enhanced within-part consistency. Experiment confirms that RPP allows PCB to gain another round of performance boost. For instance, on the Market-1501 dataset, we achieve (77.4+4.2)% mAP and (92.3+1.5)% rank-1 accuracy, surpassing the state of the art by a large margin.

##### Abstract (translated by Google)
在行人图像描述中使用部分级别的特征提供了细​​粒度的信息，并且在最近的文献中已经被验证为有益于人员检索。零件发现的前提是每个零件都应该位于适当位置。本文不是直接使用外部线索（例如姿态估计）直接定位部分，而是着重于每个部分的内容一致性。具体来说，我们的目标是学习人类检索的区分性的部分通知功能，并作出两个贡献。 （i）名为基于部分的卷积基线（PCB）的网络。给定一个图像输入，它输出一个卷积描述符，由几个部分级特征组成。采用统一的分区策略，PCB以最先进的方法获得了有竞争力的结果，证明了自己是人类检索的强大卷积基准。 （ii）精炼零件库（RPP）方法。统一划分不可避免地导致每个部分中的异常值，实际上与其他部分更相似。 RPP将这些异常值重新分配给它们最接近的部分，从而导致部件间一致性增强的精细部件。实验证实RPP可以让PCB获得新一轮的性能提升。例如，在Market-1501数据集中，我们实现了（77.4 + 4.2）％的mAP和（92.3 + 1.5）％的一级精度，大大超过了现有技术水平。

##### URL
[http://arxiv.org/abs/1711.09349](http://arxiv.org/abs/1711.09349)

##### PDF
[http://arxiv.org/pdf/1711.09349](http://arxiv.org/pdf/1711.09349)

