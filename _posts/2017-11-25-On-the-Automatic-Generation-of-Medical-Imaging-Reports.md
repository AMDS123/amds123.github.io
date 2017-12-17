---
layout: post
title: "On the Automatic Generation of Medical Imaging Reports"
date: 2017-11-25 21:49:03
categories: arXiv_CV
tags: arXiv_CV Attention RNN Prediction
author: Baoyu Jing, Pengtao Xie, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Medical imaging is widely used in clinical practice for diagnosis and treatment. Specialized physicians read medical images and write textual reports to narrate the findings. Report-writing can be error-prone for unexperienced physicians, and time-consuming and tedious for physicians in highly populated nations. To address these issues, we study the automatic generation of medical imaging reports, as an assistance for human physicians in producing reports more accurately and efficiently. This task presents several challenges. First, a complete report contains multiple heterogeneous forms of information, including findings which are paragraphs and tags which are a list of key words. Second, abnormal regions in medical images are difficult to identify. Generating textual narrations for them is even harder. Third, the reports are typically long, containing multiple paragraphs. To cope with these challenges, we (1) build a multi-task learning framework which jointly performs the prediction of tags and the generation of paragraphs, (2) propose a co-attention mechanism to localize regions containing abnormalities and generate narrations for them, (3) develop a hierarchical LSTM model to generate long para- graphs. We demonstrate the effectiveness of the proposed methods on a chest x-ray dataset and a pathology dataset.

##### Abstract (translated by Google)
医学影像在临床实践中被广泛应用于诊断和治疗。专业医生阅读医学图像，并撰写文字报告来叙述研究结果。对于没有经验的医生来说，撰写报告可能会很容易出错，对于人口稠密的国家的医生来说，这是一项耗费时间和繁琐的工作。为了解决这些问题，我们研究了医学影像报告的自动生成，作为人类医生更准确高效地生成报告的辅助工具。这个任务提出了几个挑战。首先，一个完整的报告包含多种不同形式的信息，包括发现是关键词列表的段落和标签。其次，医学图像中的异常区域很难识别。为他们生成文字叙述更加困难。第三，报告通常很长，包含多个段落。为了应对这些挑战，我们（1）构建了一个多任务的学习框架，共同完成标签的预测和段落的生成，（2）提出一个共同注意机制，对含有异常的地域进行本地化， （3）开发一个层次LSTM模型来生成长段。我们证明了所提出的方法在胸部X射线数据集和病理数据集上的有效性。

##### URL
[https://arxiv.org/abs/1711.08195](https://arxiv.org/abs/1711.08195)

##### PDF
[https://arxiv.org/pdf/1711.08195](https://arxiv.org/pdf/1711.08195)

