---
layout: post
title: "DeepTag: inferring all-cause diagnoses from clinical notes in under-resourced medical domain"
date: 2018-06-28 00:45:04
categories: arXiv_CL
tags: arXiv_CL RNN Deep_Learning
author: Allen Nie, Ashley Zehnder, Rodney L. Page, Arturo L. Pineda, Manuel A. Rivas, Carlos D. Bustamante, James Zou
mathjax: true
---

* content
{:toc}

##### Abstract
In many under-resourced settings, clinicians lack time and expertise to annotate patients with standard medical diagnosis codes. Veterinary medicine is an example of this and clinical encounters are largely captured in free text notes which are not labeled with diagnosis code. The lack of such standard coding makes it challenging to apply data science to improve patient care. It is also a major impediment to translational research, where, for example, we would like to leverage veterinary data to inform drug development for humans. We develop a deep learning algorithm, DeepTag, to automatically infer diagnosis codes from veterinarian free text notes. DeepTag is trained on a newly curated dataset of 112,558 veterinary notes manually annotated by experts. DeepTag extends multi-task LSTM with an improved hierarchical objective that captures structures between diseases. To foster human-machine collaboration, DeepTag also learns to abstain in examples when it is uncertain and defer them to human experts, resulting in improved performance of the model. DeepTag accurately infers disease codes from free text even in challenging out-of-domain settings where the text comes from different clinics than the ones used for training. It enables automated disease annotation across a broad range of clinical diagnoses with minimal pre-processing. The technical framework in this work can be applied in other medical domains that currently lack medical coding infrastructure.

##### Abstract (translated by Google)
在许多资源贫乏的地区，临床医生缺乏时间和专业知识来为患者提供标准的医疗诊断代码。兽医学就是这方面的一个例子，临床相遇大部分都是在自由文本笔记中记录的，没有用诊断代码标记。缺乏这样的标准编码使得应用数据科学改善患者护理具有挑战性。这也是转化研究的主要障碍，例如，我们希望利用兽医数据为人类的药物开发提供信息。我们开发了深度学习算法DeepTag，从兽医自由文本笔记自动推断诊断代码。 DeepTag接受了由专家手动注释的112,558份兽医笔记的新策划数据集的培训。 DeepTag利用改进的分层目标扩展了多任务LSTM，捕获疾病之间的结构。为了促进人机协作，DeepTag还学习在不确定的例子中弃权，并将其推迟给人类专家，从而提高模型的性能。 DeepTag可以从自由文本中准确推断疾病代码，即使在挑战域外设置时，文本来自不同的诊所，而不是用于培训的文本。它能够通过最少的预处理在广泛的临床诊断中实现自动疾病注释。这项工作的技术框架可以应用于目前缺乏医疗编码基础设施的其他医疗领域。

##### URL
[http://arxiv.org/abs/1806.10722](http://arxiv.org/abs/1806.10722)

##### PDF
[http://arxiv.org/pdf/1806.10722](http://arxiv.org/pdf/1806.10722)

