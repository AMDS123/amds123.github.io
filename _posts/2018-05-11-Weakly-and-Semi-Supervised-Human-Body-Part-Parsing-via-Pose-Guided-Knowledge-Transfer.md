---
layout: post
title: "Weakly and Semi Supervised Human Body Part Parsing via Pose-Guided Knowledge Transfer"
date: 2018-05-11 10:30:56
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Semi_Supervised CNN Semantic_Segmentation
author: Hao-Shu Fang, Guansong Lu, Xiaolin Fang, Jianwen Xie, Yu-Wing Tai, Cewu Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Human body part parsing, or human semantic part segmentation, is fundamental to many computer vision tasks. In conventional semantic segmentation methods, the ground truth segmentations are provided, and fully convolutional networks (FCN) are trained in an end-to-end scheme. Although these methods have demonstrated impressive results, their performance highly depends on the quantity and quality of training data. In this paper, we present a novel method to generate synthetic human part segmentation data using easily-obtained human keypoint annotations. Our key idea is to exploit the anatomical similarity among human to transfer the parsing results of a person to another person with similar pose. Using these estimated results as additional training data, our semi-supervised model outperforms its strong-supervised counterpart by 6 mIOU on the PASCAL-Person-Part dataset, and we achieve state-of-the-art human parsing results. Our approach is general and can be readily extended to other object/animal parsing task assuming that their anatomical similarity can be annotated by keypoints. The proposed model and accompanying source code are available at https://github.com/MVIG-SJTU/WSHP

##### Abstract (translated by Google)
人体部分解析或人类语义部分分割是许多计算机视觉任务的基础。在传统的语义分割方法中，提供了地面真实分割，并且完全卷积网络（FCN）以端到端方案进行训练。虽然这些方法已经显示出令人印象深刻的结果，但它们的性能高度依赖于培训数据的数量和质量在本文中，我们提出了一种使用容易获得的人关键点注释来生成合成人体部分分割数据的新方法。我们的主要想法是利用人类之间的解剖相似性将人的分析结果传递给具有相似姿势的另一人。使用这些估计结果作为额外的训练数据，我们的半监督模型在PASCAL-Person-Part数据集上优于强监督对象6 mIOU，并且我们实现了最先进的人类解析结果。我们的方法是一般的，并且可以容易地扩展到其他对象/动物解析任务，假定它们的解剖相似性可以由关键点注释。建议的模型和附带的源代码可在https://github.com/MVIG-SJTU/WSHP获得

##### URL
[http://arxiv.org/abs/1805.04310](http://arxiv.org/abs/1805.04310)

##### PDF
[http://arxiv.org/pdf/1805.04310](http://arxiv.org/pdf/1805.04310)

