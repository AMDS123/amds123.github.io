---
layout: post
title: "Predicting breast tumor proliferation from whole-slide images: the TUPAC16 challenge"
date: 2018-07-22 13:46:03
categories: arXiv_CV
tags: arXiv_CV GAN Prediction Detection Relation
author: Mitko Veta, Yujing J. Heng, Nikolas Stathonikos, Babak Ehteshami Bejnordi, Francisco Beca, Thomas Wollmann, Karl Rohr, Manan A. Shah, Dayong Wang, Mikael Rousson, Martin Hedlund, David Tellez, Francesco Ciompi, Erwan Zerhouni, David Lanyi, Matheus Viana, Vassili Kovalev, Vitali Liauchuk, Hady Ahmady Phoulady, Talha Qaiser, Simon Graham, Nasir Rajpoot, Erik Sj&#xf6;blom, Jesper Molin, Kyunghyun Paeng, Sangheum Hwang, Sunggyun Park, Zhipeng Jia, Eric I-Chao Chang, Yan Xu, Andrew H. Beck, Paul J. van Diest, Josien P. W. Pluim
mathjax: true
---

* content
{:toc}

##### Abstract
Tumor proliferation is an important biomarker indicative of the prognosis of breast cancer patients. Assessment of tumor proliferation in a clinical setting is highly subjective and labor-intensive task. Previous efforts to automate tumor proliferation assessment by image analysis only focused on mitosis detection in predefined tumor regions. However, in a real-world scenario, automatic mitosis detection should be performed in whole-slide images (WSIs) and an automatic method should be able to produce a tumor proliferation score given a WSI as input. To address this, we organized the TUmor Proliferation Assessment Challenge 2016 (TUPAC16) on prediction of tumor proliferation scores from WSIs. The challenge dataset consisted of 500 training and 321 testing breast cancer histopathology WSIs. In order to ensure fair and independent evaluation, only the ground truth for the training dataset was provided to the challenge participants. The first task of the challenge was to predict mitotic scores, i.e., to reproduce the manual method of assessing tumor proliferation by a pathologist. The second task was to predict the gene expression based PAM50 proliferation scores from the WSI. The best performing automatic method for the first task achieved a quadratic-weighted Cohen's kappa score of $\kappa$ = 0.567, 95% CI [0.464, 0.671] between the predicted scores and the ground truth. For the second task, the predictions of the top method had a Spearman's correlation coefficient of r = 0.617, 95% CI [0.581 0.651] with the ground truth. This was the first study that investigated tumor proliferation assessment from WSIs. The achieved results are promising given the difficulty of the tasks and weakly-labelled nature of the ground truth. However, further research is needed to improve the practical utility of image analysis methods for this task.

##### Abstract (translated by Google)
肿瘤增殖是指示乳腺癌患者预后的重要生物标志物。在临床环境中评估肿瘤增殖是非常主观和劳动密集型的任务。通过图像分析自动化肿瘤增殖评估的先前努力仅集中于预定义肿瘤区域中的有丝分裂检测。然而，在现实世界的情况下，应该在全幻灯片图像（WSI）中执行自动有丝分裂检测，并且自动方法应该能够在WSI作为输入的情况下产生肿瘤增殖分数。为解决这个问题，我们组织了2016年TUmor增殖评估挑战赛（TUPAC16），以预测WSI的肿瘤增殖评分。挑战数据集包括500次训练和321次乳腺癌组织病理学WSI测试。为了确保公平和独立的评估，仅向挑战参与者提供了培训数据集的基本事实。挑战的第一个任务是预测有丝分裂评分，即，再现由病理学家评估肿瘤增殖的手动方法。第二项任务是根据WSI预测基于PAM50增殖分数的基因表达。第一项任务的最佳表现自动方法在预测得分和基本事实之间实现了二次加权Cohen的kappa得分$ \ kappa $ = 0.567,95％CI [0.464,0.671]。对于第二项任务，top方法的预测具有Spearman相关系数r = 0.617,95％CI [0.581 0.651]与基本事实。这是第一项研究WSI肿瘤增殖评估的研究。鉴于任务的难度和基本事实的弱标记性质，取得的成果是有希望的。然而，需要进一步研究以提高图像分析方法在该任务中的实际应用。

##### URL
[http://arxiv.org/abs/1807.08284](http://arxiv.org/abs/1807.08284)

##### PDF
[http://arxiv.org/pdf/1807.08284](http://arxiv.org/pdf/1807.08284)

