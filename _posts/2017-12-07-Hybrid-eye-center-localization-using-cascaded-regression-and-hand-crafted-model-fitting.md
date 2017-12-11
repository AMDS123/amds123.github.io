---
layout: post
title: "Hybrid eye center localization using cascaded regression and hand-crafted model fitting"
date: 2017-12-07 19:21:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection
author: Alex Levinshtein (1), Edmund Phung (1), Parham Aarabi (1 and 2) ((1) ModiFace Inc, (2) University of Toronto)
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new cascaded regressor for eye center detection. Previous methods start from a face or an eye detector and use either advanced features or powerful regressors for eye center localization, but not both. Instead, we detect the eyes more accurately using an existing facial feature alignment method. We improve the robustness of localization by using both advanced features and powerful regression machinery. Unlike most other methods that do not refine the regression results, we make the localization more accurate by adding a robust circle fitting post-processing step. Finally, using a simple hand-crafted method for eye center localization, we show how to train the cascaded regressor without the need for manually annotated training data. We evaluate our new approach and show that it achieves state-of-the-art performance on the BioID, GI4E, and the TalkingFace datasets. At an average normalized error of e &lt; 0.05, the regressor trained on manually annotated data yields an accuracy of 95.07% (BioID), 99.27% (GI4E), and 95.68% (TalkingFace). The automatically trained regressor is nearly as good, yielding an accuracy of 93.9% (BioID), 99.27% (GI4E), and 95.46% (TalkingFace).

##### Abstract (translated by Google)
我们提出了一种新的眼部中心检测级联回归器。先前的方法从人脸或眼睛检测器开始，并使用高级功能或强大的回归器来进行眼中心定位，但不能同时使用两者。相反，我们使用现有的面部特征对齐方法更准确地检测眼睛。我们通过使用先进的功能和强大的回归机制来提高本地化的稳健性。与大多数不改进回归结果的其他方法不同，我们通过增加一个强大的循环拟合后处理步骤来使本地化更加准确。最后，使用简单的手工方法来进行眼睛中心定位，我们将展示如何训练级联回归器，而不需要手动注释的训练数据。我们评估我们的新方法，并显示它在BioID，GI4E和TalkingFace数据集上达到了最先进的性能。在平均归一化误差e < 0.05，用人工注释数据训练的回归器产生95.07％（BioID），99.27％（GI4E）和95.68％（TalkingFace）的准确度。自动训练的回归器几乎同样好，准确率为93.9％（BioID），99.27％（GI4E）和95.46％（TalkingFace）。

##### URL
[http://arxiv.org/abs/1712.02822](http://arxiv.org/abs/1712.02822)

##### PDF
[http://arxiv.org/pdf/1712.02822](http://arxiv.org/pdf/1712.02822)

