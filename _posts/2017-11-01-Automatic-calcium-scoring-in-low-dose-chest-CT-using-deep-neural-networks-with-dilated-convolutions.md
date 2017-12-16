---
layout: post
title: "Automatic calcium scoring in low-dose chest CT using deep neural networks with dilated convolutions"
date: 2017-11-01 13:54:55
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Nikolas Lessmann, Bram van Ginneken, Majd Zreik, Pim A. de Jong, Bob D. de Vos, Max A. Viergever, Ivana Išgum
mathjax: true
---

* content
{:toc}

##### Abstract
Heavy smokers undergoing screening with low-dose chest CT are affected by cardiovascular disease as much as by lung cancer. Low-dose chest CT scans acquired in screening enable quantification of atherosclerotic calcifications and thus enable identification of subjects at increased cardiovascular risk. This paper presents a method for automatic detection of coronary artery, thoracic aorta and cardiac valve calcifications in low-dose chest CT using two consecutive convolutional neural networks. The first network identifies and labels potential calcifications according to their anatomical location and the second network identifies true calcifications among the detected candidates. This method was trained and evaluated on a set of 1744 CT scans from the National Lung Screening Trial. To determine whether any reconstruction or only images reconstructed with soft tissue filters can be used for calcification detection, we evaluated the method on soft and medium/sharp filter reconstructions separately. On soft filter reconstructions, the method achieved F1 scores of 0.89, 0.89, 0.67, and 0.55 for coronary artery, thoracic aorta, aortic valve and mitral valve calcifications, respectively. On sharp filter reconstructions, the F1 scores were 0.84, 0.81, 0.64, and 0.66, respectively. Linearly weighted kappa coefficients for risk category assignment based on per subject coronary artery calcium were 0.91 and 0.90 for soft and sharp filter reconstructions, respectively. These results demonstrate that the presented method enables reliable automatic cardiovascular risk assessment in all low-dose chest CT scans acquired for lung cancer screening.

##### Abstract (translated by Google)
接受小剂量胸部CT检查的重度吸烟者与心脏病相同，受肺癌的影响。通过筛查获得的低剂量胸部CT扫描可以对动脉粥样硬化钙化进行定量，从而能够识别心血管风险增加的受试者。本文提出了一种使用两个连续的卷积神经网络在低剂量胸部CT中自动检测冠状动脉，胸主动脉和心脏瓣膜钙化的方法。第一个网络根据其解剖位置识别和标记可能的钙化点，第二个网络识别检测到的候选者之间的真实钙化点。该方法经过全国肺部筛查试验的1744个CT扫描的训练和评估。为了确定是否重建或只用软组织过滤器重建的图像可以用于钙化检测，我们分别评估软和中等/尖锐的过滤器重建的方法。在软滤片重建方面，冠状动脉，胸主动脉，主动脉瓣和二尖瓣钙化的F1分别为0.89,0.89,0.67和0.55。在锋利的过滤器重建，F1分数分别为0.84,0.81,0.64和0.66。用于基于每个受试者冠状动脉钙的风险类别分配的线性加权Kappa系数分别为0.91和0.90，用于软和尖锐的滤波器重建。这些结果表明，所提出的方法能够在所有用于肺癌筛查的低剂量胸部CT扫描中进行可靠的自动心血管风险评估。

##### URL
[https://arxiv.org/abs/1711.00349](https://arxiv.org/abs/1711.00349)

##### PDF
[https://arxiv.org/pdf/1711.00349](https://arxiv.org/pdf/1711.00349)

