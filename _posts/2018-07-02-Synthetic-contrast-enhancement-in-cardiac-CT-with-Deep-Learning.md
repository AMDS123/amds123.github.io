---
layout: post
title: "Synthetic contrast enhancement in cardiac CT with Deep Learning"
date: 2018-07-02 15:26:14
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning
author: Gianmarco Santini, Lorena M. Zumbo, Nicola Martini, Gabriele Valvano, Andrea Leo, Andrea Ripoli, Francesco Avogliero, Dante Chiappino, Daniele Della Latta
mathjax: true
---

* content
{:toc}

##### Abstract
In Europe the 20% of the CT scans cover the thoracic region. The acquired images contain information about the cardiovascular system that often remains latent due to the lack of contrast in the cardiac area. On the other hand, the contrast enhanced computed tomography (CECT) represents an imaging technique that allows to easily assess the cardiac chambers volumes and the contrast dynamics. With this work we aim to face the problem of extraction and presentation of these latent information, using a deep learning approach with convolutional neural networks. Starting from the extraction of relevant features from the image without contrast medium, we try to re-map them on features typical of CECT, to synthesize an image characterized by an attenuation in the cardiac chambers as if a virtually iodine contrast medium was injected. The purposes are to guarantee an estimation of the left cardiac chambers volume and to perform an evaluation of the contrast dynamics. Our approach is based on a deconvolutional network trained on a set of 120 patients who underwent both CT acquisitions in the same contrastographic arterial phase and the same cardiac phase. To ensure a reliable predicted CECT image, in terms of values and morphology, a custom loss function is defined by combining an error function to find a pixel-wise correspondence, which takes into account the similarity in term of Hounsfield units between the input and output images and by a cross-entropy computed on the binarized versions of the synthesized and of the real CECT image. The proposed method is finally tested on 20 subjects.

##### Abstract (translated by Google)
在欧洲，20％的CT扫描覆盖了胸部区域。获取的图像包含关于心血管系统的信息，该信息通常由于心脏区域缺乏对比而保持潜伏。另一方面，对比度增强计算机断层扫描（CECT）表示允许容易地评估心腔容积和对比度动态的成像技术。通过这项工作，我们的目标是使用卷积神经网络的深度学习方法来解决这些潜在信息的提取和呈现问题。从没有造影剂的图像中提取相关特征开始，我们尝试将它们重新映射到CECT的典型特征上，以合成以心腔中的衰减为特征的图像，就好像注入了几乎碘的造影剂一样。目的是保证估计左心室容积并执行对比度动态的评估。我们的方法基于对120名患者进行训练的去卷积网络，这些患者在相同的造影动脉期和相同的心脏期进行了CT采集。为了确保可靠的预测CECT图像，在值和形态方面，通过组合误差函数来定义像素方式对应来定义自定义损失函数，其考虑输入和输出之间的Hounsfield单位的相似性。图像和通过在合成和真实CECT图像的二值化版本上计算的交叉熵。最后对20名受试者进行了测试。

##### URL
[http://arxiv.org/abs/1807.01779](http://arxiv.org/abs/1807.01779)

##### PDF
[http://arxiv.org/pdf/1807.01779](http://arxiv.org/pdf/1807.01779)

