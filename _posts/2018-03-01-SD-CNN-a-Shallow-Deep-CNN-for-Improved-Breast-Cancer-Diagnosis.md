---
layout: post
title: "SD-CNN: a Shallow-Deep CNN for Improved Breast Cancer Diagnosis"
date: 2018-03-01 23:59:20
categories: arXiv_CV
tags: arXiv_CV CNN
author: Fei Gao, Teresa Wu, Jing Li, Bin Zheng, Lingxiang Ruan, Desheng Shang, Bhavika Patel
mathjax: true
---

* content
{:toc}

##### Abstract
Breast cancer is the second leading cause of cancer death among women worldwide. Nevertheless, it is also one of the most treatable malignances if detected early. Screening for breast cancer with digital mammography (DM) has been widely used. However it demonstrates limited sensitivity for women with dense breasts. An emerging technology in the field is contrast-enhanced digital mammography (CEDM), which includes a low energy (LE) image similar to DM, and a recombined image leveraging tumor neoangiogenesis similar to breast magnetic resonance imaging (MRI). CEDM has shown better diagnostic accuracy than DM. While promising, CEDM is not yet widely available across medical centers. In this research, we propose a Shallow-Deep Convolutional Neural Network (SD-CNN) where a shallow CNN is developed to derive "virtual" recombined images from LE images, and a deep CNN is employed to extract novel features from LE, recombined or "virtual" recombined images for ensemble models to classify the cases as benign vs. cancer. To evaluate the validity of our approach, we first develop a deep-CNN using 49 CEDM cases collected from Mayo Clinic to prove the contributions from recombined images for improved breast cancer diagnosis (0.86 in accuracy using LE imaging vs. 0.90 in accuracy using both LE and recombined imaging). We then develop a shallow-CNN using the same 49 CEDM cases to learn the nonlinear mapping from LE to recombined images. Next, we use 69 DM cases collected from the hospital located at Zhejiang University, China to generate "virtual" recombined images. Using DM alone provides 0.91 in accuracy, whereas SD-CNN improves the diagnostic accuracy to 0.95.

##### Abstract (translated by Google)
乳腺癌是全球女性癌症死亡的第二大原因。尽管如此，如果发现得早，它也是最容易治愈的恶性肿瘤之一。数字乳腺摄影（DM）筛查乳腺癌已被广泛使用。然而，对于密集乳房的女性而言，它表现出有限的敏感性该领域的新兴技术是对比增强数字乳腺X线照相术（CEDM），其包括类似于DM的低能量（LE）图像和利用类似于乳房磁共振成像（MRI）的肿瘤新血管生成的重组图像。 CEDM显示出比DM更好的诊断准确性。虽然有希望，但CEDM尚未在各医疗中心广泛使用。在这项研究中，我们提出了浅层深度卷积神经网络（SD-CNN），其中浅CNN被开发用于从LE图像中导出“虚拟”重组图像，并且深CNN被用于从LE中提取新特征，重新组合用于整体模型的“虚拟”重组图像将病例分类为良性和癌症。为了评估我们方法的有效性，我们首先使用Mayo Clinic收集的49个CEDM病例开发深CNN，以证明重组图像对改善乳腺癌诊断的贡献（使用LE成像准确度为0.86，准确度为0.90，均使用LE并重新组合成像）。然后，我们使用相同的49个CEDM案例开发浅CNN以学习从LE到重组图像的非线性映射。接下来，我们使用中国浙江大学医院收集的69例DM病例生成“虚拟”重组图像。单独使用DM可提供0.91的准确度，而SD-CNN将诊断准确度提高到0.95。

##### URL
[http://arxiv.org/abs/1803.00663](http://arxiv.org/abs/1803.00663)

##### PDF
[http://arxiv.org/pdf/1803.00663](http://arxiv.org/pdf/1803.00663)

