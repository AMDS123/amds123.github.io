---
layout: post
title: "A Classifier-guided Approach for Top-down Salient Object Detection"
date: 2016-04-22 08:43:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Hisham Cholakkal, Jubin Johnson, Deepu Rajan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework for top-down salient object detection that incorporates a tightly coupled image classification module. The classifier is trained on novel category-aware sparse codes computed on object dictionaries used for saliency modeling. A misclassification indicates that the corresponding saliency model is inaccurate. Hence, the classifier selects images for which the saliency models need to be updated. The category-aware sparse coding produces better image classification accuracy as compared to conventional sparse coding with a reduced computational complexity. A saliency-weighted max-pooling is proposed to improve image classification, which is further used to refine the saliency maps. Experimental results on Graz-02 and PASCAL VOC-07 datasets demonstrate the effectiveness of salient object detection. Although the role of the classifier is to support salient object detection, we evaluate its performance in image classification and also illustrate the utility of thresholded saliency maps for image segmentation.

##### Abstract (translated by Google)
我们提出了一个自上而下的显着物体检测框架，其中包含一个紧密耦合的图像分类模块。该分类器被训练用于在用于显着性建模的对象词典上计算的新型分类感知稀疏码。错误分类表明相应的显着性模型是不准确的。因此，分类器选择需要更新显着性模型的图像。与传统的稀疏编码相比，类别感知的稀疏编码产生更好的图像分类精确度，且计算复杂度降低。提出了一种显着性加权最大化池，用于改善图像分类，进一步用于优化显着图。 Graz-02和PASCAL VOC-07数据集的实验结果证明了显着物体检测的有效性。尽管分类器的作用是支持显着的对象检测，但我们评估其在图像分类中的性能，并且还说明了阈值显着图对图像分割的效用。

##### URL
[https://arxiv.org/abs/1604.06570](https://arxiv.org/abs/1604.06570)

