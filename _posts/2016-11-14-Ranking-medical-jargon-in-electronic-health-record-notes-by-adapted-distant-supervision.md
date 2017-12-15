---
layout: post
title: "Ranking medical jargon in electronic health record notes by adapted distant supervision"
date: 2016-11-14 17:36:05
categories: arXiv_CL
tags: arXiv_CL Knowledge Recognition
author: Jinying Chen, Abhyuday N. Jagannatha, Samah J. Jarad, Hong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Allowing patients to access their own electronic health record (EHR) notes through online patient portals has the potential to improve patient-centered care. However, medical jargon, which abounds in EHR notes, has been shown to be a barrier for patient EHR comprehension. Existing knowledge bases that link medical jargon to lay terms or definitions play an important role in alleviating this problem but have low coverage of medical jargon in EHRs. We developed a data-driven approach that mines EHRs to identify and rank medical jargon based on its importance to patients, to support the building of EHR-centric lay language resources. Methods: We developed an innovative adapted distant supervision (ADS) model based on support vector machines to rank medical jargon from EHRs. For distant supervision, we utilized the open-access, collaborative consumer health vocabulary, a large, publicly available resource that links lay terms to medical jargon. We explored both knowledge-based features from the Unified Medical Language System and distributed word representations learned from unlabeled large corpora. We evaluated the ADS model using physician-identified important medical terms. Results: Our ADS model significantly surpassed two state-of-the-art automatic term recognition methods, TF*IDF and C-Value, yielding 0.810 ROC-AUC versus 0.710 and 0.667, respectively. Our model identified 10K important medical jargon terms after ranking over 100K candidate terms mined from over 7,500 EHR narratives. Conclusion: Our work is an important step towards enriching lexical resources that link medical jargon to lay terms/definitions to support patient EHR comprehension. The identified medical jargon terms and their rankings are available upon request.

##### Abstract (translated by Google)
目标：允许患者通过在线病人门户访问他们自己的电子健康记录（EHR）笔记有可能改善以患者为中心的护理。然而，EHR记录中的医学术语已被证明是患者EHR理解的障碍。现有的将医学专业术语联系起来的知识基础对于缓解这个问题起到了重要的作用，但是在电子健康档案中对医学术语的覆盖率较低。我们开发了一种数据驱动的方法，根据对病人的重要性挖掘电子健康档案，以识别和排列医学术语，以支持建立以电子病历为中心的俗语语言资源。方法：我们开发了一种基于支持向量机的创新适配远程监督（ADS）模型，对电子健康档案中的医学术语进行排序。对于遥远的监督，我们利用开放获取，协作的消费者健康词汇，一个大型的公开可用的资源，链接术语与医学术语。我们探索了统一医学语言系统中的基于知识的特征和从无标签的大语料库中学习的分布式词汇表征。我们使用医师确定的重要医学术语评估了ADS模型。结果：我们的ADS模型显着超过了两种最先进的自动术语识别方法，TF * IDF和C-Value，分别产生0.810 ROC-AUC和0.710和0.667。我们的模型从超过7500条EHR叙述中挖掘了超过10万个候选词汇，并确定了10K个重要的医学术语。结论：我们的工作是丰富词汇资源的一个重要步骤，将医学专业术语与术语/定义联系起来，以支持患者EHR的理解。医疗专业术语及其排名可根据要求提供。

##### URL
[https://arxiv.org/abs/1611.04491](https://arxiv.org/abs/1611.04491)

##### PDF
[https://arxiv.org/pdf/1611.04491](https://arxiv.org/pdf/1611.04491)

