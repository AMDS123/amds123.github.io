---
layout: post
title: "Application of Deep Learning in Neuroradiology: Automated Detection of Basal Ganglia Hemorrhage using 2D-Convolutional Neural Networks"
date: 2017-10-27 16:23:02
categories: arXiv_CV
tags: arXiv_CV GAN CNN Image_Classification Classification Deep_Learning Detection
author: Vishal Desai, Adam E. Flanders, Paras Lakhani
mathjax: true
---

* content
{:toc}

##### Abstract
Background: Deep learning techniques have achieved high accuracy in image classification tasks, and there is interest in applicability to neuroimaging critical findings. This study evaluates the efficacy of 2D deep convolutional neural networks (DCNNs) for detecting basal ganglia (BG) hemorrhage on noncontrast head CT. Materials and Methods: 170 unique de-identified HIPAA-compliant noncontrast head CTs were obtained, those with and without BG hemorrhage. 110 cases were held-out for test, and 60 were split into training (45) and validation (15), consisting of 20 right, 20 left, and 20 no BG hemorrhage. Data augmentation was performed to increase size and variation of the training dataset by 48-fold. Two DCNNs were used to classify the images-AlexNet and GoogLeNet-using untrained networks and those pre-trained on ImageNet. Area under the curves (AUC) for the receiver-operator characteristic (ROC) curves were calculated, using the DeLong method for statistical comparison of ROCs. Results: The best performing model was the pre-trained augmented GoogLeNet, which had an AUC of 1.00 in classification of hemorrhage. Preprocessing augmentation increased accuracy for all networks (p<0.001), and pretrained networks outperformed untrained ones (p<0.001) for the unaugmented models. The best performing GoogLeNet model (AUC 1.00) outperformed the best performing AlexNet model (AUC 0.95)(p=0.01). Conclusion: For this dataset, the best performing DCNN identified BG hemorrhage on noncontrast head CT with an AUC of 1.00. Pretrained networks and data augmentation increased classifier accuracy. Future prospective research would be important to determine if the accuracy can be maintained on a larger cohort of patients and for very small hemorrhages.

##### Abstract (translated by Google)
背景：深度学习技术在图像分类任务中取得了高度的准确性，并且对神经影像学的重要发现的适用性也有兴趣。本研究评估二维深卷积神经网络（DCNNs）检测非增强CT头部基底节（BG）出血的有效性。材料与方法：取得170例独特的符合HIPAA标准的非增强型头部CT，其中有和无BG出血。 110例进行检测，60例分为训练（45）和验证（15），其中20例右20例，20例无BG出血。数据增加是为了将训练数据集的大小和变化增加48倍。使用两个DCNN对图像进行分类 -  AlexNet和GoogLeNet--使用未经训练的网络和在ImageNet上预先训练的网络。计算受试者特征曲线（ROC）曲线下面积（AUC），使用DeLong方法对ROC进行统计学比较。结果：表现最好的模型是预先训练的增强的GoogLeNet，其在出血分类中具有1.00的AUC。预处理增强提高了所有网络的准确性（p <0.001），预训练网络的未训练模型的训练优于未训练网络（p <0.001）。表现最好的GoogLeNet模型（AUC 1.00）优于AlexNet模型（AUC 0.95）（p = 0.01）。结论：对于该数据组，最佳表现的DCNN鉴定了在非增强头部CT上的BG出血，AUC为1.00。预训练网络和数据增强提高了分类器的准确性。未来的前瞻性研究对于确定是否可以维持更大的患者队列和非常小的出血的准确性至关重要。

##### URL
[https://arxiv.org/abs/1710.03823](https://arxiv.org/abs/1710.03823)

##### PDF
[https://arxiv.org/pdf/1710.03823](https://arxiv.org/pdf/1710.03823)

