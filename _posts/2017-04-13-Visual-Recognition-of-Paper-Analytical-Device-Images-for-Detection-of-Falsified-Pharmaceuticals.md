---
layout: post
title: "Visual Recognition of Paper Analytical Device Images for Detection of Falsified Pharmaceuticals"
date: 2017-04-13 18:35:33
categories: arXiv_CV
tags: arXiv_CV CNN Detection Recognition
author: Sandipan Banerjee, James Sweet, Christopher Sweet, Marya Lieberman
mathjax: true
---

* content
{:toc}

##### Abstract
Falsification of medicines is a big problem in many developing countries, where technological infrastructure is inadequate to detect these harmful products. We have developed a set of inexpensive paper cards, called Paper Analytical Devices (PADs), which can efficiently classify drugs based on their chemical composition, as a potential solution to the problem. These cards have different reagents embedded in them which produce a set of distinctive color descriptors upon reacting with the chemical compounds that constitute pharmaceutical dosage forms. If a falsified version of the medicine lacks the active ingredient or includes substitute fillers, the difference in color is perceivable by humans. However, reading the cards with accuracy takes training and practice, which may hamper their scaling and implementation in low resource settings. To deal with this, we have developed an automatic visual recognition system to read the results from the PAD images. At first, the optimal set of reagents was found by running singular value decomposition on the intensity values of the color tones in the card images. A dataset of cards embedded with these reagents is produced to generate the most distinctive results for a set of 26 different active pharmaceutical ingredients (APIs) and excipients. Then, we train two popular convolutional neural network (CNN) models, with the card images. We also extract some "hand-crafted" features from the images and train a nearest neighbor classifier and a non-linear support vector machine with them. On testing, higher-level features performed much better in accurately classifying the PAD images, with the CNN models reaching the highest average accuracy of over 94\%.

##### Abstract (translated by Google)
伪造药品是许多发展中国家的一个大问题，在这些国家，技术基础设施不足以检测这些有害产品。我们已经开发了一套名为纸张分析设备（PADs）的廉价纸卡，它可以根据化学成分有效地对药物进行分类，作为解决这个问题的一个潜在的解决方案。这些卡片中嵌入不同的试剂，与构成药物剂型的化学化合物反应后产生一组不同的颜色描述符。如果伪造的药物缺乏活性成分或包含替代填充剂，则颜色的差异可由人类察觉。然而，准确地读卡需要训练和练习，这可能妨碍他们在低资源环境下的扩展和实施。为了解决这个问题，我们开发了一个自动视觉识别系统来读取PAD图像的结果。首先，通过对卡片图像中色调的强度值进行奇异值分解，找到最佳的试剂组。生产嵌入这些试剂卡片的数据集，以产生一组26种不同的活性药物成分（API）和赋形剂的最显着的结果。然后，我们用卡片图像训练两种流行的卷积神经网络（CNN）模型。我们还从图像中提取一些“手工制作”的特征，并用它们训练最近邻分类器和非线性支持向量机。在测试中，高级特征在准确分类PAD图像方面表现得更好，CNN模型达到了94％以上的最高平均精度。

##### URL
[https://arxiv.org/abs/1704.04251](https://arxiv.org/abs/1704.04251)

##### PDF
[https://arxiv.org/pdf/1704.04251](https://arxiv.org/pdf/1704.04251)

