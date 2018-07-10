---
layout: post
title: "Automated and Interpretable Patient ECG Profiles for Disease Detection, Tracking, and Discovery"
date: 2018-07-06 21:12:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN Classification Quantitative Detection
author: Geoffrey H. Tison, Jeffrey Zhang, Francesca N. Delling, Rahul C. Deo
mathjax: true
---

* content
{:toc}

##### Abstract
The electrocardiogram or ECG has been in use for over 100 years and remains the most widely performed diagnostic test to characterize cardiac structure and electrical activity. We hypothesized that parallel advances in computing power, innovations in machine learning algorithms, and availability of large-scale digitized ECG data would enable extending the utility of the ECG beyond its current limitations, while at the same time preserving interpretability, which is fundamental to medical decision-making. We identified 36,186 ECGs from the UCSF database that were 1) in normal sinus rhythm and 2) would enable training of specific models for estimation of cardiac structure or function or detection of disease. We derived a novel model for ECG segmentation using convolutional neural networks (CNN) and Hidden Markov Models (HMM) and evaluated its output by comparing electrical interval estimates to 141,864 measurements from the clinical workflow. We built a 725-element patient-level ECG profile using downsampled segmentation data and trained machine learning models to estimate left ventricular mass, left atrial volume, mitral annulus e' and to detect and track four diseases: pulmonary arterial hypertension (PAH), hypertrophic cardiomyopathy (HCM), cardiac amyloid (CA), and mitral valve prolapse (MVP). CNN-HMM derived ECG segmentation agreed with clinical estimates, with median absolute deviations (MAD) as a fraction of observed value of 0.6% for heart rate and 4% for QT interval. Patient-level ECG profiles enabled quantitative estimates of left ventricular and mitral annulus e' velocity with good discrimination in binary classification models of left ventricular hypertrophy and diastolic function. Models for disease detection ranged from AUROC of 0.94 to 0.77 for MVP. Top-ranked variables for all models included known ECG characteristics along with novel predictors of these traits/diseases.

##### Abstract (translated by Google)
心电图或心电图已经使用了100多年，并且仍然是表征心脏结构和电活动的最广泛执行的诊断测试。我们假设计算能力的并行进步，机器学习算法的创新以及大规模数字化心电数据的可用性将使心电图的效用扩展到其当前的限制之外，同时保持可解释性，这是医学的基础。做决定。我们从UCSF数据库中确定了36,186个ECG，这些ECG是1）正常窦性心律，2）能够训练特定模型以估计心脏结构或功能或检测疾病。我们使用卷积神经网络（CNN）和隐马尔可夫模型（HMM）推导出一种新的心电图分割模型，并通过比较电气间期估计与临床工作流程中的141,864次测量来评估其输出。我们使用下采样分割数据和训练有素的机器学习模型构建了一个725元的患者级心电图，以评估左心室质量，左心房容积，二尖瓣环e'以及检测和跟踪四种疾病：肺动脉高压（PAH），肥厚心肌病（HCM），心脏淀粉样蛋白（CA）和二尖瓣脱垂（MVP）。 CNN-HMM衍生的ECG分割与临床估计一致，中位绝对偏差（MAD）为观察值的一部分，心率为0.6％，QT间期为4％。患者级心电图概况能够在左心室肥厚和舒张功能的二元分类模型中对左心室和二尖瓣环e'速度进行定量估计，并具有良好的区分。用于疾病检测的模型的MVP的AUROC为0.94至0.77。所有模型的排名靠前的变量包括已知的ECG特征以及这些特征/疾病的新预测因子。

##### URL
[http://arxiv.org/abs/1807.02569](http://arxiv.org/abs/1807.02569)

##### PDF
[http://arxiv.org/pdf/1807.02569](http://arxiv.org/pdf/1807.02569)

