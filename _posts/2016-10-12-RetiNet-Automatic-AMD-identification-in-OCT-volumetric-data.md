---
layout: post
title: "RetiNet: Automatic AMD identification in OCT volumetric data"
date: 2016-10-12 07:56:24
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Stefanos Apostolopoulos, Carlos Ciller, Sandro I. De Zanet, Sebastian Wolf, Raphael Sznitman
mathjax: true
---

* content
{:toc}

##### Abstract
Optical Coherence Tomography (OCT) provides a unique ability to image the eye retina in 3D at micrometer resolution and gives ophthalmologist the ability to visualize retinal diseases such as Age-Related Macular Degeneration (AMD). While visual inspection of OCT volumes remains the main method for AMD identification, doing so is time consuming as each cross-section within the volume must be inspected individually by the clinician. In much the same way, acquiring ground truth information for each cross-section is expensive and time consuming. This fact heavily limits the ability to acquire large amounts of ground truth, which subsequently impacts the performance of learning-based methods geared at automatic pathology identification. To avoid this burden, we propose a novel strategy for automatic analysis of OCT volumes where only volume labels are needed. That is, we train a classifier in a semi-supervised manner to conduct this task. Our approach uses a novel Convolutional Neural Network (CNN) architecture, that only needs volume-level labels to be trained to automatically asses whether an OCT volume is healthy or contains AMD. Our architecture involves first learning a cross-section pathology classifier using pseudo-labels that could be corrupted and then leverage these towards a more accurate volume-level classification. We then show that our approach provides excellent performances on a publicly available dataset and outperforms a number of existing automatic techniques.

##### Abstract (translated by Google)
光学相干断层扫描（OCT）提供了一种以微米分辨率对三维视网膜进行成像的独特功能，使眼科医生能够观察视网膜疾病，如年龄相关性黄斑变性（AMD）。虽然目视检查OCT体积仍然是AMD识别的主要方法，但是这样做是耗时的，因为体积中的每个横截面必须由临床医生单独检查。以同样的方式，获取每个横截面的地面真实信息是昂贵和耗时的。这一事实极大地限制了获取大量基础事实的能力，这随后影响了基于学习的自动病理识别方法的性能。为了避免这种负担，我们提出了一种新颖的OCT卷自动分析策略，只需要卷标。也就是说，我们以半监督的方式训练一个分类器来完成这个任务。我们的方法使用了一种新颖的卷积神经网络（CNN）架构，只需要对音量级别的标签进行训练，以自动评估OCT音量是否健康或是否包含AMD。我们的体系结构首先使用可能被损坏的伪标签来学习横截面病理分类器，然后利用这些伪标签来更准确地进行音量级分类。然后，我们表明，我们的方法在公开可用的数据集上提供了出色的性能，并且胜过了许多现有的自动技术。

##### URL
[https://arxiv.org/abs/1610.03628](https://arxiv.org/abs/1610.03628)

##### PDF
[https://arxiv.org/pdf/1610.03628](https://arxiv.org/pdf/1610.03628)

