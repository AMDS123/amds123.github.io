---
layout: post
title: "TIFTI: A Framework for Extracting Drug Intervals from Longitudinal Clinic Notes"
date: 2018-11-30 13:50:15
categories: arXiv_CL
tags: arXiv_CL
author: Monica Agrawal, Griffin Adams, Nathan Nussbaum, Ben Birnbaum
mathjax: true
---

* content
{:toc}

##### Abstract
Oral drugs are becoming increasingly common in oncology care. In contrast to intravenous chemotherapy, which is administered in the clinic and carefully tracked via structure electronic health records (EHRs), oral drug treatment is self-administered and therefore not tracked as well. Often, the details of oral cancer treatment occur only in unstructured clinic notes. Extracting this information is critical to understanding a patient's treatment history. Yet, this a challenging task because treatment intervals must be inferred longitudinally from both explicit mentions in the text as well as from document timestamps. In this work, we present TIFTI (Temporally Integrated Framework for Treatment Intervals), a robust framework for extracting oral drug treatment intervals from a patient's unstructured notes. TIFTI leverages distinct sources of temporal information by breaking the problem down into two separate subtasks: document-level sequence labeling and date extraction. On a labeled dataset of metastatic renal-cell carcinoma (RCC) patients, it exactly matched the labeled start date in 46% of the examples (86% of the examples within 30 days), and it exactly matched the labeled end date in 52% of the examples (78% of the examples within 30 days). Without retraining, the model achieved a similar level of performance on a labeled dataset of advanced non-small-cell lung cancer (NSCLC) patients.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12793](http://arxiv.org/abs/1811.12793)

##### PDF
[http://arxiv.org/pdf/1811.12793](http://arxiv.org/pdf/1811.12793)

