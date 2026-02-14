---
title: "Neural Annealing and Visualization of Autoregressive Neural Networks in the Newman–Moore Model"
collection: publications
category: manuscripts
permalink: /publication/newman-moore-2025
excerpt: 'We explore the connection between the glassy and frustrated dynamics of the Newman-Moore model and difficulty in training an neural network to capture the ground state(s).'
date: 2022-05-26
venue: 'Condensed Matter'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://smorawetz.github.io/files/condensedmatter-07-00038.pdf'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Artificial neural networks have been widely adopted as ansatzes to study classical and quantum systems. However, for some notably hard systems, such as those exhibiting glassiness and frustration, they have mainly achieved unsatisfactory results, despite their representational power and entanglement content, thus suggesting a potential conservation of computational complexity in the learning process. We explore this possibility by implementing the neural annealing method with autoregressive neural networks on a model that exhibits glassy and fractal dynamics: the two-dimensional Newman–Moore model on a triangular lattice. We find that the annealing dynamics is globally unstable because of highly chaotic loss landscapes. Furthermore, even when the correct ground-state energy is found, the neural network generally cannot find degenerate ground-state configurations due to mode collapse. These findings indicate that the glassy dynamics exhibited by the Newman–Moore model caused by the presence of fracton excitations in the configurational space likely manifests itself through trainability issues and mode collapse in the optimization landscape.