---
layout: post
title: "Fine-Grained Age Estimation in the wild with Attention LSTM Networks"
date: 2018-05-26 08:27:01
categories: arXiv_CV
tags: arXiv_CV Attention Face RNN Classification Prediction
author: Ke Zhang, Na Liu, Xingfang Yuan, Xinyao Guo, Ce Gao, Zhenbing Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Age estimation from a single face image has been an essential task in the field of human-computer interaction and computer vision which has a wide range of practical application value. Concerning the problem that accuracy of age estimation of face images in the wild are relatively low for existing methods, where they take into account only the whole features of face image while neglecting the fine-grained features of age-sensitive area, we propose a method based on Attention LSTM network for Fine-Grained age estimation in the wild based on the idea of Fine-Grained categories and visual attention mechanism. This method combines ResNets or RoR models with LSTM unit to construct AL-ResNets or AL-RoR networks to extract age-sensitive local regions, which effectively improves age estimation accuracy. Firstly, ResNets or RoR model pre-trained on ImageNet dataset is selected as the basic model, which is then fine-tuned on the IMDB-WIKI-101 dataset for age estimation. Then, we fine-tune ResNets or RoR on the target age datasets to extract the global features of face images. To extract the local characteristics of age-sensitive areas, the LSTM unit is then presented to obtain the coordinates of the age-sensitive region automatically. Finally, the age group classification experiment is conducted directly on the Adience dataset, and age-regression experiments are performed by the Deep EXpectation algorithm (DEX) on MORPH Album 2, FG-NET and LAP datasets. By combining the global and local features, we got our final prediction results. Our experiments illustrate the effectiveness of AL-ResNets or AL-RoR for age estimation in the wild, where it achieves new state-of-the-art performance than all other CNN methods on the Adience, MORPH Album 2, FG-NET and LAP datasets.

##### Abstract (translated by Google)
单人脸图像的年龄估计一直是人机交互和计算机视觉领域的一项重要任务，具有广泛的实际应用价值。针对现有方法对野外人脸图像年龄估计精度较低的问题，考虑到仅考虑人脸图像的整体特征而忽略了对年龄敏感区域的细粒度特征，我们提出了一种方法基于Fine-Grained分类和视觉注意机制的思想，基于Attention LSTM网络进行野外细粒度年龄估计。该方法将ResNets或RoR模型与LSTM单元相结合，构建AL-ResNets或AL-RoR网络，提取年龄敏感的局部区域，有效提高年龄估计的准确性。首先，选择在ImageNet数据集上预先训练的ResNets或RoR模型作为基本模型，然后在IMDB-WIKI-101数据集上对其进行微调以进行年龄估计。然后，我们对目标年龄数据集上的ResNets或RoR进行微调，以提取人脸图像的全局特征。为了提取年龄敏感区域的局部特征，然后提供LSTM单元以自动获得年龄敏感区域的坐标。最后，年龄组分类实验直接在Adience数据集上进行，年龄回归实验由MORPH相册2，FG-NET和LAP数据集上的Deep Expectation算法（DEX）执行。通过结合全球和本地特征，我们得到了最终的预测结果。我们的实验说明了AL-ResNets或AL-RoR在野外的年龄估计的有效性，它比Adience，MORPH Album 2，FG-NET和LAP上的所有其他CNN方法实现了最新的最先进性能数据集。

##### URL
[http://arxiv.org/abs/1805.10445](http://arxiv.org/abs/1805.10445)

##### PDF
[http://arxiv.org/pdf/1805.10445](http://arxiv.org/pdf/1805.10445)

