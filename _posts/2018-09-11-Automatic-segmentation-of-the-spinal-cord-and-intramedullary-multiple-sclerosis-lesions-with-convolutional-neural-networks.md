---
layout: post
title: "Automatic segmentation of the spinal cord and intramedullary multiple sclerosis lesions with convolutional neural networks"
date: 2018-09-11 22:45:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Charley Gros, Benjamin De Leener, Atef Badji, Josefina Maranzano, Dominique Eden, Sara M. Dupont, Jason Talbott, Ren Zhuoquiong, Yaou Liu, Tobias Granberg, Russell Ouellette, Yasuhiko Tachibana, Masaaki Hori, Kouhei Kamiya, Lydia Chougar, Leszek Stawiarz, Jan Hillert, Elise Bannier, Anne Kerbrat, Gilles Edan, Pierre Labauge, Virginie Callot, Jean Pelletier, Bertrand Audoin, Henitsoa Rasoanandrianina, Jean-Christophe Brisset, Paola Valsasina, Maria A. Rocca, Massimo Filippi, Rohit Bakshi, Shahamat Tauhid, Ferran Prados, Marios Yiannakas, Hugh Kearney, Olga Ciccarelli, Seth Smith, Constantina Andrada Treaba, Caterina Mainero, Jennifer Lefeuvre, Daniel S. Reich, Govind Nair, Vincent Auclair, Donald G. McLaren, Allan R. Martin, Michael G. Fehlings, Shahabeddin Vahdat, Ali Khatibi, Julien Doyon, et al. (4 additional authors not shown)
mathjax: true
---

* content
{:toc}

##### Abstract
The spinal cord is frequently affected by atrophy and/or lesions in multiple sclerosis (MS) patients. Segmentation of the spinal cord and lesions from MRI data provides measures of damage, which are key criteria for the diagnosis, prognosis, and longitudinal monitoring in MS. Automating this operation eliminates inter-rater variability and increases the efficiency of large-throughput analysis pipelines. Robust and reliable segmentation across multi-site spinal cord data is challenging because of the large variability related to acquisition parameters and image artifacts. The goal of this study was to develop a fully-automatic framework, robust to variability in both image parameters and clinical condition, for segmentation of the spinal cord and intramedullary MS lesions from conventional MRI data. Scans of 1,042 subjects (459 healthy controls, 471 MS patients, and 112 with other spinal pathologies) were included in this multi-site study (n=30). Data spanned three contrasts (T1-, T2-, and T2*-weighted) for a total of 1,943 volumes. The proposed cord and lesion automatic segmentation approach is based on a sequence of two Convolutional Neural Networks (CNNs). To deal with the very small proportion of spinal cord and/or lesion voxels compared to the rest of the volume, a first CNN with 2D dilated convolutions detects the spinal cord centerline, followed by a second CNN with 3D convolutions that segments the spinal cord and/or lesions. When compared against manual segmentation, our CNN-based approach showed a median Dice of 95% vs. 88% for PropSeg, a state-of-the-art spinal cord segmentation method. Regarding lesion segmentation on MS data, our framework provided a Dice of 60%, a relative volume difference of -15%, and a lesion-wise detection sensitivity and precision of 83% and 77%, respectively. The proposed framework is open-source and readily available in the Spinal Cord Toolbox.

##### Abstract (translated by Google)
脊髓经常受到多发性硬化（MS）患者的萎缩和/或损伤的影响。从MRI数据中分割脊髓和病变提供了损伤的测量，这是MS的诊断，预后和纵向监测的关键标准。自动执行此操作可消除评估者之间的差异，并提高大吞吐量分析管道的效率。由于与采集参数和图像伪像相关的大的可变性，跨多位点脊髓数据的稳健且可靠的分割是具有挑战性的。本研究的目的是开发一种全自动框架，对图像参数和临床状况的可变性具有鲁棒性，可用于从传统MRI数据中分割脊髓和髓内MS病变。在这项多地点研究中纳入了1,042名受试者（459名健康对照，471名MS患者和112名其他脊柱病变）的扫描（n = 30）。数据跨越三个对比（T1-，T2-和T2 *  - 加权），共计1,943卷。所提出的脐带和病变自动分割方法基于两个卷积神经网络（CNN）的序列。为了处理与体积的其余部分相比非常小比例的脊髓和/或病变体素，第一个具有2D扩张卷曲的CNN检测到脊髓中心线，接着是第二个CNN，其具有分割脊髓的3D卷曲和/或病变。与手动分割相比，我们的基于CNN的方法显示中位数骰子为95％，而PropSeg为88％，这是一种先进的脊髓分割方法。关于MS数据的病变分割，我们的框架提供了60％的骰子，相对体积差异为-15％，并且病变检测灵敏度和精确度分别为83％和77％。拟议的框架是开源的，并且可以在脊髓工具箱中随时使用。

##### URL
[http://arxiv.org/abs/1805.06349](http://arxiv.org/abs/1805.06349)

##### PDF
[http://arxiv.org/pdf/1805.06349](http://arxiv.org/pdf/1805.06349)

