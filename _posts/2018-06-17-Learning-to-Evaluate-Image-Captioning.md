---
layout: post
title: "Learning to Evaluate Image Captioning"
date: 2018-06-17 17:57:32
categories: arXiv_CV
tags: arXiv_CV Image_Caption Face Caption Relation
author: Yin Cui, Guandao Yang, Andreas Veit, Xun Huang, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Evaluation metrics for image captioning face two challenges. Firstly, commonly used metrics such as CIDEr, METEOR, ROUGE and BLEU often do not correlate well with human judgments. Secondly, each metric has well known blind spots to pathological caption constructions, and rule-based metrics lack provisions to repair such blind spots once identified. For example, the newly proposed SPICE correlates well with human judgments, but fails to capture the syntactic structure of a sentence. To address these two challenges, we propose a novel learning based discriminative evaluation metric that is directly trained to distinguish between human and machine-generated captions. In addition, we further propose a data augmentation scheme to explicitly incorporate pathological transformations as negative examples during training. The proposed metric is evaluated with three kinds of robustness tests and its correlation with human judgments. Extensive experiments show that the proposed data augmentation scheme not only makes our metric more robust toward several pathological transformations, but also improves its correlation with human judgments. Our metric outperforms other metrics on both caption level human correlation in Flickr 8k and system level human correlation in COCO. The proposed approach could be served as a learning based evaluation metric that is complementary to existing rule-based metrics.

##### Abstract (translated by Google)
图像字幕的评估指标面临两个挑战。首先，常用的指标如CIDEr，METEOR，ROUGE和BLEU通常与人的判断不相关。其次，每个度量标准对病理字幕构造都有着众所周知的盲点，而基于规则的度量标准一旦被识别就缺乏修复这些盲点的规定。例如，新提出的SPICE与人类判断相关性很​​好，但未能捕捉句子的句法结构。为了解决这两个挑战，我们提出了一种新颖的基于学习的判别式评估度量，它直接被训练来区分人类和机器生成的字幕。此外，我们进一步提出了一个数据增强方案，以明确纳入病理变换作为培训期间的负面例子。所提出的度量用三种鲁棒性测试及其与人类判断的相关性进行评估。大量实验表明，所提出的数据增强方案不仅使我们的度量对于几种病态转换更加稳健，而且还提高了它与人类判断的相关性。我们的指标优于其他指标，如Flickr 8k中的字幕级人类相关性和COCO中的系统级人类相关性。提出的方法可以作为基于学习的评估指标，与现有的基于规则的指标相辅相成。

##### URL
[http://arxiv.org/abs/1806.06422](http://arxiv.org/abs/1806.06422)

##### PDF
[http://arxiv.org/pdf/1806.06422](http://arxiv.org/pdf/1806.06422)

