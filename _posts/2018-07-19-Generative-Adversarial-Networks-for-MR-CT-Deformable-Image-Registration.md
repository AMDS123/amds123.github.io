---
layout: post
title: "Generative Adversarial Networks for MR-CT Deformable Image Registration"
date: 2018-07-19 11:41:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Relation
author: Christine Tanner, Firat Ozdemir, Romy Profanter, Valeriy Vishnevsky, Ender Konukoglu, Orcun Goksel
mathjax: true
---

* content
{:toc}

##### Abstract
Deformable Image Registration (DIR) of MR and CT images is one of the most challenging registration task, due to the inherent structural differences of the modalities and the missing dense ground truth. Recently cycle Generative Adversarial Networks (cycle-GANs) have been used to learn the intensity relationship between these 2 modalities for unpaired brain data. Yet its usefulness for DIR was not assessed. In this study we evaluate the DIR performance for thoracic and abdominal organs after synthesis by cycle-GAN. We show that geometric changes, which differentiate the two populations (e.g. inhale vs. exhale), are readily synthesized as well. This causes substantial problems for any application which relies on spatial correspondences being preserved between the real and the synthesized image (e.g. plan, segmentation, landmark propagation). To alleviate this problem, we investigated reducing the spatial information provided to the discriminator by decreasing the size of its receptive fields. Image synthesis was learned from 17 unpaired subjects per modality. Registration performance was evaluated with respect to manual segmentations of 11 structures for 3 subjects from the VISERAL challenge. State-of-the-art DIR methods based on Normalized Mutual Information (NMI), Modality Independent Neighborhood Descriptor (MIND) and their novel combination achieved a mean segmentation overlap ratio of 76.7, 67.7, 76.9%, respectively. This dropped to 69.1% or less when registering images synthesized by cycle-GAN based on local correlation, due to the poor performance on the thoracic region, where large lung volume changes were synthesized. Performance for the abdominal region was similar to that of CT-MRI NMI registration (77.4 vs. 78.8%) when using 3D synthesizing MRIs (12 slices) and medium sized receptive fields for the discriminator.

##### Abstract (translated by Google)
MR和CT图像的可变形图像配准（DIR）是最具挑战性的配准任务之一，因为模态的固有结构差异和缺失的密集地面实况。最近循环生成性对抗网络（cycle-GANs）已被用于学习这两种不成对脑数据模态之间的强度关系。然而，没有评估其对DIR的有用性。在本研究中，我们评估了通过循环-GAN合成后胸部和腹部器官的DIR性能。我们表明，区分两个种群（例如吸气与呼气）的几何变化也很容易合成。这对于依赖于在真实和合成图像之间保留空间对应的任何应用（例如，平面图，分割，界标传播）而言都会引起实质性问题。为了缓解这个问题，我们研究了通过减小​​其感知域的大小来减少提供给鉴别器的空间信息。每种方式从17个未配对的受试者中学习图像合成。针对来自VISERAL挑战的3个受试者的11个结构的手动分割评估了登记性能。基于归一化互信息（NMI），模态独立邻域描述符（MIND）及其新颖组合的现有技术DIR方法实现了平均分段重叠率分别为76.7,67.7,76.9％。当基于局部相关性记录由循环-GAN合成的图像时，由于在合成大的肺容积变化的胸部区域上的不良性能，这下降到69.1％或更低。当使用3D合成MRI（12个切片）和中等大小的感受野用于鉴别器时，腹部区域的性能类似于CT-MRI NMI配准（77.4对78.8％）。

##### URL
[https://arxiv.org/abs/1807.07349](https://arxiv.org/abs/1807.07349)

##### PDF
[https://arxiv.org/pdf/1807.07349](https://arxiv.org/pdf/1807.07349)

