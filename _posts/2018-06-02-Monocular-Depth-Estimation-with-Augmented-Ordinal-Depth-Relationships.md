---
layout: post
title: "Monocular Depth Estimation with Augmented Ordinal Depth Relationships"
date: 2018-06-02 05:52:32
categories: arXiv_CV
tags: arXiv_CV Classification Prediction Relation
author: Yuanzhouhan Cao, Tianqi Zhao, Ke Xian, Chunhua Shen, Zhiguo Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing algorithms for depth estimation from single monocular images need large quantities of metric groundtruth depths for supervised learning. We show that relative depth can be an informative cue for metric depth estimation and can be easily obtained from vast stereo videos. Acquiring metric depths from stereo videos is sometimes impracticable due to the absence of camera parameters. In this paper, we propose to improve the performance of metric depth estimation with relative depths collected from stereo movie videos using existing stereo matching algorithm. We introduce a new "Relative Depth in Stereo" (RDIS) dataset densely labelled with relative depths. We first pretrain a ResNet model on our RDIS dataset. Then we finetune the model on RGB-D datasets with metric ground-truth depths. During our finetuning, we formulate depth estimation as a classification task. This re-formulation scheme enables us to obtain the confidence of a depth prediction in the form of probability distribution. With this confidence, we propose an information gain loss to make use of the predictions that are close to ground-truth. We evaluate our approach on both indoor and outdoor benchmark RGB-D datasets and achieve state-of-the-art performance.

##### Abstract (translated by Google)
大多数现有的单眼图像深度估计算法都需要大量的度量基准深度来进行监督学习。我们表明，相对深度可以是度量深度估计的信息提示，并可以从庞大的立体视频轻松获得。由于缺少相机参数，从立体视频获取度量深度有时不切实际。在本文中，我们建议使用现有的立体匹配算法从立体电影视频中收集相对深度，以提高度量深度估计的性能。我们引入了一种新的“立体相对深度”（RDIS）数据集，该数据集密集地标有相对深度。我们首先在我们的RDIS数据集上预编译一个ResNet模型。然后我们使用度量地面真实深度对RGB-D数据集上的模型进行微调。在我们的微调过程中，我们将深度估计作为分类任务。这种重新制定方案使我们能够以概率分布的形式获得深度预测的置信度。有了这种信心，我们提出一个信息获取损失来利用接近真实的预测。我们在室内和室外基准RGB-D数据集上评估我们的方法，并实现最先进的性能。

##### URL
[http://arxiv.org/abs/1806.00585](http://arxiv.org/abs/1806.00585)

##### PDF
[http://arxiv.org/pdf/1806.00585](http://arxiv.org/pdf/1806.00585)

