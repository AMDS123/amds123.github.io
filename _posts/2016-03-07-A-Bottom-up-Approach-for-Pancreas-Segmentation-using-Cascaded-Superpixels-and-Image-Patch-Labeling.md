---
layout: post
title: "A Bottom-up Approach for Pancreas Segmentation using Cascaded Superpixels and Image Patch Labeling"
date: 2016-03-07 18:24:43
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Classification Quantitative
author: Amal Farag, Le Lu, Holger R. Roth, Jiamin Liu, Evrim Turkbey, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Robust automated organ segmentation is a prerequisite for computer-aided diagnosis (CAD), quantitative imaging analysis and surgical assistance. For high-variability organs such as the pancreas, previous approaches report undesirably low accuracies. We present a bottom-up approach for pancreas segmentation in abdominal CT scans that is based on a hierarchy of information propagation by classifying image patches at different resolutions; and cascading superpixels. There are four stages: 1) decomposing CT slice images as a set of disjoint boundary-preserving superpixels; 2) computing pancreas class probability maps via dense patch labeling; 3) classifying superpixels by pooling both intensity and probability features to form empirical statistics in cascaded random forest frameworks; and 4) simple connectivity based post-processing. The dense image patch labeling are conducted by: efficient random forest classifier on image histogram, location and texture features; and more expensive (but with better specificity) deep convolutional neural network classification on larger image windows (with more spatial contexts). Evaluation of the approach is performed on a database of 80 manually segmented CT volumes in six-fold cross-validation (CV). Our achieved results are comparable, or better than the state-of-the-art methods (evaluated by "leave-one-patient-out"), with Dice 70.7% and Jaccard 57.9%. The computational efficiency has been drastically improved in the order of 6~8 minutes, comparing with others of ~10 hours per case. Finally, we implement a multi-atlas label fusion (MALF) approach for pancreas segmentation using the same datasets. Under six-fold CV, our bottom-up segmentation method significantly outperforms its MALF counterpart: (70.7 +/- 13.0%) versus (52.5 +/- 20.8%) in Dice. Deep CNN patch labeling confidences offer more numerical stability, reflected by smaller standard deviations.

##### Abstract (translated by Google)
强大的自动器官分割是计算机辅助诊断（CAD），定量成像分析和手术辅助的先决条件。对于胰腺等高变异性器官，以前的方法报告不合要求的低精度。我们提出了一种自下而上的腹部CT扫描胰腺分割方法，该方法基于信息传播的层次结构，以不同的分辨率对图像块进行分类;和级联超像素。有四个阶段：1）将CT切片图像分解为一组不相交的边界保留超像素; 2）通过密集贴片标签计算胰腺类概率图; 3）通过汇集强度和概率特征对超级像素进行分类，形成级联随机森林框架下的经验统计;和4）简单的基于连接的后处理。密集的图像补丁标签是由图像直方图上的高效随机森林分类器，位置和纹理特征;并且在更大的图像窗口（具有更多的空间上下文）上更昂贵（但具有更好的特异性）的深度卷积神经网络分类。该方法的评估是在六次交叉验证（CV）的80个手动分割CT体积的数据库上进行的。我们取得的成果与最先进的方法（通过“一病人休假”评估）相当或者更好，骰子为70.7％，Jaccard为57.9％。计算效率已经大幅度提高了6〜8分钟，相比之下，每个案例的时间约为10个小时。最后，我们使用相同的数据集实现了胰腺分割的多图谱标签融合（MALF）方法。在六倍的CV下，我们的自下而上的分割方法显着优于MALF分支：（70.7 +/- 13.0％）与Dice中的（52.5 +/- 20.8％）。深CNN贴片标签置信度提供更多的数值稳定性，反映较小的标准偏差。

##### URL
[https://arxiv.org/abs/1505.06236](https://arxiv.org/abs/1505.06236)

##### PDF
[https://arxiv.org/pdf/1505.06236](https://arxiv.org/pdf/1505.06236)

