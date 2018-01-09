---
layout: post
title: "Improving utility of brain tumor confocal laser endomicroscopy: objective value assessment and diagnostic frame detection with convolutional neural networks"
date: 2018-01-06 22:57:06
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Mohammadhassan Izadyyazdanabadi, Evgenii Belykh, Nikolay Martirosyan, Jennifer Eschbacher, Peter Nakaji, Yezhou Yang, Mark C. Preul
mathjax: true
---

* content
{:toc}

##### Abstract
Confocal laser endomicroscopy (CLE), although capable of obtaining images at cellular resolution during surgery of brain tumors in real time, creates as many non-diagnostic as diagnostic images. Non-useful images are often distorted due to relative motion between probe and brain or blood artifacts. Many images, however, simply lack diagnostic features immediately informative to the physician. Examining all the hundreds or thousands of images from a single case to discriminate diagnostic images from nondiagnostic ones can be tedious. Providing a real-time diagnostic value assessment of images (fast enough to be used during the surgical acquisition process and accurate enough for the pathologist to rely on) to automatically detect diagnostic frames would streamline the analysis of images and filter useful images for the pathologist/surgeon. We sought to automatically classify images as diagnostic or non-diagnostic. AlexNet, a deep-learning architecture, was used in a 4-fold cross validation manner. Our dataset includes 16,795 images (8572 nondiagnostic and 8223 diagnostic) from 74 CLE-aided brain tumor surgery patients. The ground truth for all the images is provided by the pathologist. Average model accuracy on test data was 91% overall (90.79 % accuracy, 90.94 % sensitivity and 90.87 % specificity). To evaluate the model reliability we also performed receiver operating characteristic (ROC) analysis yielding 0.958 average for the area under ROC curve (AUC). These results demonstrate that a deeply trained AlexNet network can achieve a model that reliably and quickly recognizes diagnostic CLE images.

##### Abstract (translated by Google)
共聚焦激光显微内镜（CLE）尽管能够在脑肿瘤手术期间实时获得细胞分辨率的图像，但是创造出与诊断图像一样多的非诊断性图像。由于探头和脑或血液伪影之间的相对运动，无用的图像通常会失真。然而，许多图像仅仅缺乏立即向医生提供信息的诊断特征。检查单个病例的所有数百或数千个图像以将诊断图像与非诊断图像区分开可能是单调乏味的。提供对图像的实时诊断价值评估（足够快以在手术采集过程期间使用并且足够准确以供病理学家依赖）来自动检测诊断帧将简化对图像的分析并过滤有用图像给病理学家/外科医生。我们试图自动将图像分类为诊断或非诊断。 AlexNet是一种深度学习的体系结构，以4倍交叉验证的方式使用。我们的数据集包括来自74例CLE手术的脑肿瘤手术患者的16,795幅图像（8572例非诊断性和8223例诊断）。所有图像的基本事实由病理学家提供。测试数据的平均模型准确率为91％（准确率为90.79％，灵敏度为90.94％，特异度为90.87％）。为了评估模型的可靠性，我们还进行了受试者工作特征（ROC）分析，ROC曲线下面积（AUC）的平均值为0.958。这些结果表明，经过深入训练的AlexNet网络可以实现可靠且快速识别诊断CLE图像的模型。

##### URL
[http://arxiv.org/abs/1801.02101](http://arxiv.org/abs/1801.02101)

##### PDF
[http://arxiv.org/pdf/1801.02101](http://arxiv.org/pdf/1801.02101)

