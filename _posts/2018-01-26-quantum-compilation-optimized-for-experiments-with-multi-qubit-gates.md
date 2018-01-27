---
layout: szhang_note
title: Quantum compilation optimized for experiments with multi-qubit gates
category: notes
math: true
code: true
---

## Abstract

There is increasing interest in implementing quantum algorithms with simpler and shorter experimental operations for building universal quantum computers. Here, we present a general quantum computation compiler, which maps arbitrary quantum algorithm to an optimal quantum circuit consisting a sequential set of universal gates which is feasible to operate directly in experiment with atomic qubits by lasers. We implement several methods, including matrix elementary decomposition, cosine-sine decomposition, quantum Shannon decomposition and Cartan’s KAK decomposition, to transform the quantum algorithm into a series of one-bit gates and specific two-bit or multi-bit gates. The compiler optimizes experimental gate sequence by heuristically applying mirroring and merging tricks. Moreover, we use algebraic decomposition and numerical searching method to compile unitaries using native multi-bit gates, i.e., Ising gates, which significantly reduce gate numbers. The compilation technique is practically favorable and will be used in our following trapped ions experiment.