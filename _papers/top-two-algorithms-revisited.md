---
title: Top Two Algorithms Revisited
research_id: item-05
authors: Marc Jourdan, Rémy Degenne, Dorian Baudry, Rianne de Heide and Emilie Kaufmann
publication_date: '2022'
about: This paper gives a general analysis of Top Two algorithms for fixed-confidence best-arm identification. It identifies what is required of the leader, challenger and arm distributions, extending theoretical guarantees beyond the Gaussian settings for which they were previously known.
abstract: Top Two algorithms arose as an adaptation of Thompson sampling to best-arm identification in multi-armed bandit models. They select the next arm by randomizing among two candidates, a leader and a challenger. Despite strong empirical performance, fixed-confidence guarantees had mainly been available for Gaussian arms with known variances. We provide a general analysis of Top Two methods, identifying useful properties of the leader, challenger and possibly non-parametric arm distributions. This yields theoretically supported Top Two algorithms for best-arm identification with bounded distributions. The proof method also shows that the Thompson-sampling step used to select the leader can be replaced by other choices, such as selecting the empirical best arm.
abstract_heading: Summary
---
