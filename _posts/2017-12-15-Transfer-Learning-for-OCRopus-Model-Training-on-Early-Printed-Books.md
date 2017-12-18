---
layout: post
title: "Transfer Learning for OCRopus Model Training on Early Printed Books"
date: 2017-12-15 09:14:38
categories: arXiv_CV
tags: arXiv_CV OCR Transfer_Learning Recognition
author: Christian Reul, Christoph Wick, Uwe Springmann, Frank Puppe
mathjax: true
---

* content
{:toc}

##### Abstract
A method is presented that significantly reduces the character error rates for OCR text obtained from OCRopus models trained on early printed books when only small amounts of diplomatic transcriptions are available. This is achieved by building from already existing models during training instead of starting from scratch. To overcome the discrepancies between the set of characters of the pretrained model and the additional ground truth the OCRopus code is adapted to allow for alphabet expansion or reduction. The character set is now capable of flexibly adding and deleting characters from the pretrained alphabet when an existing model is loaded. For our experiments we use a self-trained mixed model on early Latin prints and the two standard OCRopus models on modern English and German Fraktur texts. The evaluation on seven early printed books showed that training from the Latin mixed model reduces the average amount of errors by 43% and 26%, respectively compared to training from scratch with 60 and 150 lines of ground truth, respectively. Furthermore, it is shown that even building from mixed models trained on data unrelated to the newly added training and test data can lead to significantly improved recognition results.

##### Abstract (translated by Google)
提出了一种方法，当只有少量的外交转录可用时，该方法显着降低了从在早期印刷书籍上训练的OCRopus模型获得的OCR文本的字符错误率。这是通过在培训期间从现有模型构建而不是从头开始实现的。为了克服预训练模型的字符集和额外的地面事实之间的差异，OCRopus代码被适配为允许字母扩展或缩小。字符集现在能够在加载现有模型时灵活地添加和删除预训练字母表中的字符。对于我们的实验，我们在早期的拉丁印刷品上使用自我训练的混合模型，在现代英语和德语Fraktur文本上使用两种标准OCRopus模型。早期七本书的评估结果显示，从拉丁语混合模式的训练分别比从60分和150分线的基础训练中分别减少了43％和26％的误差。此外，结果表明，即使从混合模型构建与新增加的训练和测试数据无关的数据，也可以显着改善识别结果。

##### URL
[http://arxiv.org/abs/1712.05586](http://arxiv.org/abs/1712.05586)

##### PDF
[http://arxiv.org/pdf/1712.05586](http://arxiv.org/pdf/1712.05586)

