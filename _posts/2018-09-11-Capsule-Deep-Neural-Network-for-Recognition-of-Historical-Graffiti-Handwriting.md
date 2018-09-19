---
layout: post
title: "Capsule Deep Neural Network for Recognition of Historical Graffiti Handwriting"
date: 2018-09-11 17:02:13
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction Recognition
author: Nikita Gordienko, Yuriy Kochura, Vlad Taran, Gang Peng, Yuri Gordienko, Sergii Stirenko
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic recognition of the historical letters (XI-XVIII centuries) carved on the stoned walls of St.Sophia cathedral in Kyiv (Ukraine) was demonstrated by means of capsule deep learning neural network. It was applied to the image dataset of the carved Glagolitic and Cyrillic letters (CGCL), which was assembled and pre-processed recently for recognition and prediction by machine learning methods (this https URL). CGCL dataset contains >4000 images for glyphs of 34 letters which are hardly recognized by experts even in contrast to notMNIST dataset with the better images of 10 letters taken from different fonts. Despite the much worse quality of CGCL dataset and extremely low number of samples (in comparison to notMNIST dataset) the capsule network model demonstrated much better results than the previously used convolutional neural network (CNN). The validation accuracy (and validation loss) was higher (lower) for capsule network model than for CNN without data augmentation even. The area under curve (AUC) values for receiver operating characteristic (ROC) were also higher for the capsule network model than for CNN model: 0.88-0.93 (capsule network) and 0.50 (CNN) without data augmentation, 0.91-0.95 (capsule network) and 0.51 (CNN) with lossless data augmentation, and similar results of 0.91-0.93 (capsule network) and 0.9 (CNN) in the regime of lossless data augmentation only. The confusion matrixes were much better for capsule network than for CNN model and gave the much lower type I (false positive) and type II (false negative) values in all three regimes of data augmentation. These results supports the previous claims that capsule-like networks allow to reduce error rates not only on MNIST digit dataset, but on the other notMNIST letter dataset and the more complex CGCL handwriting graffiti letter dataset also.

##### Abstract (translated by Google)
通过胶囊深度学习神经网络证明了在基辅（乌克兰）St.Sophia大教堂的石墙上雕刻的历史字母（XI-XVIII世纪）的自动识别。它被应用于雕刻的Glagolitic和Cyrillic字母（CGCL）的图像数据集，其最近被组装和预处理以通过机器学习方法（该https URL）进行识别和预测。 CGCL数据集包含> 4000个用于34个字母的字形的图像，即使与不具有从不同字体获取的10个字母的更好图像的非MNIST数据集相比也难以被专家识别。尽管CGCL数据集的质量差得多且样本数量极少（与非MNIST数据集相比），但胶囊网络模型显示出比先前使用的卷积神经网络（CNN）更好的结果。胶囊网络模型的验证准确度（和验证损失）比没有数据增加的CNN更高（更低）。胶囊网络模型的接收器工作特性（ROC）的曲线下面积（AUC）值也高于CNN模型：0.88-0.93（胶囊网络）和0.50（CNN）没有数据增加，0.91-0.95（胶囊网络）具有无损数据增加的0.51（CNN）和仅在无损数据增强机制中的0.91-0.93（胶囊网络）和0.9（CNN）的类似结果。胶囊网络的混淆矩阵比CNN模型好得多，并且在所有三种数据增强方案中给出了低得多的I型（假阳性）和II型（假阴性）值。这些结果支持先前的声明，即类囊状网络不仅可以降低MNIST数字数据集的错误率，而且可以降低另一个非MNIST字母数据集和更复杂的CGCL手写涂鸦字母数据集的错误率。

##### URL
[https://arxiv.org/abs/1809.06693](https://arxiv.org/abs/1809.06693)

##### PDF
[https://arxiv.org/pdf/1809.06693](https://arxiv.org/pdf/1809.06693)

