---
layout: post
title: "Convolutional Neural Networks: Ensemble Modeling, Fine-Tuning and Unsupervised Semantic Localization for Intraoperative CLE Images"
date: 2017-10-23 18:07:26
categories: arXiv_CV
tags: arXiv_CV Review CNN Deep_Learning
author: Mohammadhassan Izadyyazdanabadi, Evgenii Belykh, Michael Mooney, Nikolay Martirosyan, Jennifer Eschbacher, Peter Nakaji, Mark C. Preul, Yezhou Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Confocal laser endomicroscopy (CLE) is an advanced optical fluorescence technology undergoing assessment for applications in brain tumor surgery. Despite its promising potential, interpreting the unfamiliar gray tone images of fluorescent stains can be difficult. Many of the CLE images can be distorted by motion, extremely low or high fluorescence signal, or obscured by red blood cell accumulation, and these can be interpreted as nondiagnostic. However, just one neat CLE image might suffice for intraoperative diagnosis of the tumor. While manual examination of thousands of nondiagnostic images during surgery would be impractical, this creates an opportunity for a model to select diagnostic images for the pathologists or surgeon's review. In this study, we sought to develop a deep learning model to automatically detect the diagnostic images using a manually annotated dataset, and we employed a patient-based nested cross-validation approach to explore generalizability of the model. We explored various training regimes: deep training, shallow fine-tuning, and deep fine-tuning. Further, we investigated the effect of ensemble modeling by combining the top-5 single models crafted in the development phase. We localized histological features from diagnostic CLE images by visualization of shallow and deep neural activations. Our inter-rater experiment results confirmed that our ensemble of deeply fine-tuned models achieved higher agreement with the ground truth than the other observers. With the speed and precision of the proposed method (110 images/second; 85% on the gold standard test subset), it has potential to be integrated into the operative workflow in the brain tumor surgery.

##### Abstract (translated by Google)
共聚焦激光内窥镜（CLE）是一种先进的光学荧光技术，正在接受脑肿瘤手术应用的评估。尽管其潜力很大，但是解释荧光污渍的不熟悉的灰色图像可能是困难的。许多CLE图像可能因运动而失真，荧光信号极低或极高，或被红细胞积聚所掩盖，可被视为无法诊断。然而，只有一个清晰的CLE图像可能足以用于术中诊断肿瘤。尽管在手术期间手动检查数千个非诊断图像是不切实际的，但是这为模型选择用于病理学家或外科医生的评论的诊断图像提供了机会。在这项研究中，我们试图开发一种深度学习模型，使用手动注释的数据集自动检测诊断图像，并且我们采用基于患者的嵌套交叉验证方法来探索模型的普遍性。我们探索了各种训练体制：深度训练，浅层微调和深度微调。此外，我们通过结合在开发阶段制定的前5个单一模型来调查集成建模的影响。我们通过浅层和深层神经激活的可视化定位诊断CLE图像的组织学特征。我们的评价人间的实验结果证实，我们的深度微调模型的集合与其他观察者相比，与基本事实达成了更高的一致性。由于该方法的速度和精度（每秒110幅图像，金标准测试子集中的85％），它有可能被纳入脑肿瘤手术的操作流程。

##### URL
[https://arxiv.org/abs/1709.03028](https://arxiv.org/abs/1709.03028)

##### PDF
[https://arxiv.org/pdf/1709.03028](https://arxiv.org/pdf/1709.03028)

