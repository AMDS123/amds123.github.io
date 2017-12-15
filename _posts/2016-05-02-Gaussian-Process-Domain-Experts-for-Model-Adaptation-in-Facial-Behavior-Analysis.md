---
layout: post
title: "Gaussian Process Domain Experts for Model Adaptation in Facial Behavior Analysis"
date: 2016-05-02 18:54:08
categories: arXiv_CV
tags: arXiv_CV Face Classification Prediction
author: Stefanos Eleftheriadis, Ognjen Rudovic, Marc P. Deisenroth, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach for supervised domain adaptation that is based upon the probabilistic framework of Gaussian processes (GPs). Specifically, we introduce domain-specific GPs as local experts for facial expression classification from face images. The adaptation of the classifier is facilitated in probabilistic fashion by conditioning the target expert on multiple source experts. Furthermore, in contrast to existing adaptation approaches, we also learn a target expert from available target data solely. Then, a single and confident classifier is obtained by combining the predictions from multiple experts based on their confidence. Learning of the model is efficient and requires no retraining/reweighting of the source classifiers. We evaluate the proposed approach on two publicly available datasets for multi-class (MultiPIE) and multi-label (DISFA) facial expression classification. To this end, we perform adaptation of two contextual factors: 'where' (view) and 'who' (subject). We show in our experiments that the proposed approach consistently outperforms both source and target classifiers, while using as few as 30 target examples. It also outperforms the state-of-the-art approaches for supervised domain adaptation.

##### Abstract (translated by Google)
我们提出了一种基于高斯过程（GPs）的概率框架的监督域适应的新方法。具体而言，我们引入领域特定的GP作为面部表情分类的本地专家从面部图像。通过对多个源专家的目标专家进行调节，以概率的方式促进分类器的适应。此外，与现有的适应方法相比，我们也仅从目标数据中学习目标专家。然后，通过结合多位专家根据他们的置信度得出的预测结果，获得单一的自信分类器。学习模型是有效的，不需要对源分类器进行再训练/重新加权。我们评估提出的方法在两个公开可用的多类（MultiPIE）和多标签（DISFA）面部表情分类的数据集。为此，我们进行了两个语境因素的调整：“在哪里”（观点）和“谁”（主题）。我们在实验中表明，提出的方法始终优于源分类器和目标分类器，而只使用30个目标示例。它也超越了监督域适应的最先进的方法。

##### URL
[https://arxiv.org/abs/1604.02917](https://arxiv.org/abs/1604.02917)

##### PDF
[https://arxiv.org/pdf/1604.02917](https://arxiv.org/pdf/1604.02917)

