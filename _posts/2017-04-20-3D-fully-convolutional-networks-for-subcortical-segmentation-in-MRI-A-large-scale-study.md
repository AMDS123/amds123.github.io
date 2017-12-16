---
layout: post
title: "3D fully convolutional networks for subcortical segmentation in MRI: A large-scale study"
date: 2017-04-20 02:03:35
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Embedding CNN Inference Prediction
author: J. Dolz, C. Desrosiers, I. Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
This study investigates a 3D and fully convolutional neural network (CNN) for subcortical brain structure segmentation in MRI. 3D CNN architectures have been generally avoided due to their computational and memory requirements during inference. We address the problem via small kernels, allowing deeper architectures. We further model both local and global context by embedding intermediate-layer outputs in the final prediction, which encourages consistency between features extracted at different scales and embeds fine-grained information directly in the segmentation process. Our model is efficiently trained end-to-end on a graphics processing unit (GPU), in a single stage, exploiting the dense inference capabilities of fully CNNs. We performed comprehensive experiments over two publicly available datasets. First, we demonstrate a state-of-the-art performance on the ISBR dataset. Then, we report a {\em large-scale} multi-site evaluation over 1112 unregistered subject datasets acquired from 17 different sites (ABIDE dataset), with ages ranging from 7 to 64 years, showing that our method is robust to various acquisition protocols, demographics and clinical factors. Our method yielded segmentations that are highly consistent with a standard atlas-based approach, while running in a fraction of the time needed by atlas-based methods and avoiding registration/normalization steps. This makes it convenient for massive multi-site neuroanatomical imaging studies. To the best of our knowledge, our work is the first to study subcortical structure segmentation on such large-scale and heterogeneous data.

##### Abstract (translated by Google)
这项研究调查了三维和完全卷积神经网络（CNN）的皮质下脑结构分割在MRI。由于在推理期间的计算和存储需求，3D CNN体系结构一般被避免。我们通过小内核来解决这个问题，从而允许更深层的体系结构。我们通过在最终预测中嵌入中间层输出来进一步模拟局部和全局的情况，这促进了不同尺度下提取的特征之间的一致性，并直接在细分过程中嵌入细粒度的信息。我们的模型在图形处理单元（GPU）上进行了端到端的高效培训，可以在单个阶段利用完全CNN的密集推理功能。我们对两个公开可用的数据集进行了全面的实验。首先，我们展示ISBR数据集上最先进的性能。然后，我们报告了对1112个从17个不同地点（ABIDE数据集）获得的未登记的主题数据集进行了大规模的多站点评估，年龄从7岁到64岁不等，表明我们的方法对各种采集协议，人口统计学和临床​​因素。我们的方法产生了与基于标准的基于图谱的方法高度一致的分割，同时运行在基于图谱的方法所需的一小部分时间，并避免了注册/标准化步骤。这使得大规模的多部位神经解剖成像研究变得方便。据我们所知，我们的工作是第一个研究这种大规模和异构数据的皮质下结构分割。

##### URL
[https://arxiv.org/abs/1612.03925](https://arxiv.org/abs/1612.03925)

##### PDF
[https://arxiv.org/pdf/1612.03925](https://arxiv.org/pdf/1612.03925)

