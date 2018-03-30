---
layout: post
title: "PersonLab: Person Pose Estimation and Instance Segmentation with a Bottom-Up, Part-Based, Geometric Embedding Model"
date: 2018-03-22 04:31:02
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Embedding CNN Inference
author: George Papandreou, Tyler Zhu, Liang-Chieh Chen, Spyros Gidaris, Jonathan Tompson, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
We present a box-free bottom-up approach for the tasks of pose estimation and instance segmentation of people in multi-person images using an efficient single-shot model. The proposed PersonLab model tackles both semantic-level reasoning and object-part associations using part-based modeling. Our model employs a convolutional network which learns to detect individual keypoints and predict their relative displacements, allowing us to group keypoints into person pose instances. Further, we propose a part-induced geometric embedding descriptor which allows us to associate semantic person pixels with their corresponding person instance, delivering instance-level person segmentations. Our system is based on a fully-convolutional architecture and allows for efficient inference, with runtime essentially independent of the number of people present in the scene. Trained on COCO data alone, our system achieves COCO test-dev keypoint average precision of 0.665 using single-scale inference and 0.687 using multi-scale inference, significantly outperforming all previous bottom-up pose estimation systems. We are also the first bottom-up method to report competitive results for the person class in the COCO instance segmentation task, achieving a person category average precision of 0.417.

##### Abstract (translated by Google)
我们提出了一个无盒自下而上的方法，用于使用高效的单次模型对多人图像中的人进行姿态估计和实例分割。建议的PersonLab模型使用基于部件的建模来处理语义层推理和对象部分关联。我们的模型采用了卷积网络，可以学习检测各个关键点并预测它们的相对位移，从而使我们能够将关键点分组为人物姿势实例。此外，我们提出了一个部分诱导的几何嵌入描述符，它允许我们将语义人像素与其相应的人员实例相关联，从而提供实例级别的人员分段。我们的系统基于完全卷积体系结构，可以进行高效的推理，运行时间基本上与场景中出现的人数无关。仅依靠COCO数据训练，我们的系统通过单尺度推理获得了0.665的COCO测试 - 开发关键点平均精度，使用多尺度推理实现了0.687的COCO测试 - 开发关键点平均精度，明显优于所有以前的自下而上的姿势估计系统。我们也是第一种自下而上的自下而上方法来报告COCO实例分割任务中的人员类别的竞争结果，实现了人类分类平均精度为0.417。

##### URL
[https://arxiv.org/abs/1803.08225](https://arxiv.org/abs/1803.08225)

##### PDF
[https://arxiv.org/pdf/1803.08225](https://arxiv.org/pdf/1803.08225)

