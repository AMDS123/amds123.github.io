---
layout: post
title: "Recovering 6D Object Pose and Predicting Next-Best-View in the Crowd"
date: 2016-04-19 17:31:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Pose_Estimation Classification Prediction Detection
author: Andreas Doumanoglou, Rigas Kouskouridas, Sotiris Malassiotis, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection and 6D pose estimation in the crowd (scenes with multiple object instances, severe foreground occlusions and background distractors), has become an important problem in many rapidly evolving technological areas such as robotics and augmented reality. Single shot-based 6D pose estimators with manually designed features are still unable to tackle the above challenges, motivating the research towards unsupervised feature learning and next-best-view estimation. In this work, we present a complete framework for both single shot-based 6D object pose estimation and next-best-view prediction based on Hough Forests, the state of the art object pose estimator that performs classification and regression jointly. Rather than using manually designed features we a) propose an unsupervised feature learnt from depth-invariant patches using a Sparse Autoencoder and b) offer an extensive evaluation of various state of the art features. Furthermore, taking advantage of the clustering performed in the leaf nodes of Hough Forests, we learn to estimate the reduction of uncertainty in other views, formulating the problem of selecting the next-best-view. To further improve pose estimation, we propose an improved joint registration and hypotheses verification module as a final refinement step to reject false detections. We provide two additional challenging datasets inspired from realistic scenarios to extensively evaluate the state of the art and our framework. One is related to domestic environments and the other depicts a bin-picking scenario mostly found in industrial settings. We show that our framework significantly outperforms state of the art both on public and on our datasets.

##### Abstract (translated by Google)
人群中的对象检测和6D姿态估计（具有多个对象实例的场景，严重的前景遮挡和背景干扰）已经成为诸如机器人和增强现实等许多快速发展的技术领域中的重要问题。手动设计特征的基于单次拍摄的六维姿态估计器仍然无法解决上述挑战，从而激发了对无监督特征学习和次最佳视图估计的研究。在这项工作中，我们提出了一个基于Hough Forens的基于单次的6D对象姿态估计和次最佳视图预测的完整框架，这是一个共同执行分类和回归的艺术对象姿态估计器的状态。我们没有使用手动设计的特征，而是提出了一个使用稀疏自动编码器从深度不变的补丁中学习的无监督特征，b）提供了对各种先进特征的广泛评估。此外，利用Hough Forest叶子节点进行聚类，我们学会了估计其他视图中不确定性的减少，从而制定出选择次优视图的问题。为了进一步改善姿态估计，我们提出了一个改进的联合配准和假设验证模块，作为拒绝错误检测的最终细化步骤。我们提供了两个额外的具有挑战性的数据集，从现实情景中得到启发，广泛评估艺术和框架的状态。一个涉及到家庭环境，另一个涉及大多数在工业环境中使用的垃圾拣选场景。我们展示了我们的框架在公共和我们的数据集上都明显优于现有技术。

##### URL
[https://arxiv.org/abs/1512.07506](https://arxiv.org/abs/1512.07506)

##### PDF
[https://arxiv.org/pdf/1512.07506](https://arxiv.org/pdf/1512.07506)

