---
title: "BlockRace: A Big Data Approach to Dynamic Block-based Data Race Detection for Multithreaded Programs"
collection: publications
permalink: /publication/regiontrack
excerpt:
date: 2020-10-01
venue: 'ACM Transactions on Software Engineering and Methodology (TOSEM), accepted'
paperurl: 'https://doi.org/10.1145/3387903.3389311'
citation: 'X. Mei, Z. Wei, H. Zhang, and W.K. Chan, “BlockRace: A Big Data Approach to Dynamic Block-based Data Race Detection for Multithreaded Programs,” In Proceedings of ACM/IEEE International Conference on Automation of Software Test (AST), 2020, pp. 71-80.'
---
**Abstract** - Atomicity is a correctness criterion to reason about isolated code regions in a multithreaded program when they are executed concurrently. However, dynamic instances of these code regions, called transactions, may fail to behave atomically, resulting in transactional atomicity violations. Existing dynamic online atomicity checkers incur either false positives or false negatives in detecting transactions experiencing transactional atomicity violations. This paper proposes RegionTrack. RegionTrack tracks cross-thread dependences at the event, dynamic subregion, and transaction levels. It maintains both dynamic subregions within selected transactions and transactional happens-before relations through its novel timestamp propagation approach. We prove that RegionTrack is sound and complete in detecting both transactional atomicity violations and non-serializable traces. To the best of our knowledge, it is the first online technique that precisely captures the transitively closed set of happens-before relations over all conflicting events with respect to every running transaction for the above two kinds of issues. We have evaluated RegionTrack on 19 subjects of the DaCapo and the Java Grande Forum benchmarks. The empirical results confirm that RegionTrack precisely detected all those transactions which experienced transactional atomicity violations and identified all non-serializable traces. The overall results also show that RegionTrack incurred 1.10x and 1.08x lower memory and runtime overheads than Velodrome and 2.10x and 1.21x lower than Aerodrome, respectively. Moreover, it incurred 2.89x lower memory overhead than DoubleChecker. On average, Velodrome detected about 55% fewer violations than RegionTrack, which in turn reported about 3%-70% fewer violations than DoubleChecker. 

[Download paper here](https://doi.org/10.1145/3387903.3389311)

