---
title: "Memory Management for Concurrent Data Structures on Hardware Transactional Memory"
collection: publications
permalink: /publication/2017-MemoryManagement
excerpt: 'In this paper, we revisit epochs, another popular memory management technique, and offer an interpretation for HTM systems. HTM helps avoid a common problem of quiescent techniques where delayed or failed threads prevent memory reclamation. In transactional mode, HTM allows threads to interrupt other delayed threads that prevent progress otherwise. This paper describes the design and implementation of this technique and discusses trade-offs compared to other techniques. Experiments were conducted on Intel Haswell and Power8 architectures. The described technique is competitive with other HTM based techniques. Our results also demonstrate that under many scenarios, HTM based algorithms can be as fast as other optimized algorithms.'
date: 2017-02-05
venue: 'Transact 2017'
paperurl: 'http://rmmilewi.github.io/files/memorymanagement17.pdf'
citation: 'Peter Pirkelbauer, Amalee Wilson, Hadia Ahmed, and Reed Milewicz. Memory Management for Concurrent Data Structures on Hardware Transactional Memory. In Transact 2017, workshop at PPoPP17, 2017.'
---
Similar to fine-grained locking, and lock-free programming, memory management poses challenges to programming systems with hardware transactional memory (HTM). Thus, scalable data structures need to integrate a memory management scheme, such as hazard pointers, repeated offender, reference counting, and Stacktrack.

In this paper, we revisit epochs, another popular memory management technique, and offer an interpretation for HTM systems. HTM helps avoid a common problem of quiescent techniques where delayed or failed threads prevent memory reclamation. In transactional mode, HTM allows threads to interrupt other delayed threads that prevent progress otherwise. This paper describes the design and implementation of this technique and discusses trade-offs compared to other techniques. Experiments were conducted on Intel Haswell and Power8 architectures. The described technique is competitive with other HTM based techniques. Our results also demonstrate that under many scenarios, HTM based algorithms can be as fast as other optimized algorithms.

[Download paper here](http://rmmilewi.github.io/files/memorymanagement17.pdf)

Recommended citation: Peter Pirkelbauer, Amalee Wilson, Hadia Ahmed, and Reed Milewicz. Memory Management for Concurrent Data Structures on Hardware Transactional Memory. In Transact 2017, workshop at PPoPP17, 2017.