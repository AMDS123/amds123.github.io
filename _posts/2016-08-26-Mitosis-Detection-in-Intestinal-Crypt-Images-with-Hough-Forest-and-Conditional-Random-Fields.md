---
layout: post
title: "Mitosis Detection in Intestinal Crypt Images with Hough Forest and Conditional Random Fields"
date: 2016-08-26 21:53:30
categories: arXiv_CV
tags: arXiv_CV OCR Detection
author: Gerda Bortsova, Michael Sterr, Lichao Wang, Fausto Milletari, Nassir Navab, Anika Böttcher, Heiko Lickert, Fabian Theis, Tingying Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Intestinal enteroendocrine cells secrete hormones that are vital for the regulation of glucose metabolism but their differentiation from intestinal stem cells is not fully understood. Asymmetric stem cell divisions have been linked to intestinal stem cell homeostasis and secretory fate commitment. We monitored cell divisions using 4D live cell imaging of cultured intestinal crypts to characterize division modes by means of measurable features such as orientation or shape. A statistical analysis of these measurements requires annotation of mitosis events, which is currently a tedious and time-consuming task that has to be performed manually. To assist data processing, we developed a learning based method to automatically detect mitosis events. The method contains a dual-phase framework for joint detection of dividing cells (mothers) and their progeny (daughters). In the first phase we detect mother and daughters independently using Hough Forest whilst in the second phase we associate mother and daughters by modelling their joint probability as Conditional Random Field (CRF). The method has been evaluated on 32 movies and has achieved an AUC of 72%, which can be used in conjunction with manual correction and dramatically speed up the processing pipeline.

##### Abstract (translated by Google)
肠内分泌细胞分泌激素对于糖代谢的调节是至关重要的，但是它们与肠干细胞的分化尚不完全清楚。不对称干细胞分裂已经与肠干细胞体内平衡和分泌命运承诺相关联。我们监测细胞分裂使用4D活细胞成像的培养肠隐窝通过可测量的特征，如方向或形状来表征分割模式。对这些测量的统计分析需要对有丝分裂事件进行标注，目前这是一项繁琐且耗时的工作，必须手动完成。为了协助数据处理，我们开发了一种基于学习的方法来自动检测有丝分裂事件。该方法包含一个联合检测分裂细胞（母亲）及其后代（女儿）的双阶段框架。在第一阶段，我们独立使用Hough Forest检测母亲和女儿，而在第二阶段，我们通过将他们的联合概率建模为条件随机场（CRF）来将母亲和女儿联系起来。该方法已经在32部电影上评估过，并且达到了72％的AUC，可以与手动校正结合使用，大大加快了处理流程。

##### URL
[https://arxiv.org/abs/1608.07616](https://arxiv.org/abs/1608.07616)

##### PDF
[https://arxiv.org/pdf/1608.07616](https://arxiv.org/pdf/1608.07616)

