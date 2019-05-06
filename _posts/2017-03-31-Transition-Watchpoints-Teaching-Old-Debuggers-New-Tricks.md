---
layout: post
title: "Transition Watchpoints: Teaching Old Debuggers New Tricks"
date: 2017-03-31 11:47:28
categories: arXiv_CV
tags: arXiv_CV
author: Kapil Arya (Northeastern University, USA), Tyler Denniston (MIT, USA), Ariel Rabkin (Cloudera, USA), Gene Cooperman (Northeastern University, USA)
mathjax: true
---

* content
{:toc}

##### Abstract
Reversible debuggers and process replay have been developed at least since 1970. This vision enables one to execute backwards in time under a debugger. Two important problems in practice are that, first, current reversible debuggers are slow when reversing over long time periods, and, second, after building one reversible debugger, it is difficult to transfer that achievement to a new programming environment. The user observes a bug when arriving at an error. Searching backwards for the corresponding fault may require many reverse steps. Ultimately, the user prefers to write an expression that will transition to false upon arriving at the fault. The solution is an expression-transition watchpoint facility based on top of snapshots and record/replay. Expression-transition watch- points are implemented as binary search through the timeline of a program execution, while using the snapshots as landmarks within that timeline. This allows for debugging of subtle bugs that appear only after minutes or more of program execution. When a bug occurs within seconds of program startup, repeated debugging sessions suffice. Reversible debugging is preferred for bugs seen only after minutes. This architecture allows for an efficient and easy-to-write snapshot-based reversibe debugger on top of a conventional debugger. The validity of this approach was tested by developing four personalities (for GDB, MATLAB, Perl, and Python), with each personality typically requiring just 100 lines of code.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.10864](https://arxiv.org/abs/1703.10864)

##### PDF
[https://arxiv.org/pdf/1703.10864](https://arxiv.org/pdf/1703.10864)

