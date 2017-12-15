---
layout: post
title: "Synthesizing Training Images for Boosting Human 3D Pose Estimation"
date: 2017-01-05 08:09:00
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Wenzheng Chen, Huan Wang, Yangyan Li, Hao Su, Zhenhua Wang, Changhe Tu, Dani Lischinski, Daniel Cohen-Or, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Human 3D pose estimation from a single image is a challenging task with numerous applications. Convolutional Neural Networks (CNNs) have recently achieved superior performance on the task of 2D pose estimation from a single image, by training on images with 2D annotations collected by crowd sourcing. This suggests that similar success could be achieved for direct estimation of 3D poses. However, 3D poses are much harder to annotate, and the lack of suitable annotated training images hinders attempts towards end-to-end solutions. To address this issue, we opt to automatically synthesize training images with ground truth pose annotations. Our work is a systematic study along this road. We find that pose space coverage and texture diversity are the key ingredients for the effectiveness of synthetic training data. We present a fully automatic, scalable approach that samples the human pose space for guiding the synthesis procedure and extracts clothing textures from real images. Furthermore, we explore domain adaptation for bridging the gap between our synthetic training images and real testing photos. We demonstrate that CNNs trained with our synthetic images out-perform those trained with real photos on 3D pose estimation tasks.

##### Abstract (translated by Google)
来自单个图像的人类三维姿态估计是具有许多应用的具有挑战性的任务。卷积神经网络（CNN）最近已经在单个图像的2D姿态估计的任务上通过使用通过众包采集的2D注释对图像进行训练而取得了优异的性能。这表明类似的成功可以实现直接估计三维姿势。然而，3D姿势更难以注释，而缺乏合适的注释训练图像阻碍了尝试端到端的解决方案。为了解决这个问题，我们选择自动合成具有地面真实姿势注释的训练图像。我们的工作是沿着这条道路进行系统的研究。我们发现姿态空间覆盖和纹理多样性是综合训练数据有效性的关键因素。我们提出了一个全自动的，可扩展的方法，对人体姿势空间进行采样，以指导合成过程，并从真实图像中提取服装纹理。此外，我们还探索了适应领域，弥补了我们的综合训练图像和实际测试照片之间的差距。我们证明，使用我们的合成图像进行训练的CNN胜过那些在3D姿势估计任务上使用真实照片进行训练的人员。

##### URL
[https://arxiv.org/abs/1604.02703](https://arxiv.org/abs/1604.02703)

##### PDF
[https://arxiv.org/pdf/1604.02703](https://arxiv.org/pdf/1604.02703)

