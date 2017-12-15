---
layout: post
title: "We don't need no bounding-boxes: Training object class detectors using only human verification"
date: 2017-04-24 12:14:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Dim P. Papadopoulos, Jasper R. R. Uijlings, Frank Keller, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Training object class detectors typically requires a large set of images in which objects are annotated by bounding-boxes. However, manually drawing bounding-boxes is very time consuming. We propose a new scheme for training object detectors which only requires annotators to verify bounding-boxes produced automatically by the learning algorithm. Our scheme iterates between re-training the detector, re-localizing objects in the training images, and human verification. We use the verification signal both to improve re-training and to reduce the search space for re-localisation, which makes these steps different to what is normally done in a weakly supervised setting. Extensive experiments on PASCAL VOC 2007 show that (1) using human verification to update detectors and reduce the search space leads to the rapid production of high-quality bounding-box annotations; (2) our scheme delivers detectors performing almost as good as those trained in a fully supervised setting, without ever drawing any bounding-box; (3) as the verification task is very quick, our scheme substantially reduces total annotation time by a factor 6x-9x.

##### Abstract (translated by Google)
训练对象类别检测器通常需要大量图像，其中对象由边界框注释。但是，手动绘制包围盒非常耗时。我们提出了一个新的训练对象检测器的方案，只需要注释者来验证学习算法自动产生的边界盒。我们的方案在重新训练检测器，重新定位训练图像中的对象和人工验证之间进行迭代。我们使用验证信号来改善重新训练并减少重新定位的搜索空间，这使得这些步骤与通常在弱监督环境中所做的不同。对PASCAL VOC 2007进行的大量实验表明：（1）利用人工验证来更新探测器并缩小搜索空间，从而快速生成高质量的包围盒注释; （2）我们的方案提供的探测器性能几乎与完全监督环境下训练的探测器一样好，没有绘制任何边界框; （3）由于验证任务非常快，我们的方案大大减少了总注释时间6倍-9倍。

##### URL
[https://arxiv.org/abs/1602.08405](https://arxiv.org/abs/1602.08405)

##### PDF
[https://arxiv.org/pdf/1602.08405](https://arxiv.org/pdf/1602.08405)

