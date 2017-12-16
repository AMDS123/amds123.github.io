---
layout: post
title: "A New Representation of Skeleton Sequences for 3D Action Recognition"
date: 2017-06-05 01:29:39
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Relation Recognition
author: Qiuhong Ke, Mohammed Bennamoun, Senjian An, Ferdous Sohel, Farid Boussaid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new method for 3D action recognition with skeleton sequences (i.e., 3D trajectories of human skeleton joints). The proposed method first transforms each skeleton sequence into three clips each consisting of several frames for spatial temporal feature learning using deep neural networks. Each clip is generated from one channel of the cylindrical coordinates of the skeleton sequence. Each frame of the generated clips represents the temporal information of the entire skeleton sequence, and incorporates one particular spatial relationship between the joints. The entire clips include multiple frames with different spatial relationships, which provide useful spatial structural information of the human skeleton. We propose to use deep convolutional neural networks to learn long-term temporal information of the skeleton sequence from the frames of the generated clips, and then use a Multi-Task Learning Network (MTLN) to jointly process all frames of the generated clips in parallel to incorporate spatial structural information for action recognition. Experimental results clearly show the effectiveness of the proposed new representation and feature learning method for 3D action recognition.

##### Abstract (translated by Google)
本文提出了一种利用骨架序列（即人体骨骼关节的三维轨迹）进行三维动作识别的新方法。所提出的方法首先将每个骨架序列转换成三个剪辑，每个剪辑由多个帧组成，以便利用深度神经网络进行空间时间特征学习每个剪辑是从骨架序列的圆柱坐标的一个通道生成的。生成的剪辑的每一帧表示整个骨架序列的时间信息，并且在关节之间包含一个特定的空间关系。整个剪辑包括具有不同空间关系的多个帧，从而提供有用的人体骨架的空间结构信息。我们建议使用深度卷积神经网络从生成的剪辑的帧中学习骨架序列的长期时间信息，然后使用多任务学习网络（MTLN）并行处理生成的剪辑的所有帧整合行动识别的空间结构信息。实验结果清楚地表明了所提出的新的表示和三维动作识别的特征学习方法的有效性。

##### URL
[https://arxiv.org/abs/1703.03492](https://arxiv.org/abs/1703.03492)

##### PDF
[https://arxiv.org/pdf/1703.03492](https://arxiv.org/pdf/1703.03492)

