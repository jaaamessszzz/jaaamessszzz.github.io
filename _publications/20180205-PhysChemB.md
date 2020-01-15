---
title: "Flex ddG: Rosetta Ensemble-Based Estimation of Changes in Protein–Protein Binding Affinity upon Mutation"
collection: publications
permalink: /publication/20180205-PhysChemB
excerpt: 'Improving our ability to calculate protein-protein interface DDGs upon mutation'
date: 2018-02-05
venue: 'The Journal of Physical Chemistry B'
paperurl: 'https://pubs.acs.org/doi/abs/10.1021/acs.jpcb.7b11367'
citation: 'Barlow KA, Ó Conchúir S, Thompson S, Suresh P, Lucas JE, Heinonen M, Kortemme T. Flex ddG: Rosetta 
Ensemble-Based Estimation of Changes in Protein-Protein Binding Affinity upon Mutation. J Phys Chem B. 2018 
doi: 10.1021/acs.jpcb.7b11367. '
---
Computationally modeling changes in binding free energies upon mutation (interface ΔΔG) allows large-scale prediction 
and perturbation of protein–protein interactions. Additionally, methods that consider and sample relevant conformational 
plasticity should be able to achieve higher prediction accuracy over methods that do not. To test this hypothesis, we 
developed a method within the Rosetta macromolecular modeling suite (flex ddG) that samples conformational diversity 
using “backrub” to generate an ensemble of models and then applies torsion minimization, side chain repacking, and 
averaging across this ensemble to estimate interface ΔΔG values. We tested our method on a curated benchmark set of 
1240 mutants, and found the method outperformed existing methods that sampled conformational space to a lesser degree. 
We observed considerable improvements with flex ddG over existing methods on the subset of small side chain to large 
side chain mutations, as well as for multiple simultaneous non-alanine mutations, stabilizing mutations, and mutations 
in antibody–antigen interfaces. Finally, we applied a generalized additive model (GAM) approach to the Rosetta energy 
function; the resulting nonlinear reweighting model improved the agreement with experimentally determined interface ΔΔG 
values but also highlighted the necessity of future energy function improvements.