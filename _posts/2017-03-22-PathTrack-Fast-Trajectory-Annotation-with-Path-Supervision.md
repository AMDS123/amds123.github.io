---
layout: post
title: "PathTrack: Fast Trajectory Annotation with Path Supervision"
date: 2017-03-22 07:08:34
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Classification Recognition
author: Santiago Manen, Michael Gygli, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Progress in Multiple Object Tracking (MOT) has been historically limited by the size of the available datasets. We present an efficient framework to annotate trajectories and use it to produce a MOT dataset of unprecedented size. In our novel path supervision the annotator loosely follows the object with the cursor while watching the video, providing a path annotation for each object in the sequence. Our approach is able to turn such weak annotations into dense box trajectories. Our experiments on existing datasets prove that our framework produces more accurate annotations than the state of the art, in a fraction of the time. We further validate our approach by crowdsourcing the PathTrack dataset, with more than 15,000 person trajectories in 720 sequences. Tracking approaches can benefit training on such large-scale datasets, as did object recognition. We prove this by re-training an off-the-shelf person matching network, originally trained on the MOT15 dataset, almost halving the misclassification rate. Additionally, training on our data consistently improves tracking results, both on our dataset and on MOT15. On the latter, we improve the top-performing tracker (NOMT) dropping the number of IDSwitches by 18% and fragments by 5%.

##### Abstract (translated by Google)
多目标跟踪（MOT）的进展历来受可用数据集大小的限制。我们提出了一个有效的框架来注释轨迹，并用它来产生一个空前大小的MOT数据集。在我们新颖的路径监视中，注释者在观看视频时用光标宽松地跟随对象，为序列中的每个对象提供路径注释。我们的方法能够将这种弱注释转变成密集的盒子轨迹。我们对现有数据集进行的实验证明，我们的框架能够在一小部分时间内产生比现有技术更精确的注释。我们通过众包PathTrack数据集进一步验证了我们的方法，在720个序列中有超过15000个人的轨迹。跟踪方法可以使这类大规模数据集的训练受益，对象识别也是如此。我们通过重新培训一个原来在MOT15数据集上进行训练的现成的人员匹配网络来证明这一点，差错分类几乎减半。此外，对我们的数据进行培训可以持续改善我们的数据集和MOT15上的跟踪结果。在后者中，我们改进了性能最佳的跟踪器（NOMT），IDSwitch的数量减少了18％，碎片减少了5％。

##### URL
[https://arxiv.org/abs/1703.02437](https://arxiv.org/abs/1703.02437)

##### PDF
[https://arxiv.org/pdf/1703.02437](https://arxiv.org/pdf/1703.02437)

