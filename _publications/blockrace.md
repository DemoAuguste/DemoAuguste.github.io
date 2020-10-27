---
title: "BlockRace: A Big Data Approach to Dynamic Block-based Data Race Detection for Multithreaded Programs"
collection: publications
permalink: /publication/apricot
excerpt:
date: 2020-10-01
venue: '2020 ACM/IEEE International Conference on Automation of Software Test (AST)'
paperurl: 'https://doi.org/10.1145/3387903.3389311'
citation: 'X. Mei, Z. Wei, H. Zhang, and W.K. Chan, “BlockRace: A Big Data Approach to Dynamic Block-based Data Race Detection for Multithreaded Programs,” In Proceedings of ACM/IEEE International Conference on Automation of Software Test (AST), 2020, pp. 71-80.'
---
**Abstract** - The advent of multicore systems and distributed frameworks enables distributed strategies to address challenges in large-scale divisible problems by decomposing them into small ones, processing the corresponding sub-solutions and aggregating these sub-solutions into the final result. However, dynamic online detection of data races in execution traces of multithreaded programs is challenging to be parallelized due to their inherent historic event sensitivity and incremental inference of happens-before transitive closure To examine the extent of such detection to be transformed into parallel versions, in this paper, we present BlockRace, a novel dynamic block-based data race detection technique, which precisely detects data races in such traces and checks pairs of events blocks in parallel using its novel strategy. We evaluate BlockRace on 18 programs, and the results show that BlockRace achieves 1.96x to 5.5x speedups compared to its sequential counterparts. To the best of our knowledge, BlockRace is the first technique to detect races in block parrs where these block pairs can be run in parallel on Big Data frameworks.

[Download paper here](https://doi.org/10.1145/3387903.3389311)

