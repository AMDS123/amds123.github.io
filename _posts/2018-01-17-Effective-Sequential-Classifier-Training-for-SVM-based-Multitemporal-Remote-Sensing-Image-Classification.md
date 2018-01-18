---
layout: post
title: "Effective Sequential Classifier Training for SVM-based Multitemporal Remote Sensing Image Classification"
date: 2018-01-17 02:24:47
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Relation
author: Yiqing Guo, Xiuping Jia, David Paull
mathjax: true
---

* content
{:toc}

##### Abstract
The explosive availability of remote sensing images has challenged supervised classification algorithms such as Support Vector Machines (SVM), as training samples tend to be highly limited due to the expensive and laborious task of ground truthing. The temporal correlation and spectral similarity between multitemporal images have opened up an opportunity to alleviate this problem. In this study, a SVM-based Sequential Classifier Training (SCT-SVM) approach is proposed for multitemporal remote sensing image classification. The approach leverages the classifiers of previous images to reduce the required number of training samples for the classifier training of an incoming image. For each incoming image, a rough classifier is firstly predicted based on the temporal trend of a set of previous classifiers. The predicted classifier is then fine-tuned into a more accurate position with current training samples. This approach can be applied progressively to sequential image data, with only a small number of training samples being required from each image. Experiments were conducted with Sentinel-2A multitemporal data over an agricultural area in Australia. Results showed that the proposed SCT-SVM achieved better classification accuracies compared with two state-of-the-art model transfer algorithms. When training data are insufficient, the overall classification accuracy of the incoming image was improved from 76.18% to 94.02% with the proposed SCT-SVM, compared with those obtained without the assistance from previous images. These results demonstrate that the leverage of a priori information from previous images can provide advantageous assistance for later images in multitemporal image classification.

##### Abstract (translated by Google)
遥感图像的爆炸性可用性已经对支持向量机（SVM）等监督分类算法提出了挑战，因为训练样本往往由于地面实验的昂贵和费力而受到高度限制。多时相图像之间的时间相关性和光谱相似性为缓解这一问题开辟了一个机会。在这项研究中，提出了一种基于支持向量机的时序分类器训练（SCT-SVM）方法，用于多时相遥感图像分类。该方法利用先前图像的分类器来减少输入图像的分类器训练所需的训练样本数量。对于每个输入图像，首先基于一组先前分类器的时间趋势预测粗分类器。然后用当前训练样本将预测的分类器精确调整到更准确的位置。这种方法可以逐步应用于连续的图像数据，每个图像只需要少量的训练样本。在澳大利亚的一个农业区进行了Sentinel-2A多时相数据的实验。结果表明，与两种最先进的模型转换算法相比，所提出的SCT-SVM具有更好的分类精度。在训练数据不足的情况下，提出的SCT-SVM将输入图像的整体分类准确率从76.18％提高到94.02％。这些结果表明，来自先前图像的先验信息的杠杆作用可以为多时相图像分类中的后期图像提供有利的帮助。

##### URL
[http://arxiv.org/abs/1706.04719](http://arxiv.org/abs/1706.04719)

##### PDF
[http://arxiv.org/pdf/1706.04719](http://arxiv.org/pdf/1706.04719)

