---
layout: post
title: "Automatic segmentation of the spinal cord and intramedullary multiple sclerosis lesions with convolutional neural networks"
date: 2018-05-16 14:39:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Charley Gros, Benjamin De Leener, Atef Badji, Josefina Maranzano, Dominique Eden, Sara M. Dupont, Jason Talbott, Ren Zhuoquiong, Yaou Liu, Tobias Granberg, Russell Ouellette, Yasuhiko Tachibana, Masaaki Hori, Kouhei Kamiya, Lydia Chougar, Leszek Stawiarz, Jan Hillert, Elise Bannier, Anne Kerbrat, Gilles Edan, Pierre Labauge, Virginie Callot, Jean Pelletier, Bertrand Audoin, Henitsoa Rasoanandrianina, Jean-Christophe Brisset, Paola Valsasina, Maria A. Rocca, Massimo Filippi, Rohit Bakshi, Shahamat Tauhid, Ferran Prados, Marios Yiannakas, Hugh Kearney, Olga Ciccarelli, Seth Smith, Constantina Andrada Treaba, Caterina Mainero, Jennifer Lefeuvre, Daniel S. Reich, Govind Nair, Vincent Auclair, Donald G. McLaren, Allan R. Martin, Michael G. Fehlings, Shahabeddin Vahdat, Ali Khatibi, Julien Doyon, et al. (4 additional authors not shown)
mathjax: true
---

* content
{:toc}

##### Abstract
The spinal cord is frequently affected by atrophy and/or lesions in multiple sclerosis (MS) patients. Segmentation of the spinal cord and lesions from MRI data provides measures of atrophy and lesion burden, which are key criteria for the diagnosis, prognosis and longitudinal monitoring in MS. Achieving robust and reliable segmentation across multi-center spinal cord data is challenging because of the large variability related to acquisition parameters and image artifacts. In particular, a precise delineation of lesions is hindered by a broad heterogeneity of lesion contrast, size, location, and shape. The goal of this study was to develop a fully-automatic framework, robust to variability in both image parameters and clinical condition, for segmentation of the spinal cord and intramedullary MS lesions from conventional MRI data. 1042 adult subjects (459 healthy controls, 471 MS patients, and 112 with other spinal pathologies) were included in this multi-center study (n=30 centers). Data spanned 3 contrasts (T1-, T2- and T2*-weighted) for a total of 1943 volumes and featured large heterogeneity in terms of resolution, orientation, coverage and clinical conditions. The proposed cord and lesion automatic segmentation approach is based on a cascade of two Convolutional Neural Networks (CNN): a first CNN with 2D dilated convolutions detects the spinal cord centerline followed by a second 3D CNN that segments the spinal cord and lesions. When compared to a state-of-the-art spinal cord segmentation method (PropSeg), our CNN-based approach showed a median Dice of 95% vs. 88% for PropSeg. Regarding lesion segmentation, our framework, when compared with manual segmentation of MS patients, provided a lesion-wise detection sensitivity of 83%, a precision of 77%, a relative volume difference of 15%, and a Dice of 60%. The proposed framework is open-source and available in the Spinal Cord Toolbox.

##### Abstract (translated by Google)
多发性硬化症（MS）患者的脊髓经常受到萎缩和/或损伤的影响。 MRI数据对脊髓和病灶的分割提供了萎缩和病变负担的测量，这是MS诊断，预后和纵向监测的关键标准。由于与采集参数和图像伪影有很大的可变性，因此跨多中心脊髓数据实现稳健可靠的分割具有挑战性。特别是，病灶对比度，大小，位置和形状的广泛异质性阻碍了对病灶的精确划分。这项研究的目标是开发一个全自动框架，强大的图像参数和临床条件的可变性，从传统的MRI数据分割脊髓和髓内MS病变。这项多中心研究纳入了1042名成人受试者（459名健康对照者，471名MS患者和112名患有其他脊柱病变者）（n = 30个中心）。数据跨越了3个对比（T1-，T2-和T2 *  - 加权），总共1943卷，并且在分辨率，取向，覆盖范围和临床条件方面具有较大的异质性。所提出的线和病变自动分割的方法是基于两个卷积神经网络（CNN）的级联：使用二维卷积扩张的第一CNN检测脊髓中心线接着是第二3D CNN该段脊髓和病变。与先进的脊髓分割方法（PropSeg）相比，我们基于CNN的方法显示中位骰子为95％，而PropSeg为88％。关于病变分割，我们的框架与手动分割MS患者相比，提供了83％的病灶检测灵敏度，77％的精确度，15％的相对体积差异和60％的骰子。提议的框架是开源的，可在脊髓工具箱中找到。

##### URL
[http://arxiv.org/abs/1805.06349](http://arxiv.org/abs/1805.06349)

##### PDF
[http://arxiv.org/pdf/1805.06349](http://arxiv.org/pdf/1805.06349)

