---
layout: post
title: "Reinforcement Learning for Automatic Test Case Prioritization and Selection in Continuous Integration"
date: 2018-11-09 20:08:58
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Helge Spieker, Arnaud Gotlieb, Dusica Marijan, Morten Mossige
mathjax: true
---

* content
{:toc}

##### Abstract
Testing in Continuous Integration (CI) involves test case prioritization, selection, and execution at each cycle. Selecting the most promising test cases to detect bugs is hard if there are uncertainties on the impact of committed code changes or, if traceability links between code and tests are not available. This paper introduces Retecs, a new method for automatically learning test case selection and prioritization in CI with the goal to minimize the round-trip time between code commits and developer feedback on failed test cases. The Retecs method uses reinforcement learning to select and prioritize test cases according to their duration, previous last execution and failure history. In a constantly changing environment, where new test cases are created and obsolete test cases are deleted, the Retecs method learns to prioritize error-prone test cases higher under guidance of a reward function and by observing previous CI cycles. By applying Retecs on data extracted from three industrial case studies, we show for the first time that reinforcement learning enables fruitful automatic adaptive test case selection and prioritization in CI and regression testing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04122](http://arxiv.org/abs/1811.04122)

##### PDF
[http://arxiv.org/pdf/1811.04122](http://arxiv.org/pdf/1811.04122)

