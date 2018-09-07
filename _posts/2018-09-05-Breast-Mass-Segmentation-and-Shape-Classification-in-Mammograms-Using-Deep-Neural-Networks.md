---
layout: post
title: "Breast Mass Segmentation and Shape Classification in Mammograms Using Deep Neural Networks"
date: 2018-09-05 18:40:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Classification Detection
author: Vivek Kumar Singh, Hatem A. Rashwan, Santiago Romani, Farhan Akram, Nidhi Pandey, Md. Mostafa Kamal Sarker, Adel Saleh, Meritexell Arenas, Miguel Arquez, Domenec Puig, Jordina Torrents-Barrena
mathjax: true
---

* content
{:toc}

##### Abstract
Mammogram analysis to manually extract breast masses is a tough assignment that radiologists must frequently carry out. Therefore, image analysis methods are needed for the detection and delineation of breast masses, which portray crucial morphological information that will support reliable diagnosis. In this paper, we proposed a conditional Generative Adversarial Network (cGAN) devised to segment a breast mass within a region of interest (ROI) in a mammogram. The generative network learns to recognize the breast mass area and to create the binary mask that outlines the breast mass. In turn, the adversarial network learns to distinguish between real (ground truth) and synthetic segmentations, thus enforcing the generative network to create binary masks as realistic as possible. The cGAN works well even when the number of training samples are limited. Therefore, the proposed method outperforms several state-of-the-art approaches. This hypothesis is corroborated by diverse experiments performed on two datasets, the public INbreast and a private in-house dataset. The proposed segmentation model provides a high Dice coefficient and Intersection over Union (IoU) of 94% and 87%, respectively. In addition, a shape descriptor based on a Convolutional Neural Network (CNN) is proposed to classify the generated masks into four mass shapes: irregular, lobular, oval and round. The proposed shape descriptor was trained on Digital Database for Screening Mammography (DDSM) yielding an overall accuracy of 80%, which outperforms the current state-of-the-art.

##### Abstract (translated by Google)
手动提取乳房肿块的乳房X光检查分析是放射科医生必须经常进行的艰巨任务。因此，需要图像分析方法来检测和描绘乳房肿块，其描绘了将支持可靠诊断的关键形态学信息。在本文中，我们提出了一种条件生成对抗网络（cGAN），用于在乳房X线照片中分割感兴趣区域（ROI）内的乳房肿块。生成网络学会识别乳房肿块区域并创建概述乳房肿块的二元面罩。反过来，对抗性网络学会区分真实（地面实况）和合成分割，从而强制生成网络以尽可能真实地创建二进制掩模。即使训练样本的数量有限，cGAN也能很好地工作。因此，所提出的方法优于几种最先进的方法。在两个数据集上进行的各种实验，即公共INbreast和私人内部数据集，证实了这一假设。所提出的分割模型提供了高Dice系数和联合交叉（IoU）分别为94％和87％。另外，提出了基于卷积神经网络（CNN）的形状描述符，以将生成的掩模分类为四种质量形状：不规则形，小叶形，椭圆形和圆形。所提出的形状描述符在用于筛选乳腺摄影（DDSM）的数字数据库上进行训练，产生80％的总体准确度，其优于当前的最新技术水平。

##### URL
[http://arxiv.org/abs/1809.01687](http://arxiv.org/abs/1809.01687)

##### PDF
[http://arxiv.org/pdf/1809.01687](http://arxiv.org/pdf/1809.01687)

