---
layout: post
title: "Neural Classification of Malicious Scripts: A study with JavaScript and VBScript"
date: 2018-05-15 07:22:24
categories: arXiv_AI
tags: arXiv_AI Embedding RNN Classification
author: Jack W. Stokes, Rakshit Agrawal, Geoff McDonald
mathjax: true
---

* content
{:toc}

##### Abstract
Malicious scripts are an important computer infection threat vector. Our analysis reveals that the two most prevalent types of malicious scripts include JavaScript and VBScript. The percentage of detected JavaScript attacks are on the rise. To address these threats, we investigate two deep recurrent models, LaMP (LSTM and Max Pooling) and CPoLS (Convoluted Partitioning of Long Sequences), which process JavaScript and VBScript as byte sequences. Lower layers capture the sequential nature of these byte sequences while higher layers classify the resulting embedding as malicious or benign. Unlike previously proposed solutions, our models are trained in an end-to-end fashion allowing discriminative training even for the sequential processing layers. Evaluating these models on a large corpus of 296,274 JavaScript files indicates that the best performing LaMP model has a 65.9% true positive rate (TPR) at a false positive rate (FPR) of 1.0%. Similarly, the best CPoLS model has a TPR of 45.3% at an FPR of 1.0%. LaMP and CPoLS yield a TPR of 69.3% and 67.9%, respectively, at an FPR of 1.0% on a collection of 240,504 VBScript files.

##### Abstract (translated by Google)
恶意脚本是重要的计算机感染威胁载体。我们的分析表明，两种最流行的恶意脚本类型包括JavaScript和VBScript。检测到的JavaScript攻击的比例正在上升。为了解决这些威胁，我们调查了两种经常性模型，即LaMP（LSTM和Max Pooling）和CPoLS（长序列的卷积分割），它们将JavaScript和VBScript作为字节序列进行处理。较低层捕获这些字节序列的顺序性质，而较高层将得到的嵌入分类为恶意或良性。与以前提出的解决方案不同，我们的模型以端到端的方式进行培训，即使对于顺序处理层也可以进行有区别的培训。在296,274个JavaScript文件的大型语料库上评估这些模型表明，在假阳性率（FPR）为1.0％时，表现最好的LaMP模型的真实阳性率（TPR）为65.9％。同样，最好的CPoLS模型在FPR为1.0％时TPR为45.3％。 LaMP和CPoLS在240,504个VBScript文件集合的FPR为1.0％时分别产生69.3％和67.9％的TPR。

##### URL
[http://arxiv.org/abs/1805.05603](http://arxiv.org/abs/1805.05603)

##### PDF
[http://arxiv.org/pdf/1805.05603](http://arxiv.org/pdf/1805.05603)

