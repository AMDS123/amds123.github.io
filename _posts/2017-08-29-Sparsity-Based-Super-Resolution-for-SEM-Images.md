---
layout: post
title: "Sparsity-Based Super Resolution for SEM Images"
date: 2017-08-29 16:23:43
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse Face
author: Shahar Tsiper, Or Dicker, Idan Kaizerman, Zeev Zohar, Mordechai Segev, Yonina C. Eldar
mathjax: true
---

* content
{:toc}

##### Abstract
The scanning electron microscope (SEM) produces an image of a sample by scanning it with a focused beam of electrons. The electrons interact with the atoms in the sample, which emit secondary electrons that contain information about the surface topography and composition. The sample is scanned by the electron beam point by point, until an image of the surface is formed. Since its invention in 1942, SEMs have become paramount in the discovery and understanding of the nanometer world, and today it is extensively used for both research and in industry. In principle, SEMs can achieve resolution better than one nanometer. However, for many applications, working at sub-nanometer resolution implies an exceedingly large number of scanning points. For exactly this reason, the SEM diagnostics of microelectronic chips is performed either at high resolution (HR) over a small area or at low resolution (LR) while capturing a larger portion of the chip. Here, we employ sparse coding and dictionary learning to algorithmically enhance LR SEM images of microelectronic chips up to the level of the HR images acquired by slow SEM scans, while considerably reducing the noise. Our methodology consists of two steps: an offline stage of learning a joint dictionary from a sequence of LR and HR images of the same region in the chip, followed by a fast-online super-resolution step where the resolution of a new LR image is enhanced. We provide several examples with typical chips used in the microelectronics industry, as well as a statistical study on arbitrary images with characteristic structural features. Conceptually, our method works well when the images have similar characteristics. This work demonstrates that employing sparsity concepts can greatly improve the performance of SEM, thereby considerably increasing the scanning throughput without compromising on analysis quality and resolution.

##### Abstract (translated by Google)
扫描电子显微镜（SEM）通过用聚焦的电子束扫描来产生样品的图像。电子与样品中的原子相互作用，发射包含关于表面形貌和组成的信息的二次电子。样品由电子束逐点扫描，直到形成表面的图像。自从1942年发明以来，SEM在纳米世界的发现和理解中已经变得至关重要，如今它在研究和工业上都被广泛使用。原则上，SEM可以达到比1纳米更好的分辨率。但是，对于许多应用而言，以亚纳米分辨率工作意味着扫描点的数量非常大。正是由于这个原因，微电子芯片的SEM诊断是在小面积或低分辨率（LR）下以高分辨率（HR）进行的，同时捕获更大部分的芯片。在这里，我们采用稀疏编码和字典学习算法增强微电子芯片的LR SEM图像，直到通过慢扫描获得的HR图像的水平，同时显着降低噪声。我们的方法包括两个步骤：离线阶段，从芯片中同一区域的LR和HR图像序列中学习联合字典，然后进行快速在线超分辨率步骤，其中新的LR图像的分辨率是增强。我们提供了微电子工业中使用的典型芯片的几个例子，以及具有特征结构特征的任意图像的统计研究。从概念上讲，当图像具有相似的特征时，我们的方法运作良好。这项工作表明，使用稀疏概念可以大大提高SEM的性能，从而大大提高扫描的吞吐量，而不会影响分析质量和分辨率。

##### URL
[https://arxiv.org/abs/1709.02235](https://arxiv.org/abs/1709.02235)

##### PDF
[https://arxiv.org/pdf/1709.02235](https://arxiv.org/pdf/1709.02235)

