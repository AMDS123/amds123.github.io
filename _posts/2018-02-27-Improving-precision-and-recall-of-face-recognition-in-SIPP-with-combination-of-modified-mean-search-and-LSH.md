---
layout: post
title: "Improving precision and recall of face recognition in SIPP with combination of modified mean search and LSH"
date: 2018-02-27 16:33:02
categories: arXiv_CV
tags: arXiv_CV Face Recognition Face_Recognition
author: Xihua Li
mathjax: true
---

* content
{:toc}

##### Abstract
Although face recognition has been improved much as the development of Deep Neural Networks, SIPP(Single Image Per Person) problem in face recognition has not been better solved, especially in practical applications where searching over complicated database. In this paper, a combination of modified mean search and LSH method would be introduced orderly to improve the precision and recall of SIPP face recognition without retrain of the DNN model. First, a modified SVD based augmentation method would be introduced to get more intra-class variations even for person with only one image. Second, an unique rule based combination of modified mean search and LSH method was proposed the first time to help get the most similar personID in a complicated dataset, and some theoretical explaining followed. Third, we would like to emphasize, no need to retrain of the DNN model and would easy to be extended without much efforts. We do some practical testing in competition of Msceleb challenge-2 2017 which was hold by Microsoft Research, great improvement of coverage from 13.39% to 19.25%, 29.94%, 42.11%, 47.52% at precision 99%(P99) would be shown latter, coverage reach 94.2% and 100% at precision 97%(P97) and 95%(P95) respectively. As far as we known, this is the only paper who do not fine-tuning on competition dataset and ranked top-10. A similar test on CASIA WebFace dataset also demonstrated the same improvements on both precision and recall.

##### Abstract (translated by Google)
尽管随着深度神经网络的发展，人脸识别得到了很大改善，但人脸识别中的SIPP（Single Image Per Person）问题并没有得到较好的解决，特别是在复杂数据库搜索的实际应用中。本文将有序引入改进的均值搜索和LSH方法的组合，以提高SIPP人脸识别的精度和查全率，而无需重新训练DNN模型。首先，将引入修改的基于SVD的增强方法来获得更多的类内变体，即使对于只有一个图像的人也是如此。其次，首次提出了一种独特的基于修正均值搜索和LSH方法的规则组合方法，以帮助获取复杂数据集中最相似的personID，并进行了一些理论解释。第三，我们想强调的是，不需要重新培训DNN模型，并且很容易就可以毫不费力地进行扩展。我们在微软研究院举办的Msceleb challenge-2 2017竞赛中进行了一些实际测试，覆盖率从13.39％到19.25％，29.94％，42.11％，47.52％的精确度提高了99％（P99）覆盖率分别达到94.2％和100％，精度分别为97％（P97）和95％（P95）。据我们所知，这是唯一没有对竞赛数据集进行微调并排名前10位的论文。对CASIA WebFace数据集进行的类似测试也证明了精确度和召回率方面的改进。

##### URL
[http://arxiv.org/abs/1709.03872](http://arxiv.org/abs/1709.03872)

##### PDF
[http://arxiv.org/pdf/1709.03872](http://arxiv.org/pdf/1709.03872)

