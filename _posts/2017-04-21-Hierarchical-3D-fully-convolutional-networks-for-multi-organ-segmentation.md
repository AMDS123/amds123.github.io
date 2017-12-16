---
layout: post
title: "Hierarchical 3D fully convolutional networks for multi-organ segmentation"
date: 2017-04-21 03:05:15
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Prediction
author: Holger R. Roth, Hirohisa Oda, Yuichiro Hayashi, Masahiro Oda, Natsuki Shimizu, Michitaka Fujiwara, Kazunari Misawa, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in 3D fully convolutional networks (FCN) have made it feasible to produce dense voxel-wise predictions of full volumetric images. In this work, we show that a multi-class 3D FCN trained on manually labeled CT scans of seven abdominal structures (artery, vein, liver, spleen, stomach, gallbladder, and pancreas) can achieve competitive segmentation results, while avoiding the need for handcrafting features or training organ-specific models. To this end, we propose a two-stage, coarse-to-fine approach that trains an FCN model to roughly delineate the organs of interest in the first stage (seeing $\sim$40% of the voxels within a simple, automatically generated binary mask of the patient's body). We then use these predictions of the first-stage FCN to define a candidate region that will be used to train a second FCN. This step reduces the number of voxels the FCN has to classify to $\sim$10% while maintaining a recall high of $>$99%. This second-stage FCN can now focus on more detailed segmentation of the organs. We respectively utilize training and validation sets consisting of 281 and 50 clinical CT images. Our hierarchical approach provides an improved Dice score of 7.5 percentage points per organ on average in our validation set. We furthermore test our models on a completely unseen data collection acquired at a different hospital that includes 150 CT scans with three anatomical labels (liver, spleen, and pancreas). In such challenging organs as the pancreas, our hierarchical approach improves the mean Dice score from 68.5 to 82.2%, achieving the highest reported average score on this dataset.

##### Abstract (translated by Google)
3D全卷积网络（FCN）的最新进展已经使得生成全体积图像的密集体素预测成为可能。在这项工作中，我们展示了一个多级三维FCN在七个腹部结构（动脉，静脉，肝脏，脾脏，胃，胆囊和胰腺）的手动标记的CT扫描上训练可以实现竞争性分割结果，同时避免手工制作功能或训练器官特定的模型。为此，我们提出了一个两阶段的，从粗到精的方法，它训练一个FCN模型，在第一阶段粗略描述感兴趣的器官（在一个简单的自动生成的二进制数中看$ 40％的体素病人的面具）。然后，我们使用这些第一阶段FCN的预测来定义将用于训练第二FCN的候选区域。这个步骤减少了FCN必须分类的体素数量$ \ sim $ 10％，同时保持高达$> 99％的召回率。这个第二阶段的FCN现在可以集中于器官的更详细的分割。我们分别使用由281和50个临床CT图像组成的训练和验证集。我们的分层方法在我们的验证集中平均提高了每个器官7.5个百分点的Dice评分。我们进一步测试我们的模型，在一个完全不可见的数据收集在不同的医院获得，包括150个CT扫描与三个解剖标签（肝脏，脾脏和胰腺）。在像胰腺这样具有挑战性的器官中，我们的分层方法将骰子平均得分从68.5％提高到82.2％，在这个数据集上达到了最高的平均得分。

##### URL
[https://arxiv.org/abs/1704.06382](https://arxiv.org/abs/1704.06382)

##### PDF
[https://arxiv.org/pdf/1704.06382](https://arxiv.org/pdf/1704.06382)

