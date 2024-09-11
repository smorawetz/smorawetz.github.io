---
title: "U(1)-symmetric recurrent neural networks for quantum state reconstruction"
collection: publications
category: manuscripts
permalink: /publication/u1-nn-reconstruction-2021
excerpt: 'In this work, we propose a novel recurrent neural network ansatz which respects the U(1) symmetry of an underlying Hamiltonian, significantly improving the performance of neural network quantum state reconstruction.'
date: 2021-07-01
venue: 'Physical Review A'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://smorawetz.github.io/files/PhysRevA.104.012401.pdf'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Generative models are a promising technology for the enhancement of quantum simulators. These machine learning methods are capable of reconstructing a quantum state from experimental measurements, and can aid in the calculation of physical observables. In this paper, we employ a recurrent neural network (RNN) to reconstruct the ground state of the spin-1/2 XY model, a prototypical Hamiltonian explored in trapped ion simulators. We explore its performance after enforcing a U(1) symmetry, which was recently shown by Hibat-Allah et al. [Phys. Rev. Res. 2, 023358 (2020)] to preserve the autoregressive nature of the RNN. By studying the reconstruction of the XY model ground state from projective measurement data, we show that imposing U(1) symmetry on the RNN significantly increases the efficiency of learning, particularly in the early epoch regime. We argue that this performance increase may result from the tendency of the enforced symmetry to alleviate vanishing and exploding gradients, which helps stabilize the training process. Thus, symmetry-enforced RNNs may be particularly useful for applications of quantum simulators where a rapid feedback between optimization and circuit preparation is necessary, such as in hybrid classical-quantum algorithms.