---
layout: post
title: "Learning from Synthetic Data for Crowd Counting in the Wild"
date: 2019-03-08 06:40:50
categories: arXiv_CV
tags: arXiv_CV
author: Qi Wang, Junyu Gao, Wei Lin, Yuan Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, counting the number of people for crowd scenes is a hot topic because of its widespread applications (e.g. video surveillance, public security). It is a difficult task in the wild: changeable environment, large-range number of people cause the current methods can not work well. In addition, due to the scarce data, many methods suffer from over-fitting to a different extent. To remedy the above two problems, firstly, we develop a data collector and labeler, which can generate the synthetic crowd scenes and simultaneously annotate them without any manpower. Based on it, we build a large-scale, diverse synthetic dataset. Secondly, we propose two schemes that exploit the synthetic data to boost the performance of crowd counting in the wild: 1) pretrain a crowd counter on the synthetic data, then finetune it using the real data, which significantly prompts the model's performance on real data; 2) propose a crowd counting method via domain adaptation, which can free humans from heavy data annotations. Extensive experiments show that the first method achieves the state-of-the-art performance on four real datasets, and the second outperforms our baselines. The dataset and source code are available at https://gjy3035.github.io/GCC-CL/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03303](http://arxiv.org/abs/1903.03303)

##### PDF
[http://arxiv.org/pdf/1903.03303](http://arxiv.org/pdf/1903.03303)

