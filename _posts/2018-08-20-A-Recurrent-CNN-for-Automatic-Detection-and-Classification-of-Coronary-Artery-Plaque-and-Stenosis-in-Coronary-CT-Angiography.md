---
layout: post
title: "A Recurrent CNN for Automatic Detection and Classification of Coronary Artery Plaque and Stenosis in Coronary CT Angiography"
date: 2018-08-20 12:43:26
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Majd Zreik, Robbert W. van Hamersvelt, Jelmer M. Wolterink, Tim Leiner, Max A. Viergever, Ivana Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
Various types of atherosclerotic plaque and varying grades of stenosis could lead to different management of patients with coronary artery disease. Therefore, it is crucial to detect and classify the type of coronary artery plaque, as well as to detect and determine the degree of coronary artery stenosis. This study includes retrospectively collected clinically obtained coronary CT angiography (CCTA) scans of 163 patients. To perform automatic analysis for coronary artery plaque and stenosis classification, a multi-task recurrent convolutional neural network is applied on multi-planar reformatted (MPR) images of the coronary arteries. First, a 3D convolutional neural network is utilized to extract features along the coronary artery. Subsequently, the extracted features are aggregated by a recurrent neural network that performs two simultaneous multi-class classification tasks. In the first task, the network detects and characterizes the type of the coronary artery plaque (no plaque, non-calcified, mixed, calcified). In the second task, the network detects and determines the anatomical significance of the coronary artery stenosis (no stenosis, non-significant i.e. &lt;50% luminal narrowing, significant i.e. &gt;50% luminal narrowing). For detection and classification of coronary plaque, the method achieved an accuracy of 0.77. For detection and classification of stenosis, the method achieved an accuracy of 0.80. The results demonstrate that automatic detection and classification of coronary artery plaque and stenosis are feasible. This may enable automated triage of patients to those without coronary plaque and those with coronary plaque and stenosis in need for further cardiovascular workup.

##### Abstract (translated by Google)
各种类型的动脉粥样硬化斑块和不同等级的狭窄可导致患有冠状动脉疾病的患者的不同管理。因此，检测和分类冠状动脉斑块的类型，以及检测和确定冠状动脉狭窄的程度至关重要。本研究包括回顾性收集163例患者的临床获得的冠状动脉CT血管造影（CCTA）扫描。为了对冠状动脉斑块和狭窄分类进行自动分析，将多任务递归卷积神经网络应用于冠状动脉的多平面重新格式化（MPR）图像。首先，利用3D卷积神经网络从冠状动脉提取特征。随后，提取的特征由递归神经网络聚合，该神经网络执行两个同时的多类分类任务。在第一项任务中，网络检测并表征冠状动脉斑块的类型（无斑块，非钙化，混合，钙化）。在第二项任务中，网络检测并确定冠状动脉狭窄的解剖学意义（无狭窄，不显着，即<50％管腔狭窄，显着，即> 50％管腔狭窄）。对于冠状动脉斑块的检测和分类，该方法实现了0.77的准确度。对于狭窄的检测和分类，该方法实现了0.80的准确度。结果表明，冠状动脉斑块和狭窄的自动检测和分类是可行的。这可以使患者能够自动分类到没有冠状动脉斑块的患者和需要进一步心血管检查的冠状动脉斑块和狭窄患者。

##### URL
[http://arxiv.org/abs/1804.04360](http://arxiv.org/abs/1804.04360)

##### PDF
[http://arxiv.org/pdf/1804.04360](http://arxiv.org/pdf/1804.04360)

