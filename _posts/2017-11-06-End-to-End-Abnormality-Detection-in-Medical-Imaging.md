---
layout: post
title: "End-to-End Abnormality Detection in Medical Imaging"
date: 2017-11-06 18:41:18
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Dufan Wu, Kyungsang Kim, Bin Dong, Quanzheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Nearly all of the deep learning based image analysis methods work on reconstructed images, which are obtained from original acquisitions via solving inverse problems. The reconstruction algorithms are designed for human observers, but not necessarily optimized for DNNs. It is desirable to train the DNNs directly from the original data which lie in a different domain with the images. In this work, we proposed an end-to-end DNN for abnormality detection in medical imaging. A DNN was built as the unrolled version of iterative reconstruction algorithms to map the acquisitions to images, and followed by a 3D convolutional neural network (CNN) to detect the abnormality in the reconstructed images. The two networks were trained jointly in order to optimize the entire DNN for the detection task from the original acquisitions. The DNN was implemented for lung nodule detection in low-dose chest CT. The proposed end-to-end DNN demonstrated better sensitivity and accuracy for the task compared to a two-step approach, in which the reconstruction and detection DNNs were trained separately. A significant reduction of false positive rate on suspicious lesions were observed, which is crucial for the known over-diagnosis in low-dose lung CT imaging. The images reconstructed by the proposed end-to-end network also presented enhanced details in the region of interest.

##### Abstract (translated by Google)
几乎所有的基于深度学习的图像分析方法都是通过解决逆问题从原始采集获得的重建图像。重建算法是为人类观察者设计的，但不一定针对DNN进行优化。直接从位于与图像不同的域中的原始数据训练DNN是可取的。在这项工作中，我们提出了一个端到端DNN用于医学成像异常检测。建立了DNN作为迭代重建算法的展开版本，将采集映射到图像，然后用三维卷积神经网络（CNN）检测重建图像中的异常。两个网络共同进行了培训，以优化从原始收购中检测任务的整个DNN。 DNN用于低剂量胸部CT肺结节检测。与两步法相比，所提出的端到端DNN表现出更好的灵敏度和准确性，其中重建和检测DNN分别被训练。观察到可疑病变的假阳性率显着降低，这对于小剂量肺CT成像中已知的过度诊断是至关重要的。所提议的端到端网络重建的图像也在感兴趣的区域提供了增强的细节。

##### URL
[https://arxiv.org/abs/1711.02074](https://arxiv.org/abs/1711.02074)

##### PDF
[https://arxiv.org/pdf/1711.02074](https://arxiv.org/pdf/1711.02074)

