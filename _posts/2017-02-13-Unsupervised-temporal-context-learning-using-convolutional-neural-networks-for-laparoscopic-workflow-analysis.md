---
layout: post
title: "Unsupervised temporal context learning using convolutional neural networks for laparoscopic workflow analysis"
date: 2017-02-13 09:29:50
categories: arXiv_CV
tags: arXiv_CV Video_Indexing Knowledge Segmentation CNN Recognition
author: Sebastian Bodenstedt (1), Martin Wagner (2), Darko Katić (1), Patrick Mietkowski (2), Benjamin Mayer (2), Hannes Kenngott (2), Beat Müller-Stich (2), Rüdiger Dillmann (1), Stefanie Speidel (1) ((1) Institute for Anthropomatics and Robotics, Karlsruhe Institute of Technology, Karlsruhe, (2) Department of General, Visceral and Transplant Surgery, University of Heidelberg, Heidelberg)
mathjax: true
---

* content
{:toc}

##### Abstract
Computer-assisted surgery (CAS) aims to provide the surgeon with the right type of assistance at the right moment. Such assistance systems are especially relevant in laparoscopic surgery, where CAS can alleviate some of the drawbacks that surgeons incur. For many assistance functions, e.g. displaying the location of a tumor at the appropriate time or suggesting what instruments to prepare next, analyzing the surgical workflow is a prerequisite. Since laparoscopic interventions are performed via endoscope, the video signal is an obvious sensor modality to rely on for workflow analysis. Image-based workflow analysis tasks in laparoscopy, such as phase recognition, skill assessment, video indexing or automatic annotation, require a temporal distinction between video frames. Generally computer vision based methods that generalize from previously seen data are used. For training such methods, large amounts of annotated data are necessary. Annotating surgical data requires expert knowledge, therefore collecting a sufficient amount of data is difficult, time-consuming and not always feasible. In this paper, we address this problem by presenting an unsupervised method for training a convolutional neural network (CNN) to differentiate between laparoscopic video frames on a temporal basis. We extract video frames at regular intervals from 324 unlabeled laparoscopic interventions, resulting in a dataset of approximately 2.2 million images. From this dataset, we extract image pairs from the same video and train a CNN to determine their temporal order. To solve this problem, the CNN has to extract features that are relevant for comprehending laparoscopic workflow. Furthermore, we demonstrate that such a CNN can be adapted for surgical workflow segmentation. We performed image-based workflow segmentation on a publicly available dataset of 7 cholecystectomies and 9 colorectal interventions.

##### Abstract (translated by Google)
计算机辅助手术（CAS）旨在为外科医生提供恰当的帮助。这种辅助系统在腹腔镜手术中尤为重要，在这种手术中，CAS可以减轻外科医生带来的一些缺点。对于许多辅助功能，例如在适当的时间显示肿瘤的位置，或者提出下一步准备什么仪器，分析手术工作流程是一个先决条件。由于腹腔镜介入是通过内窥镜进行的，所以视频信号是依赖于工作流分析的明显的传感器模式。在腹腔镜检查中基于图像的工作流分析任务，例如相位识别，技能评估，视频索引或自动注释，需要视频帧之间的时间差异。通常使用基于计算机视觉的方法，其从先前看到的数据进行概括。为了训练这种方法，大量的注释数据是必要的。注释手术数据需要专业知识，因此收集足够数量的数据是困难的，耗时且不总是可行的。在本文中，我们通过提出一种用于训练卷积神经网络（CNN）的无监督方法来解决这个问题，以在时间基础上区分腹腔镜视频帧。我们从324个未标记的腹腔镜介入中定期提取视频帧，产生约220万张图像的数据集。从这个数据集中，我们从同一个视频中提取图像对并训练一个CNN来确定它们的时间顺序。为了解决这个问题，CNN必须提取与理解腹腔镜工作流相关的特征。此外，我们证明这样一个CNN可以适应手术工作流分割。我们在一个公开可用的7胆囊切除术和9结直肠癌干预数据集上进行基于图像的工作流程分割。

##### URL
[https://arxiv.org/abs/1702.03684](https://arxiv.org/abs/1702.03684)

##### PDF
[https://arxiv.org/pdf/1702.03684](https://arxiv.org/pdf/1702.03684)

