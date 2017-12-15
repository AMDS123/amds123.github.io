---
layout: post
title: "DNN adaptation by automatic quality estimation of ASR hypotheses"
date: 2017-02-06 17:21:39
categories: arXiv_SD
tags: arXiv_SD Prediction
author: Daniele Falavigna, Marco Matassoni, Shahab Jalalvand, Matteo Negri, Marco Turchi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose to exploit the automatic Quality Estimation (QE) of ASR hypotheses to perform the unsupervised adaptation of a deep neural network modeling acoustic probabilities. Our hypothesis is that significant improvements can be achieved by: i)automatically transcribing the evaluation data we are currently trying to recognise, and ii) selecting from it a subset of "good quality" instances based on the word error rate (WER) scores predicted by a QE component. To validate this hypothesis, we run several experiments on the evaluation data sets released for the CHiME-3 challenge. First, we operate in oracle conditions in which manual transcriptions of the evaluation data are available, thus allowing us to compute the "true" sentence WER. In this scenario, we perform the adaptation with variable amounts of data, which are characterised by different levels of quality. Then, we move to realistic conditions in which the manual transcriptions of the evaluation data are not available. In this case, the adaptation is performed on data selected according to the WER scores "predicted" by a QE component. Our results indicate that: i) QE predictions allow us to closely approximate the adaptation results obtained in oracle conditions, and ii) the overall ASR performance based on the proposed QE-driven adaptation method is significantly better than the strong, most recent, CHiME-3 baseline.

##### Abstract (translated by Google)
在本文中，我们建议利用ASR假设的自动质量估计（QE）来执行深度神经网络建模声学概率的无监督自适应。我们的假设是可以通过以下方式实现显着的改进：i）自动转录我们当前正在尝试识别的评估数据，以及ii）基于预测的字错误率（WER）分数从其中选择一个“优质”实例的子集由QE组件。为了验证这个假设，我们针对CHiME-3挑战公布的评估数据集进行了几次实验。首先，我们在预言评估数据的手工记录的情况下运行，从而允许我们计算“真实”的句子WER。在这种情况下，我们使用不同数量的数据进行适应性调整，这些数据具有不同的质量水平。然后，我们转到实际情况，其中评估数据的手动转录不可用。在这种情况下，对根据由QE组件“预测”的WER分数选择的数据执行适配。我们的研究结果表明：（1）QE预测使得我们能够近似得到在预言条件下得到的适应结果;（2）基于所提出的QE驱动的适应方法的整体ASR性能明显优于强的，最近的CHiME- 3基线。

##### URL
[https://arxiv.org/abs/1702.01714](https://arxiv.org/abs/1702.01714)

##### PDF
[https://arxiv.org/pdf/1702.01714](https://arxiv.org/pdf/1702.01714)

