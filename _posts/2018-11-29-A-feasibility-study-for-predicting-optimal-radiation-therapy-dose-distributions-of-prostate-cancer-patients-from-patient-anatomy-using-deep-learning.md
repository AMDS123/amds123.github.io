---
layout: post
title: "A feasibility study for predicting optimal radiation therapy dose distributions of prostate cancer patients from patient anatomy using deep learning"
date: 2018-11-29 21:34:27
categories: arXiv_AI
tags: arXiv_AI Segmentation GAN CNN Optimization Deep_Learning Prediction
author: Dan Nguyen, Troy Long, Xun Jia, Weiguo Lu, Xuejun Gu, Zohaib Iqbal, Steve Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
With the advancement of treatment modalities in radiation therapy for cancer patients, outcomes have improved, but at the cost of increased treatment plan complexity and planning time. The accurate prediction of dose distributions would alleviate this issue by guiding clinical plan optimization to save time and maintain high quality plans. We have modified a convolutional deep network model, U-net (originally designed for segmentation purposes), for predicting dose from patient image contours of the planning target volume (PTV) and organs at risk (OAR). We show that, as an example, we are able to accurately predict the dose of intensity-modulated radiation therapy (IMRT) for prostate cancer patients, where the average Dice similarity coefficient is 0.91 when comparing the predicted vs. true isodose volumes between 0% and 100% of the prescription dose. The average value of the absolute differences in [max, mean] dose is found to be under 5% of the prescription dose, specifically for each structure is [1.80%, 1.03%](PTV), [1.94%, 4.22%](Bladder), [1.80%, 0.48%](Body), [3.87%, 1.79%](L Femoral Head), [5.07%, 2.55%](R Femoral Head), and [1.26%, 1.62%](Rectum) of the prescription dose. We thus managed to map a desired radiation dose distribution from a patient's PTV and OAR contours. As an additional advantage, relatively little data was used in the techniques and models described in this paper.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.09233](http://arxiv.org/abs/1709.09233)

##### PDF
[http://arxiv.org/pdf/1709.09233](http://arxiv.org/pdf/1709.09233)

