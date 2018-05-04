---
layout: post
title: "A generalizable approach for multi-view 3D human pose regression"
date: 2018-04-27 12:14:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Abdolrahim Kadkhodamohammadi, Nicolas Padoy
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the significant improvement in the performance of monocular pose estimation approaches and their ability to generalize to unseen environments, multi-view (MV) approaches are often lagging behind in terms of accuracy and are specific to certain datasets. This is mainly due to the fact that (1) contrary to real world single-view (SV) datasets, MV datasets are often captured in controlled environments to collect precise 3D annotations, which do not cover all real world challenges, and (2) the model parameters are learned for specific camera setups. To alleviate these problems, we propose a two-stage approach to detect and estimate 3D human poses, which separates SV pose detection from MV 3D pose estimation. This separation enables us to utilize each dataset for the right task, i.e. SV datasets for constructing robust pose detection models and MV datasets for constructing precise MV 3D regression models. In addition, our 3D regression approach only requires 3D pose data and its projections to the views for building the model, hence removing the need for collecting annotated data from the test setup. Our approach can therefore be easily generalized to a new environment by simply projecting 3D poses into 2D during training according to the camera setup used at test time. As 2D poses are collected at test time using a SV pose detector, which might generate inaccurate detections, we model its characteristics and incorporate this information during training. We demonstrate that incorporating the detector's characteristics is important to build a robust 3D regression model and that the resulting regression model generalizes well to new MV environments. Our evaluation results show that our approach achieves competitive results on the Human3.6M dataset and significantly improves results on a MV clinical dataset that is the first MV dataset generated from live surgery recordings.

##### Abstract (translated by Google)
尽管单眼姿态估计方法的性能有明显改善，并且能够推广到看不见的环境，但多视图（MV）方法在准确性方面往往落后，并且特定于某些数据集。这主要归因于以下事实：（1）与现实世界单视图（SV）数据集相反，MV数据集通常在受控环境中捕获以收集精确的3D注释，其不覆盖所有现实世界的挑战，以及（2）学习了特定相机设置的模型参数。为了缓解这些问题，我们提出了一种两阶段方法来检测和估计3D人体姿势，其将SV姿势检测与MV 3D姿态估计分开。这种分离使得我们能够将每个数据集用于正确的任务，即SV数据集用于构建鲁棒的姿态检测模型和MV数据集，用于构建精确的MV 3D回归模型。此外，我们的3D回归方法仅需要3D姿态数据及其对构建模型的视图的投影，因此无需从测试设置收集注释数据。因此，根据测试时使用的相机设置，在训练过程中将3D姿势简单地投影到2D中，可以轻松将我们的方法推广到新的环境。由于2D姿势是在测试时间使用SV姿势检测器收集的，这可能会产生不准确的检测结果，因此我们对其特征进行建模并在训练期间合并这些信息。我们证明，结合探测器的特性对建立一个强大的三维回归模型非常重要，并且所得到的回归模型可以很好地推广到新的MV环境。我们的评估结果显示，我们的方法在Human3.6M数据集上实现了有竞争力的结果，并显着改善了MV临床数据集的结果，该数据集是首次通过实况手术记录生成的MV数据集。

##### URL
[https://arxiv.org/abs/1804.10462](https://arxiv.org/abs/1804.10462)

##### PDF
[https://arxiv.org/pdf/1804.10462](https://arxiv.org/pdf/1804.10462)

