---
layout: post
title: "Weakly supervised object detection using pseudo-strong labels"
date: 2016-07-16 11:49:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Ke Yang, Dongsheng Li, Yong Dou, Shaohe Lv, Qiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is an import task of computer vision.A variety of methods have been proposed,but methods using the weak labels still do not have a satisfactory result.In this paper,we propose a new framework that using the weakly supervised method's output as the pseudo-strong labels to train a strongly supervised model.One weakly supervised method is treated as black-box to generate class-specific bounding boxes on train dataset.A de-noise method is then applied to the noisy bounding boxes.Then the de-noised pseudo-strong labels are used to train a strongly object detection network.The whole framework is still weakly supervised because the entire process only uses the image-level labels.The experiment results on PASCAL VOC 2007 prove the validity of our framework, and we get result 43.4% on mean average precision compared to 39.5% of the previous best result and 34.5% of the initial method,respectively.And this frame work is simple and distinct,and is promising to be applied to other method easily.

##### Abstract (translated by Google)
目标检测是计算机视觉的一项重要任务，已经提出了多种方法，但使用弱标签的方法仍然没有得到满意的结果。本文提出了一种新的框架，使用弱监督方法的输出作为伪强标签训练强监督模型。将弱监督方法视为黑盒，在训练数据集上生成类别特定边界框，然后对噪声包围盒应用去噪方法，噪声伪强标签被用来训练一个强烈的物体检测网络。整个框架仍然是弱监督的，因为整个过程只使用图像级标签。在PASCAL VOC 2007上的实验结果证明了我们框架的有效性，平均得到的结果平均精度为43.4％，相比之前的最好结果的39.5％和初始方法的34.5％，且框架工作简单明了，有望应用于其他方法很容易。

##### URL
[https://arxiv.org/abs/1607.04731](https://arxiv.org/abs/1607.04731)

