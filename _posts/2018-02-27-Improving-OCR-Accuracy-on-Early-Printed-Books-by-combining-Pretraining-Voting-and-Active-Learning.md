---
layout: post
title: "Improving OCR Accuracy on Early Printed Books by combining Pretraining, Voting, and Active Learning"
date: 2018-02-27 17:35:36
categories: arXiv_CV
tags: arXiv_CV OCR
author: Christian Reul, Uwe Springmann, Christoph Wick, Frank Puppe
mathjax: true
---

* content
{:toc}

##### Abstract
We combine three methods which significantly improve the OCR accuracy of OCR mod-els trained on early printed books: (1) The pretraining method utilizes the informationstored in already existing models trained on a variety of typesets (mixed models) insteadof starting the training from scratch. (2) Performing cross fold training on a single setof ground truth data (line images and their transcriptions) with a single OCR engine(OCRopus) produces a committee whose members then vote for the best outcome byalso taking the top-N alternatives and their intrinsic confidence values into account.(3) Following the principle of maximal disagreement we select additional training lineswhich the voters disagree most on, expecting them to offer the highest informationgain for a subsequent training (active learning). Evaluations on six early printed booksyielded the following results: On average the combination of pretraining and votingimproved the character accuracy by 46% when training five folds starting from the samemixed model. This number rose to 53% when using different models for pretraining,underlining the importance of diverse voters. Incorporating active learning improvedthe obtained results by another 16% on average (evaluated on three of the six books).Overall, the proposed methods lead to an average error rate of 2.5% when training ononly 60 lines. Using a substantial ground truth pool of 1,000 lines brought the errorrate down even further to less than 1% on average.

##### Abstract (translated by Google)
我们结合了三种方法，这些方法显着提高了在早期印刷书籍上训练的OCR模型的OCR准确性：（1）预训练方法利用存储在已有模型上的信息存储在各种排版（混合模型）上，而不是从头开始训练。 （2）使用单一OCR引擎（OCRopus）对单一地面真实数据（线条图像及其转录）进行交叉褶皱训练产生一个委员会，其成员然后通过同时考虑最佳N替代方案和他们的内在方案投票选出最佳结果（3）遵循最大分歧原则，我们选择额外的选民最不同意的训练路线，期望他们为后续训练（主动学习）提供最高的信息价值。对六本早期印刷书籍的评估得出以下结果：平均而言，训练和投票的组合在从同一混合模型开始训练五个折叠时提高了46％的字符准确性。使用不同模式进行训练时，这一数字上升到53％，强调了不同选民的重要性。结合主动学习将所得结果平均提高了16％（在六本书中的三本中评估）。总体而言，所提出的方法在仅训练60行时导致平均错误率为2.5％。使用大量1,000条线路的基础真值池，将误差率进一步降低到平均不到1％。

##### URL
[https://arxiv.org/abs/1802.10038](https://arxiv.org/abs/1802.10038)

##### PDF
[https://arxiv.org/pdf/1802.10038](https://arxiv.org/pdf/1802.10038)

