---
layout: post
title: "RhoanaNet Pipeline: Dense Automatic Neural Annotation"
date: 2016-11-21 19:48:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Seymour Knowles-Barley, Verena Kaynig, Thouis Ray Jones, Alyssa Wilson, Joshua Morgan, Dongil Lee, Daniel Berger, Narayanan Kasthuri, Jeff W. Lichtman, Hanspeter Pfister
mathjax: true
---

* content
{:toc}

##### Abstract
Reconstructing a synaptic wiring diagram, or connectome, from electron microscopy (EM) images of brain tissue currently requires many hours of manual annotation or proofreading (Kasthuri and Lichtman, 2010; Lichtman and Sanes, 2008; Seung, 2009). The desire to reconstruct ever larger and more complex networks has pushed the collection of ever larger EM datasets. A cubic millimeter of raw imaging data would take up 1 PB of storage and present an annotation project that would be impractical without relying heavily on automatic segmentation methods. The RhoanaNet image processing pipeline was developed to automatically segment large volumes of EM data and ease the burden of manual proofreading and annotation. Based on (Kaynig et al., 2015), we updated every stage of the software pipeline to provide better throughput performance and higher quality segmentation results. We used state of the art deep learning techniques to generate improved membrane probability maps, and Gala (Nunez-Iglesias et al., 2014) was used to agglomerate 2D segments into 3D objects. We applied the RhoanaNet pipeline to four densely annotated EM datasets, two from mouse cortex, one from cerebellum and one from mouse lateral geniculate nucleus (LGN). All training and test data is made available for benchmark comparisons. The best segmentation results obtained gave $V^\text{Info}_\text{F-score}$ scores of 0.9054 and 09182 for the cortex datasets, 0.9438 for LGN, and 0.9150 for Cerebellum. The RhoanaNet pipeline is open source software. All source code, training data, test data, and annotations for all four benchmark datasets are available at www.rhoana.org.

##### Abstract (translated by Google)
从脑组织的电子显微镜（EM）图像重建突触布线图或connectome目前需要许多小时的手动注释或校对（Kasthuri and Lichtman，2010; Lichtman and Sanes，2008; Seung，2009）。重建更大更复杂的网络的愿望推动了收集更大的EM数据集。原始成像数据的立方毫米将占用1 PB的存储空间，并提出一个注解项目，如果不依赖于自动分割方法，这将是不切实际的。 RhoanaNet图像处理流水线的开发是为了自动分割大量的EM数据，并减轻手动校对和注释的负担。基于（Kaynig et al。，2015），我们更新了软件流水线的每个阶段，以提供更好的吞吐量性能和更高质量的分割结果。我们使用最先进的深度学习技术来生成改进的膜概率图，并且使用Gala（Nunez-Iglesias等，2014）将2D片段聚集成3D对象。我们将RhoanaNet管道应用于四个密集注释的EM数据集，两个来自小鼠皮层，一个来自小脑，一个来自小鼠外侧膝状核（LGN）。所有培训和测试数据都可用于基准比较。获得的最佳分割结果赋予皮层数据集0.9054和09182，LGN 0.9438和小脑0.9150的$文本{信息}文本{F记分} $分数。 RhoanaNet管道是开源软件。所有四个基准数据集的所有源代码，培训数据，测试数据和注释均可在www.rhoana.org上获得。

##### URL
[https://arxiv.org/abs/1611.06973](https://arxiv.org/abs/1611.06973)

##### PDF
[https://arxiv.org/pdf/1611.06973](https://arxiv.org/pdf/1611.06973)

