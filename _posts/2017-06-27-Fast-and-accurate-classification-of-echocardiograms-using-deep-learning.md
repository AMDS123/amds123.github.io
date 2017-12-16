---
layout: post
title: "Fast and accurate classification of echocardiograms using deep learning"
date: 2017-06-27 03:21:47
categories: arXiv_CV
tags: arXiv_CV Salient CNN Classification Deep_Learning
author: Ali Madani, Ramy Arnaout, Mohammad Mofrad, Rima Arnaout
mathjax: true
---

* content
{:toc}

##### Abstract
Echocardiography is essential to modern cardiology. However, human interpretation limits high throughput analysis, limiting echocardiography from reaching its full clinical and research potential for precision medicine. Deep learning is a cutting-edge machine-learning technique that has been useful in analyzing medical images but has not yet been widely applied to echocardiography, partly due to the complexity of echocardiograms' multi view, multi modality format. The essential first step toward comprehensive computer assisted echocardiographic interpretation is determining whether computers can learn to recognize standard views. To this end, we anonymized 834,267 transthoracic echocardiogram (TTE) images from 267 patients (20 to 96 years, 51 percent female, 26 percent obese) seen between 2000 and 2017 and labeled them according to standard views. Images covered a range of real world clinical variation. We built a multilayer convolutional neural network and used supervised learning to simultaneously classify 15 standard views. Eighty percent of data used was randomly chosen for training and 20 percent reserved for validation and testing on never seen echocardiograms. Using multiple images from each clip, the model classified among 12 video views with 97.8 percent overall test accuracy without overfitting. Even on single low resolution images, test accuracy among 15 views was 91.7 percent versus 70.2 to 83.5 percent for board-certified echocardiographers. Confusional matrices, occlusion experiments, and saliency mapping showed that the model finds recognizable similarities among related views and classifies using clinically relevant image features. In conclusion, deep neural networks can classify essential echocardiographic views simultaneously and with high accuracy. Our results provide a foundation for more complex deep learning assisted echocardiographic interpretation.

##### Abstract (translated by Google)
超声心动图对现代心脏病学至关重要。然而，人的解释限制了高通量分析，限制超声心动图达不到其精密医学的全部临床和研究潜力。深度学习是一种先进的机器学习技术，在分析医学图像方面很有用，但在超声心动图方面还没有得到广泛的应用，部分原因是超声心动图的多视图，多模态格式的复杂性。计算机辅助超声心动图解释的基本的第一步是确定计算机是否可以学会识别标准视图。为此，我们对2000年至2017年期间267名患者（20至96岁，51％的女性，26％的肥胖）的经胸超声心动图（TTE）图像进行了匿名处理，并将其标记为标准视图。图像涵盖了一系列真实世界的临床变化。我们构建了一个多层卷积神经网络，并使用监督学习来同时分类15个标准视图。百分之八十使用的数据是随机选择进行培训，20％用于验证和测试从未见过超声心动图。使用来自每个剪辑的多个图像，该模型被分类在12个视频视图中，具有97.8％的整体测试准确性而没有过度拟合。即使在单个低分辨率图像上，15个视图中的测试精确度为91.7％，而板认证的超声心动图测试仪的测试精度为70.2％到83.5％。混淆矩阵，遮挡实验和显着性映射表明，该模型发现相关视图之间可识别的相似性，并使用临床相关的图像特征进行分类。总之，深度神经网络可以同时和高准确度地分类基本的超声心动图视图。我们的结果为更复杂的深度学习辅助超声心动图解释提供了基础。

##### URL
[https://arxiv.org/abs/1706.08658](https://arxiv.org/abs/1706.08658)

##### PDF
[https://arxiv.org/pdf/1706.08658](https://arxiv.org/pdf/1706.08658)

