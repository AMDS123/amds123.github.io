---
layout: post
title: "STC: A Simple to Complex Framework for Weakly-supervised Semantic Segmentation"
date: 2016-12-07 10:59:12
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Yunchao Wei, Xiaodan Liang, Yunpeng Chen, Xiaohui Shen, Ming-Ming Cheng, Jiashi Feng, Yao Zhao, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, significant improvement has been made on semantic object segmentation due to the development of deep convolutional neural networks (DCNNs). Training such a DCNN usually relies on a large number of images with pixel-level segmentation masks, and annotating these images is very costly in terms of both finance and human effort. In this paper, we propose a simple to complex (STC) framework in which only image-level annotations are utilized to learn DCNNs for semantic segmentation. Specifically, we first train an initial segmentation network called Initial-DCNN with the saliency maps of simple images (i.e., those with a single category of major object(s) and clean background). These saliency maps can be automatically obtained by existing bottom-up salient object detection techniques, where no supervision information is needed. Then, a better network called Enhanced-DCNN is learned with supervision from the predicted segmentation masks of simple images based on the Initial-DCNN as well as the image-level annotations. Finally, more pixel-level segmentation masks of complex images (two or more categories of objects with cluttered background), which are inferred by using Enhanced-DCNN and image-level annotations, are utilized as the supervision information to learn the Powerful-DCNN for semantic segmentation. Our method utilizes $40$K simple images from Flickr.com and 10K complex images from PASCAL VOC for step-wisely boosting the segmentation network. Extensive experimental results on PASCAL VOC 2012 segmentation benchmark well demonstrate the superiority of the proposed STC framework compared with other state-of-the-arts.

##### Abstract (translated by Google)
最近，由于深度卷积神经网络（DCNN）的发展，语义对象分割已经取得了显着的进步。训练这样的DCNN通常依赖于大量的具有像素级分割掩模的图像，并且注解这些图像在财务和人力两方面都是非常昂贵的。在本文中，我们提出了一个简单到复杂（STC）的框架，其中只有图像级别的注释被用来学习DCNN的语义分割。具体而言，我们首先用简单图像的显着图（即，具有单个类别的主要对象和干净背景的那些）的显着图来训练初始分割网络Initial-DCNN。这些显着图可以通过现有的自下而上的显着物体检测技术自动获得，其中不需要监督信息。然后，基于Initial-DCNN以及图像级注释，在预测的简单图像的分割掩模的监督下学习一个称为Enhanced-DCNN的更好的网络。最后，利用Enhanced-DCNN和图像级注释推导出复杂图像（背景杂乱的两类或多类物体）的更多像素级分割掩模作为监督信息学习Powerful-DCNN语义分割。我们的方法利用来自Flickr.com的$ 40 $ K简单图像和来自PASCAL VOC的10K复杂图像，用于逐步提升分割网络。 PASCAL VOC 2012分段基准的广泛实验结果很好地证明了与其他技术水平相比拟议STC框架的优越性。

##### URL
[https://arxiv.org/abs/1509.03150](https://arxiv.org/abs/1509.03150)

##### PDF
[https://arxiv.org/pdf/1509.03150](https://arxiv.org/pdf/1509.03150)

