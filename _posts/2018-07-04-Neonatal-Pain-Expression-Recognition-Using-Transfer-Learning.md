---
layout: post
title: "Neonatal Pain Expression Recognition Using Transfer Learning"
date: 2018-07-04 15:15:05
categories: arXiv_CV
tags: arXiv_CV Face CNN Image_Classification Transfer_Learning Classification Recognition Face_Recognition
author: Ghada Zamzmi, Dmitry Goldgof, Rangachar Kasturi, Yu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer learning using pre-trained Convolutional Neural Networks (CNNs) has been successfully applied to images for different classification tasks. In this paper, we propose a new pipeline for pain expression recognition in neonates using transfer learning. Specifically, we propose to exploit a pre-trained CNN that was originally trained on a relatively similar dataset for face recognition (VGG Face) as well as CNNs that were pre-trained on a relatively different dataset for image classification (iVGG F,M, and S) to extract deep features from neonates' faces. In the final stage, several supervised machine learning classifiers are trained to classify neonates' facial expression into pain or no pain expression. The proposed pipeline achieved, on a testing dataset, 0.841 AUC and 90.34 accuracy, which is approx. 7 higher than the accuracy of handcrafted traditional features. We also propose to combine deep features with traditional features and hypothesize that the mixed features would improve pain classification performance. Combining deep features with traditional features achieved 92.71 accuracy and 0.948 AUC. These results show that transfer learning, which is a faster and more practical option than training CNN from the scratch, can be used to extract useful features for pain expression recognition in neonates. It also shows that combining deep features with traditional handcrafted features is a good practice to improve the performance of pain expression recognition and possibly the performance of similar applications.

##### Abstract (translated by Google)
使用预先训练的卷积神经网络（CNN）的转移学习已成功应用于不同分类任务的图像。在本文中，我们提出了一种新的管道，用于使用转移学习在新生儿中进行疼痛表达识别。具体来说，我们建议利用一个预先训练的CNN，该CNN最初是在相对类似的人脸识别数据集（VGG Face）上训练的，以及在相对不同的数据集上进行图像分类预训练的CNN（iVGG F，M，和S）从新生儿的脸上提取深层特征。在最后阶段，训练几个受监督的机器学习分类器，以将新生儿的面部表情分类为疼痛或无疼痛表达。拟议的管道在测试数据集上实现了0.841 AUC和90.34精度，大约是。 7高于手工制作传统功能的准确性。我们还建议将深层特征与传统特征相结合，并假设混合特征将改善疼痛分类性能。将深度特征与传统特征相结合，可实现92.71精度和0.948 AUC。这些结果表明，转移学习是一种比从头开始训练CNN更快更实用的选择，可用于提取新生儿疼痛表达识别的有用特征。它还表明，将深层特征与传统手工特征相结合是一种很好的实践，可以提高疼痛表达识别的性能，并可能提高类似应用的性能。

##### URL
[http://arxiv.org/abs/1807.01631](http://arxiv.org/abs/1807.01631)

##### PDF
[http://arxiv.org/pdf/1807.01631](http://arxiv.org/pdf/1807.01631)

