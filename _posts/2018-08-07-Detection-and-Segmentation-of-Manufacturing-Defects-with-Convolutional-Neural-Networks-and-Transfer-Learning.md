---
layout: post
title: "Detection and Segmentation of Manufacturing Defects with Convolutional Neural Networks and Transfer Learning"
date: 2018-08-07 18:57:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Transfer_Learning Classification Prediction Detection
author: Max Ferguson, Ronay Ak, Yung-Tsun Tina Lee, Kincho H. Law
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic detection of defects in metal castings is a challenging task, owing to the rare occurrence and variation in appearance of defects. However, automatic defect detection systems can lead to significant increases in final product quality. Convolutional neural networks (CNNs) have shown outstanding performance in both image classification and localization tasks. In this work, a system is proposed for the identification of casting defects in X-ray images, based on the mask region-based CNN architecture. The proposed defect detection system simultaneously performs defect detection and segmentation on input images, making it suitable for a range of defect detection tasks. It is shown that training the network to simultaneously perform defect detection and defect instance segmentation, results in a higher defect detection accuracy than training on defect detection alone. Transfer learning is leveraged to reduce the training data demands and increase the prediction accuracy of the trained model. More specifically, the model is first trained with two large openly-available image datasets before fine-tuning on a relatively small metal casting X-ray dataset. The accuracy of the trained model exceeds state-of-the art performance on the GDXray Castings dataset and is fast enough to be used in a production setting. The system also performs well on the GDXray Welds dataset. A number of in-depth studies are conducted to explore how transfer learning, multi-task learning, and multi-class learning influence the performance of the trained system.

##### Abstract (translated by Google)
由于缺陷的出现和变化很少，因此自动检测金属铸件中的缺陷是一项具有挑战性的任务。但是，自动缺陷检测系统可以显着提高最终产品质量。卷积神经网络（CNN）在图像分类和定位任务中都表现出色。在这项工作中，基于基于掩模区域的CNN架构，提出了一种用于识别X射线图像中的铸造缺陷的系统。所提出的缺陷检测系统同时对输入图像执行缺陷检测和分割，使其适用于一系列缺陷检测任务。示出了训练网络以同时执行缺陷检测和缺陷实例分割，导致比仅针对缺陷检测的训练更高的缺陷检测精度。利用转移学习来减少训练数据需求并提高训练模型的预测准确性。更具体地，在对相对小的金属铸造X射线数据集进行微调之前，首先用两个大的可公开可用的图像数据集训练模型。训练模型的准确性超过了GDXray Castings数据集的最新性能，并且足够快，可用于生产环境。该系统在GDXray Welds数据集上也表现良好。进行了许多深入研究，以探索转学习，多任务学习和多班学习如何影响受训系统的表现。

##### URL
[http://arxiv.org/abs/1808.02518](http://arxiv.org/abs/1808.02518)

##### PDF
[http://arxiv.org/pdf/1808.02518](http://arxiv.org/pdf/1808.02518)

