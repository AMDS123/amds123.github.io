---
layout: post
title: "SPF-CellTracker: Tracking multiple cells with strongly-correlated moves using a spatial particle filter"
date: 2016-05-27 19:52:44
categories: arXiv_CV
tags: arXiv_CV GAN Tracking Prediction
author: Osamu Hirose, Shotaro Kawaguchi, Terumasa Tokunaga, Yu Toyoshima, Takayuki Teramoto, Sayuri Kuge, Takeshi Ishihara, Yuichi Iino, Ryo Yoshida
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking many cells in time-lapse 3D image sequences is an important challenging task of bioimage informatics. Motivated by a study of brain-wide 4D imaging of neural activity in C. elegans, we present a new method of multi-cell tracking. Data types to which the method is applicable are characterized as follows: (i) cells are imaged as globular-like objects, (ii) it is difficult to distinguish cells based only on shape and size, (iii) the number of imaged cells ranges in several hundreds, (iv) moves of nearly-located cells are strongly correlated and (v) cells do not divide. We developed a tracking software suite which we call SPF-CellTracker. Incorporating dependency on cells' moves into prediction model is the key to reduce the tracking errors: cell-switching and coalescence of tracked positions. We model target cells' correlated moves as a Markov random field and we also derive a fast computation algorithm, which we call spatial particle filter. With the live-imaging data of nuclei of C. elegans neurons in which approximately 120 nuclei of neurons are imaged, we demonstrate an advantage of the proposed method over the standard particle filter and a method developed by Tokunaga et al. (2014).

##### Abstract (translated by Google)
跟踪时间推移3D图像序列中的许多细胞是生物信息学的一个重要的具有挑战性的任务。受到线虫中大脑四维神经活动成像研究的启发，我们提出了一种多细胞追踪的新方法。该方法适用的数据类型的特征如下：（i）细胞被成像为球状物体，（ii）难以仅基于形状和大小来区分细胞，（iii）成像细胞范围的数量在几百个中，（iv）几乎定位的细胞的移动强相关，（v）细胞不分裂。我们开发了一个我们称之为SPF-CellTracker的跟踪软件套件。将细胞依赖性移入预测模型是减少跟踪错误的关键：跟踪位置的细胞切换和合并。我们将目标细胞的相关运动建模为马尔可夫随机场，并推导出一种快速计算算法，我们称之为空间粒子滤波。利用线虫神经元细胞核的成像数据，对大约120个神经元细胞核进行成像，证明了该方法优于标准粒子滤波器和Tokunaga等人开发的方法。 （2014）。

##### URL
[https://arxiv.org/abs/1508.06464](https://arxiv.org/abs/1508.06464)

##### PDF
[https://arxiv.org/pdf/1508.06464](https://arxiv.org/pdf/1508.06464)

