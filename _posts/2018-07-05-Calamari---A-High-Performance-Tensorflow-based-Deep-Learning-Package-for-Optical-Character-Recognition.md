---
layout: post
title: "Calamari - A High-Performance Tensorflow-based Deep Learning Package for Optical Character Recognition"
date: 2018-07-05 13:46:37
categories: arXiv_CV
tags: arXiv_CV OCR CNN RNN Classification Deep_Learning Prediction Recognition
author: Christoph Wick, Christian Reul, Frank Puppe
mathjax: true
---

* content
{:toc}

##### Abstract
Optical Character Recognition (OCR) on contemporary and historical data is still in the focus of many researchers. Especially historical prints require book specific trained OCR models to achieve applicable results (Springmann and L\"udeling, 2016, Reul et al., 2017a). To reduce the human effort for manually annotating ground truth (GT) various techniques such as voting and pretraining have shown to be very efficient (Reul et al., 2018a, Reul et al., 2018b). Calamari is a new open source OCR line recognition software that both uses state-of-the art Deep Neural Networks (DNNs) implemented in Tensorflow and giving native support for techniques such as pretraining and voting. The customizable network architectures constructed of Convolutional Neural Networks (CNNS) and Long-ShortTerm-Memory (LSTM) layers are trained by the so-called Connectionist Temporal Classification (CTC) algorithm of Graves et al. (2006). Optional usage of a GPU drastically reduces the computation times for both training and prediction. We use two different datasets to compare the performance of Calamari to OCRopy, OCRopus3, and Tesseract 4. Calamari reaches a Character Error Rate (CER) of 0.11% on the UW3 dataset written in modern English and 0.18% on the DTA19 dataset written in German Fraktur, which considerably outperforms the results of the existing softwares.

##### Abstract (translated by Google)
关于当代和历史数据的光学字符识别（OCR）仍然是许多研究人员关注的焦点。特别是历史版画需要书籍特定的训练OCR模型才能达到适用的结果（Springmann和L \“udeling，2016，Reul等，2017a）。减少人工注意地面实况（GT）的各种技巧，如投票和预训练已经证明是非常有效的（Reul等，2018a，Reul等，2018b）.Calamari是一种新的开源OCR线识别软件，它使用了最先进的深度神经网络（DNN）。 Tensorflow并为预训练和投票等技术提供原生支持。由卷积神经网络（CNNS）和长短时间内存（LSTM）层构成的可定制网络架构通过所谓的连接主义时间分类（CTC）算法进行训练。 Graves等人（2006）.GPU的可选用法大大减少了训练和预测的计算时间。我们使用两个不同的数据集来比较Calamari与OCRopy，OCRopus3和Tesseract 4. Calamari在用现代英语编写的UW3数据集上达到0.11％的字符错误率（CER），在用德语Fraktur编写的DTA19数据集上达到0.18％，其显着优于现有软件的结果。

##### URL
[http://arxiv.org/abs/1807.02004](http://arxiv.org/abs/1807.02004)

##### PDF
[http://arxiv.org/pdf/1807.02004](http://arxiv.org/pdf/1807.02004)

