---
layout: post
title: "An application of cascaded 3D fully convolutional networks for medical image segmentation"
date: 2018-03-20 05:22:07
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Semantic_Segmentation Prediction
author: Holger R. Roth, Hirohisa Oda, Xiangrong Zhou, Natsuki Shimizu, Ying Yang, Yuichiro Hayashi, Masahiro Oda, Michitaka Fujiwara, Kazunari Misawa, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in 3D fully convolutional networks (FCN) have made it feasible to produce dense voxel-wise predictions of volumetric images. In this work, we show that a multi-class 3D FCN trained on manually labeled CT scans of several anatomical structures (ranging from the large organs to thin vessels) can achieve competitive segmentation results, while avoiding the need for handcrafting features or training class-specific models. 
 To this end, we propose a two-stage, coarse-to-fine approach that will first use a 3D FCN to roughly define a candidate region, which will then be used as input to a second 3D FCN. This reduces the number of voxels the second FCN has to classify to ~10% and allows it to focus on more detailed segmentation of the organs and vessels. 
 We utilize training and validation sets consisting of 331 clinical CT images and test our models on a completely unseen data collection acquired at a different hospital that includes 150 CT scans, targeting three anatomical organs (liver, spleen, and pancreas). In challenging organs such as the pancreas, our cascaded approach improves the mean Dice score from 68.5 to 82.2%, achieving the highest reported average score on this dataset. We compare with a 2D FCN method on a separate dataset of 240 CT scans with 18 classes and achieve a significantly higher performance in small organs and vessels. Furthermore, we explore fine-tuning our models to different datasets. 
 Our experiments illustrate the promise and robustness of current 3D FCN based semantic segmentation of medical images, achieving state-of-the-art results. Our code and trained models are available for download: https://github.com/holgerroth/3Dunet_abdomen_cascade.

##### Abstract (translated by Google)
3D全卷积网络（FCN）的最新进展使得对体积图像进行密集的体素预测成为可能。在这项工作中，我们展示了一个多级三维FCN训练手动标记的几个解剖结构（从大型器官到薄血管）的CT扫描可以实现有竞争力的分割结果，同时避免需要手工制作功能或训练班级 - 具体型号。
 为此，我们提出了一个两阶段的，从粗到精的方法，它将首先使用3D FCN粗略定义候选区域，然后将其用作第二个3D FCN的输入。这减少了第二个FCN必须分类的体素数量至〜10％，并使其能够专注于器官和血管的更详细的分割。
 我们利用由331个临床CT影像组成的训练和验证集合，并对包含150次CT扫描的不同医院采集的完全不可见的数据集进行测试，针对三个解剖器官（肝脏，脾脏和胰腺）。在胰腺等具有挑战性的器官中，我们的级联方法将骰子平均得分从68.5提高到82.2％，实现了该数据集报告的最高平均得分。我们在240个CT扫描的18个类别的独立数据集上比较2D FCN方法，并在小器官和血管中实现显着更高的性能。此外，我们探索微调我们的模型到不同的数据集。
 我们的实验说明了当前基于三维FCN的医学图像语义分割的前景和稳健性，实现了最先进的结果。我们的代码和训练有素的模型可供下载：https：//github.com/holgerroth/3Dunet_abdomen_cascade。

##### URL
[http://arxiv.org/abs/1803.05431](http://arxiv.org/abs/1803.05431)

##### PDF
[http://arxiv.org/pdf/1803.05431](http://arxiv.org/pdf/1803.05431)

