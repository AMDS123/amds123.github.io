---
layout: post
title: "Predicting and Understanding Law-Making with Word Vectors and an Ensemble Model"
date: 2017-04-29 17:12:33
categories: arXiv_CL
tags: arXiv_CL Language_Model Prediction
author: John J. Nay
mathjax: true
---

* content
{:toc}

##### Abstract
Out of nearly 70,000 bills introduced in the U.S. Congress from 2001 to 2015, only 2,513 were enacted. We developed a machine learning approach to forecasting the probability that any bill will become law. Starting in 2001 with the 107th Congress, we trained models on data from previous Congresses, predicted all bills in the current Congress, and repeated until the 113th Congress served as the test. For prediction we scored each sentence of a bill with a language model that embeds legislative vocabulary into a high-dimensional, semantic-laden vector space. This language representation enables our investigation into which words increase the probability of enactment for any topic. To test the relative importance of text and context, we compared the text model to a context-only model that uses variables such as whether the bill's sponsor is in the majority party. To test the effect of changes to bills after their introduction on our ability to predict their final outcome, we compared using the bill text and meta-data available at the time of introduction with using the most recent data. At the time of introduction context-only predictions outperform text-only, and with the newest data text-only outperforms context-only. Combining text and context always performs best. We conducted a global sensitivity analysis on the combined model to determine important variables predicting enactment.

##### Abstract (translated by Google)
2001年至2015年，美国国会通过的近7万份法案中，仅有2513份。我们开发了机器学习方法来预测任何账单将成为法律的可能性。从2001年的第107届大会开始，我们训练了以前大会的数据模型，预测了现在国会的所有议案，并一直重复，直到第113届国会作为考验。为了进行预测，我们用语言模型对法案的每个句子进行评分，这种语言模型将立法词汇嵌入到高维，语义载体向量空间中。这种语言表达使我们能够调查哪些词增加了任何主题的制定概率。为了测试文本和上下文的相对重要性，我们将文本模型与仅使用变量的上下文模型（比如账单的赞助者是否在多数派对）进行比较。为了测试引入之后账单变更对预测他们最终结果的能力的影响，我们使用最新的数据在引入时使用了账单文本和元数据进行了比较。在引入时，仅上下文预测优于纯文本，而最新数据文本仅胜于上下文。结合文本和上下文总是表现最好。我们对组合模型进行了全局敏感性分析，以确定预测颁布的重要变量。

##### URL
[https://arxiv.org/abs/1607.02109](https://arxiv.org/abs/1607.02109)

##### PDF
[https://arxiv.org/pdf/1607.02109](https://arxiv.org/pdf/1607.02109)

