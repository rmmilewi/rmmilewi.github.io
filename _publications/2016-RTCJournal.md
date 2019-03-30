---
title: "Lightweight Runtime Checking of C Programs with RTC"
collection: publications
permalink: /publication/2016-RTCJournal
excerpt: 'This is a journal version of the RTC paper presented at SAC'15.'
date: 2016-
venue: 'Computer Languages, Systems and Structures'
paperurl: 'http://rmmilewi.github.io/files/sac15j.pdf'
citation: 'Reed Milewicz, Rajesh Vanka, James Tuck, Daniel Quinlan, and Peter Pirkelbauer. Lightweight runtime checking of C programs with RTC. In Computer Languages, Systems and Structures, 2016.'
---

The C Programming Language is known for being an efficient language that can be compiled on almost any architecture and operating system. However the absence of dynamic safety checks and a relatively weak type system allows programmer oversights that are hard to spot. In this paper, we present RTC, a runtime monitoring tool that instruments unsafe code and monitors the program execution. RTC is built on top of the ROSE compiler infrastructure. RTC finds memory bugs and arithmetic overflows and underflows, and run-time type violations. Most of the instrumentations are directly added to the source file and only require a minimal runtime system. As a result, the instru- mented code remains portable. In tests against known error detection benchmarks, RTC found 98% of all memory related bugs and had zero false positives. In performance tests conducted with well known algorithms, such as binary search and MD5, we determined that our tool has an average run-time overhead rate of 9.7x and memory overhead rate of 3.5x.

This is a journal version of the RTC paper presented at SAC'15.

[Download paper here](http://rmmilewi.github.io/files/sac15j.pdf)

Recommended citation: Reed Milewicz, Rajesh Vanka, James Tuck, Daniel Quinlan, and Peter Pirkelbauer. Lightweight runtime checking of C programs with RTC. In Computer Languages, Systems and Structures, 2016.