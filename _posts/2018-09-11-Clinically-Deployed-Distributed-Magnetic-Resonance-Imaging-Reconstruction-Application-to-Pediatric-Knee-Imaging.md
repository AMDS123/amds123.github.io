---
layout: post
title: "Clinically Deployed Distributed Magnetic Resonance Imaging Reconstruction: Application to Pediatric Knee Imaging"
date: 2018-09-11 23:21:48
categories: arXiv_CV
tags: arXiv_CV
author: Michael J. Anderson, Jonathan I. Tamir, Javier S. Turek, Marcus T. Alley, Theodore L. Willke, Shreyas S. Vasanawala, Michael Lustig
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic resonance imaging is capable of producing volumetric images without ionizing radiation. Nonetheless, long acquisitions lead to prohibitively long exams. Compressed sensing (CS) can enable faster scanning via sub-sampling with reduced artifacts. However, CS requires significantly higher reconstruction computation, limiting current clinical applications to 2D/3D or limited-resolution dynamic imaging. Here we analyze the practical limitations to T2 Shuffling, a four-dimensional CS-based acquisition, which provides sharp 3D-isotropic-resolution and multi-contrast images in a single scan. Our improvements to the pipeline on a single machine provide a 3x overall reconstruction speedup, which allowed us to add algorithmic changes improving image quality. Using four machines, we achieved additional 2.1x improvement through distributed parallelization. Our solution reduced the reconstruction time in the hospital to 90 seconds on a 4-node cluster, enabling its use clinically. To understand the implications of scaling this application, we simulated running our reconstructions with a multiple scanner setup typical in hospitals.

##### Abstract (translated by Google)
磁共振成像能够在没有电离辐射的情况下产生体积图像。尽管如此，长期的收购导致考试时间过长。压缩感知（CS）可以通过子采样实现更快的扫描，同时减少伪像。然而，CS需要显着更高的重建计算，将当前的临床应用限制为2D / 3D或有限分辨率的动态成像。在这里，我们分析T2 Shuffling的实际限制，这是一种基于CS的四维采集，可在单次扫描中提供清晰的3D各向同性分辨率和多对比度图像。我们在单台机器上对管道的改进提供了3倍的整体重建加速，这使我们能够添加算法更改，从而提高图像质量。使用四台机器，我们通过分布式并行化实现了2.1倍的改进。我们的解决方案在4节点集群上将医院的重建时间缩短至90秒，从而使其在临床上得以使用。为了理解扩展此应用程序的含义，我们使用医院中典型的多扫描仪设置模拟运行我们的重建。

##### URL
[http://arxiv.org/abs/1809.04195](http://arxiv.org/abs/1809.04195)

##### PDF
[http://arxiv.org/pdf/1809.04195](http://arxiv.org/pdf/1809.04195)

