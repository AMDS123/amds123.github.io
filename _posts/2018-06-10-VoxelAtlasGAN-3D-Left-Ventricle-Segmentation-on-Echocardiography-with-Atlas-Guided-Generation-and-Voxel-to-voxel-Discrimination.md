---
layout: post
title: "VoxelAtlasGAN: 3D Left Ventricle Segmentation on Echocardiography with Atlas Guided Generation and Voxel-to-voxel Discrimination"
date: 2018-06-10 09:25:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Segmentation GAN Face Optimization Inference Relation
author: Suyu Dong, Gongning Luo, Kuanquan Wang, Shaodong Cao, Ashley Mercado, Olga Shmuilovich, Henggui Zhang, Shuo Li
mathjax: true
---

* content
{:toc}

##### Abstract
3D left ventricle (LV) segmentation on echocardiography is very important for diagnosis and treatment of cardiac disease. It is not only because of that echocardiography is a real-time imaging technology and widespread in clinical application, but also because of that LV segmentation on 3D echocardiography can provide more full volume information of heart than LV segmentation on 2D echocardiography. However, 3D LV segmentation on echocardiography is still an open and challenging task owing to the lower contrast, higher noise and data dimensionality, limited annotation of 3D echocardiography. In this paper, we proposed a novel real-time framework, i.e., VoxelAtlasGAN, for 3D LV segmentation on 3D echocardiography. This framework has three contributions: 1) It is based on voxel-to-voxel conditional generative adversarial nets (cGAN). For the first time, cGAN is used for 3D LV segmentation on echocardiography. And cGAN advantageously fuses substantial 3D spatial context information from 3D echocardiography by self-learning structured loss; 2) For the first time, it embeds the atlas into an end-to-end optimization framework, which uses 3D LV atlas as a powerful prior knowledge to improve the inference speed, address the lower contrast and the limited annotation problems of 3D echocardiography; 3) It combines traditional discrimination loss and the new proposed consistent constraint, which further improves the generalization of the proposed framework. VoxelAtlasGAN was validated on 60 subjects on 3D echocardiography and it achieved satisfactory segmentation results and high inference speed. The mean surface distance is 1.85 mm, the mean hausdorff surface distance is 7.26 mm, mean dice is 0.953, the correlation of EF is 0.918, and the mean inference speed is 0.1s. These results have demonstrated that our proposed method has great potential for clinical application

##### Abstract (translated by Google)
超声心动图的3D左心室（LV）分割对心脏疾病的诊断和治疗非常重要。这不仅仅是因为超声心动图是一种实时成像技术并且在临床应用中广泛存在，而且还因为三维超声心动图的LV分割可以提供比二维超声心动图LV分割更全面的心脏体积信息。然而，由于对比度较低，噪声和数据维数较高，三维超声心动图的注释有限，超声心动图3D LV分割仍是一项开放且具有挑战性的任务。在本文中，我们提出了一种新颖的实时框架，即VoxelAtlasGAN，用于三维超声心动图的三维LV分割。这个框架有三个贡献：1）它基于体素到体素条件生成对抗网络（cGAN）。 cGAN首次用于超声心动图的三维LV分割。并且cGAN通过自学习结构化损失有利地融合来自3D超声心动图的实质性3D空间情境信息; 2）首次将地图集嵌入到端到端的优化框架中，该框架使用3D LV地图集作为强大的先验知识来提高推理速度，解决3D超声心动图对比度低和注记有限的问题; 3）它将传统的歧视损失和新提出的一致性约束相结合，进一步改进了拟议框架的推广。 VoxelAtlasGAN在三维超声心动图上的60名受试者中得到验证，并且获得了令人满意的分割结果和高推断速度。平均表面距离为1.85毫米，平均hausdorff表面距离为7.26毫米，平均骰子为0.953，EF的相关系数为0.918，平均推理速度为0.1秒。这些结果表明，我们提出的方法具有很大的临床应用潜力

##### URL
[http://arxiv.org/abs/1806.03619](http://arxiv.org/abs/1806.03619)

##### PDF
[http://arxiv.org/pdf/1806.03619](http://arxiv.org/pdf/1806.03619)

