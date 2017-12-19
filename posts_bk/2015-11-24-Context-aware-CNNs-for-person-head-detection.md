---
layout: post
title: "Context-aware CNNs for person head detection"
date: 2015-11-24 23:23:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection Relation
author: Tuan-Hung Vu, Anton Osokin, Ivan Laptev
mathjax: true
---

* content
{:toc}

##### Abstract
Person detection is a key problem for many computer vision tasks. While face detection has reached maturity, detecting people under a full variation of camera view-points, human poses, lighting conditions and occlusions is still a difficult challenge. In this work we focus on detecting human heads in natural scenes. Starting from the recent local R-CNN object detector, we extend it with two types of contextual cues. First, we leverage person-scene relations and propose a Global CNN model trained to predict positions and scales of heads directly from the full image. Second, we explicitly model pairwise relations among objects and train a Pairwise CNN model using a structured-output surrogate loss. The Local, Global and Pairwise models are combined into a joint CNN framework. To train and test our full model, we introduce a large dataset composed of 369,846 human heads annotated in 224,740 movie frames. We evaluate our method and demonstrate improvements of person head detection against several recent baselines in three datasets. We also show improvements of the detection speed provided by our model.

##### Abstract (translated by Google)
人员检测是许多计算机视觉任务的关键问题。虽然人脸检测已经成熟，但在完整的摄像机视点，人体姿势，光照条件和遮挡情况下检测人员仍然是一个难题。在这项工作中，我们专注于在自然场景中检测人头。从最近的本地R-CNN对象检测器开始，我们用两种上下文线索来扩展它。首先，我们利用人际关系，并提出一个全球CNN模型，训练直接从完整图像预测头部的位置和尺度。其次，我们明确地建模对象之间的成对关系，并使用结构化输出替代损失来训练一个成对的CNN模型。本地，全球和成对的模式被合并为一个CNN联合框架。为了训练和测试我们的完整模型，我们引入了由224,740个电影帧注释的369,846个人头组成的大数据集。我们评估我们的方法，并在三个数据集中显示人头检测与几个最近基线的改进。我们还展示了由我们的模型提供的检测速度的改进。

##### URL
[https://arxiv.org/abs/1511.07917](https://arxiv.org/abs/1511.07917)

##### PDF
[https://arxiv.org/pdf/1511.07917](https://arxiv.org/pdf/1511.07917)

