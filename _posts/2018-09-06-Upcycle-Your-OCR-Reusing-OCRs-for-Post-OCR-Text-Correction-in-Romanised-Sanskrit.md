---
layout: post
title: "Upcycle Your OCR: Reusing OCRs for Post-OCR Text Correction in Romanised Sanskrit"
date: 2018-09-06 18:02:55
categories: arXiv_CL
tags: arXiv_CL OCR Survey Prediction Recognition
author: Amrith Krishna, Bodhisattwa Prasad Majumder, Rajesh Shreedhar Bhat, Pawan Goyal
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a post-OCR text correction approach for digitising texts in Romanised Sanskrit. Owing to the lack of resources our approach uses OCR models trained for other languages written in Roman. Currently, there exists no dataset available for Romanised Sanskrit OCR. So, we bootstrap a dataset of 430 images, scanned in two different settings and their corresponding ground truth. For training, we synthetically generate training images for both the settings. We find that the use of copying mechanism (Gu et al., 2016) yields a percentage increase of 7.69 in Character Recognition Rate (CRR) than the current state of the art model in solving monotone sequence-to-sequence tasks (Schnober et al., 2016). We find that our system is robust in combating OCR-prone errors, as it obtains a CRR of 87.01% from an OCR output with CRR of 35.76% for one of the dataset settings. A human judgment survey performed on the models shows that our proposed model results in predictions which are faster to comprehend and faster to improve for a human than the other systems.

##### Abstract (translated by Google)
我们提出了一种后OCR文本校正方法，用于数字化罗马化梵语中的文本。由于缺乏资源，我们的方法使用针对罗马语编写的其他语言训练的OCR模型。目前，没有可用于Romanised Sanskrit OCR的数据集。因此，我们引导了430个图像的数据集，在两个不同的设置中扫描它们相应的基本事实。对于训练，我们综合生成两种设置的训练图像。我们发现复制机制的使用（Gu et al。，2016）在字符识别率（CRR）中比现有技术模型在解决单调序列到序列任务时产生了7.69的百分比增长（Schnober et al 。，2016）。我们发现我们的系统在抵抗容易出现OCR的错误方面非常强大，因为它从一个OCR输出获得了87.01％的CRR，其中一个数据集设置的CRR为35.76％。对模型进行的人工判断调查显示，我们提出的模型可以产生比其他系统更快理解和更快地改进人类的预测。

##### URL
[https://arxiv.org/abs/1809.02147](https://arxiv.org/abs/1809.02147)

##### PDF
[https://arxiv.org/pdf/1809.02147](https://arxiv.org/pdf/1809.02147)

