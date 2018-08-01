---
layout: post
title: "Leveraging Unlabeled Whole-Slide-Images for Mitosis Detection"
date: 2018-07-31 06:19:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Saad Ullah Akram, Talha Qaiser, Simon Graham, Juho Kannala, Janne Heikkil&#xe4;, Nasir Rajpoot
mathjax: true
---

* content
{:toc}

##### Abstract
Mitosis count is an important biomarker for prognosis of various cancers. At present, pathologists typically perform manual counting on a few selected regions of interest in breast whole-slide-images (WSIs) of patient biopsies. This task is very time-consuming, tedious and subjective. Automated mitosis detection methods have made great advances in recent years. However, these methods require exhaustive labeling of a large number of selected regions of interest. This task is very expensive because expert pathologists are needed for reliable and accurate annotations. In this paper, we present a semi-supervised mitosis detection method which is designed to leverage a large number of unlabeled breast cancer WSIs. As a result, our method capitalizes on the growing number of digitized histology images, without relying on exhaustive annotations, subsequently improving mitosis detection. Our method first learns a mitosis detector from labeled data, uses this detector to mine additional mitosis samples from unlabeled WSIs, and then trains the final model using this larger and diverse set of mitosis samples. The use of unlabeled data improves F1-score by $\sim$5\% compared to our best performing fully-supervised model on the TUPAC validation set. Our submission (single model) to TUPAC challenge ranks highly on the leaderboard with an F1-score of 0.64.

##### Abstract (translated by Google)
有丝分裂计数是各种癌症预后的重要生物标志物。目前，病理学家通常对患者活组织检查的乳房全幻灯片图像（WSI）中的一些选定感兴趣区域进行手动计数。这项任务非常耗时，乏味且主观。近年来，自动有丝分裂检测方法取得了很大进展。然而，这些方法需要对大量选定的感兴趣区域进行详尽的标记。这项任务非常昂贵，因为需要专家病理学家来进行可靠和准确的注释。在本文中，我们提出了一种半监督有丝分裂检测方法，旨在利用大量未标记的乳腺癌WSI。因此，我们的方法利用越来越多的数字化组织学图像，而不依赖于详尽的注释，随后改进有丝分裂检测。我们的方法首先从标记数据中学习有丝分裂检测器，使用该检测器从未标记的WSI中挖掘额外的有丝分裂样品，然后使用这种更大和更多样的有丝分裂样品训练最终模型。与我们在TUPAC验证集上表现最佳的全监督模型相比，使用未标记数据可将F1得分提高$ \ sim $ 5 \％。我们对TUPAC挑战的提交（单一模式）在排行榜上排名很高，得分为0.64。

##### URL
[http://arxiv.org/abs/1807.11677](http://arxiv.org/abs/1807.11677)

##### PDF
[http://arxiv.org/pdf/1807.11677](http://arxiv.org/pdf/1807.11677)

