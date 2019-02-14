---
layout: post
title: "Time-aware Test Case Execution Scheduling for Cyber-Physical Systems"
date: 2019-02-12 20:39:05
categories: arXiv_AI
tags: arXiv_AI
author: Morten Mossige, Arnaud Gotlieb, Helge Spieker, Hein Meling, Mats Carlsson
mathjax: true
---

* content
{:toc}

##### Abstract
Testing cyber-physical systems involves the execution of test cases on target-machines equipped with the latest release of a software control system. When testing industrial robots, it is common that the target machines need to share some common resources, e.g., costly hardware devices, and so there is a need to schedule test case execution on the target machines, accounting for these shared resources. With a large number of such tests executed on a regular basis, this scheduling becomes difficult to manage manually. In fact, with manual test execution planning and scheduling, some robots may remain unoccupied for long periods of time and some test cases may not be executed. This paper introduces TC-Sched, a time-aware method for automated test case execution scheduling. TC-Sched uses Constraint Programming to schedule tests to run on multiple machines constrained by the tests' access to shared resources, such as measurement or networking devices. The CP model is written in SICStus Prolog and uses the Cumulatives global constraint. Given a set of test cases, a set of machines, and a set of shared resources, TC-Sched produces an execution schedule where each test is executed once with minimal time between when a source code change is committed and the test results are reported to the developer. Experiments reveal that TC-Sched can schedule 500 test cases over 100 machines in less than 4 minutes for 99.5% of the instances. In addition, TC-Sched largely outperforms simpler methods based on a greedy algorithm and is suitable for deployment on industrial robot testing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04627](http://arxiv.org/abs/1902.04627)

##### PDF
[http://arxiv.org/pdf/1902.04627](http://arxiv.org/pdf/1902.04627)

