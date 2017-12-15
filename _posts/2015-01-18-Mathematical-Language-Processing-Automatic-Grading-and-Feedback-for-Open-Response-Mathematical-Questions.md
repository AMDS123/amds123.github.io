---
layout: post
title: "Mathematical Language Processing: Automatic Grading and Feedback for Open Response Mathematical Questions"
date: 2015-01-18 20:50:39
categories: arXiv_CL
tags: arXiv_CL
author: Andrew S. Lan, Divyanshu Vats, Andrew E. Waters, Richard G. Baraniuk
mathjax: true
---

* content
{:toc}

##### Abstract
While computer and communication technologies have provided effective means to scale up many aspects of education, the submission and grading of assessments such as homework assignments and tests remains a weak link. In this paper, we study the problem of automatically grading the kinds of open response mathematical questions that figure prominently in STEM (science, technology, engineering, and mathematics) courses. Our data-driven framework for mathematical language processing (MLP) leverages solution data from a large number of learners to evaluate the correctness of their solutions, assign partial-credit scores, and provide feedback to each learner on the likely locations of any errors. MLP takes inspiration from the success of natural language processing for text data and comprises three main steps. First, we convert each solution to an open response mathematical question into a series of numerical features. Second, we cluster the features from several solutions to uncover the structures of correct, partially correct, and incorrect solutions. We develop two different clustering approaches, one that leverages generic clustering algorithms and one based on Bayesian nonparametrics. Third, we automatically grade the remaining (potentially large number of) solutions based on their assigned cluster and one instructor-provided grade per cluster. As a bonus, we can track the cluster assignment of each step of a multistep solution and determine when it departs from a cluster of correct solutions, which enables us to indicate the likely locations of errors to learners. We test and validate MLP on real-world MOOC data to demonstrate how it can substantially reduce the human effort required in large-scale educational platforms.

##### Abstract (translated by Google)
计算机和通信技术为教育的多方面提供了有效的手段，而作业分配和测试等评估的提交和分级仍然是一个薄弱环节。本文研究STEM（科学，技术，工程，数学）课程中突出反映数学问题的自动评分问题。我们数据驱动的数学语言处理（MLP）框​​架利用了大量学习者的解决方案数据来评估其解决方案的正确性，分配部分学分，并向每个学习者提供有关任何错误可能位置的反馈。 MLP从文本数据的自然语言处理的成功中获得灵感，包括三个主要步骤。首先，我们将每个解决方案转换为一个开放的响应数学问题，形成一系列的数字特征。其次，我们将来自几个解决方案的特征进行聚类，以揭示正确的，部分正确的和不正确的解决方案的结构。我们开发了两种不同的聚类方法，一种是利用泛型聚类算法，另一种是基于贝叶斯非参数的聚类方法。第三，我们根据自己分配的集群和每个集群提供的一个教师提供的等级自动为剩下的（可能是大量的）解决方案评分。作为奖励，我们可以跟踪多步解决方案每一步的聚类分配，并确定何时离开一组正确的解决方案，这使我们能够向学习者指出错误的可能位置。我们在实际的MOOC数据上测试和验证MLP，以展示如何大幅减少大规模教育平台所需的人力成本。

##### URL
[https://arxiv.org/abs/1501.04346](https://arxiv.org/abs/1501.04346)

##### PDF
[https://arxiv.org/pdf/1501.04346](https://arxiv.org/pdf/1501.04346)

