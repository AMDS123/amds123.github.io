---
layout: post
title: "Auditing Black-Box Models Using Transparent Model Distillation With Side Information"
date: 2018-02-24 05:25:51
categories: arXiv_AI
tags: arXiv_AI Knowledge Prediction
author: Sarah Tan, Rich Caruana, Giles Hooker, Yin Lou
mathjax: true
---

* content
{:toc}

##### Abstract
Black-box risk scoring models permeate our lives, yet are typically proprietary or opaque. We propose a transparent model distillation approach to audit such models. Model distillation was first introduced to transfer knowledge from a large, complex teacher model to a faster, simpler student model without significant loss in prediction accuracy. To this we add a third criterion - transparency. To gain insight into black-box models, we treat them as teachers, training transparent student models to mimic the risk scores assigned by the teacher. Moreover, we use side information in the form of the actual outcomes the teacher scoring model was intended to predict in the first place. By training a second transparent model on the outcomes, we can compare the two models to each other. When comparing models trained on risk scores to models trained on outcomes, we show that it is necessary to calibrate the risk-scoring model's predictions to remove distortion that may have been added to the black-box risk-scoring model during or after its training process. We also show how to compute confidence intervals for the particular class of transparent student models we use - tree-based additive models with pairwise interactions (GA2Ms) - to support comparison of the two transparent models. We demonstrate the methods on four public datasets: COMPAS, Lending Club, Stop-and-Frisk, and Chicago Police.

##### Abstract (translated by Google)
黑盒风险评分模型渗透到我们的生活中，但通常是专有或不透明的。我们提出了一种透明的模型蒸馏方法来审计这些模型。首先引入了模型蒸馏，将知识从一个庞大复杂的教师模型转移到一个更快，更简单的学生模型，而不会显着降低预测的准确性。为此，我们增加了第三个标准 - 透明度。为了深入了解黑盒模型，我们将其视为教师，培训透明的学生模型以模拟教师分配的风险评分。此外，我们以教师评分模型预期首先预测的实际结果的形式使用辅助信息。通过对结果进行第二个透明模型的培训，我们可以将两种模型相互比较。当比较训练有关风险评分的模型和训练结果模型时，我们表明有必要校准风险评分模型的预测，以消除在训练过程中或之后可能添加到黑盒风险评分模型的失真。我们还展示了如何计算我们使用的特定类别透明学生模型（具有成对相互作用的基于树的可加模型（GA2Ms））的置信区间，以支持两个透明模型的比较。我们在四个公共数据集上展示了这些方法：COMPAS，Lending Club，Stop-and-Frisk和芝加哥警察。

##### URL
[http://arxiv.org/abs/1710.06169](http://arxiv.org/abs/1710.06169)

##### PDF
[http://arxiv.org/pdf/1710.06169](http://arxiv.org/pdf/1710.06169)

