## Companinon Repository for "Self-Assembly of  a Dimer System"
Paper Link https://arxiv.org/pdf/1909.00455.pdf 

## Notebook viewing links: 
**Degeneracy Factor Calculation:** https://nbviewer.jupyter.org/github/mowillia/dimer_self_assembly_code/blob/master/degen_factors_self_assembly.ipynb

**Biophysics Calculations:** https://nbviewer.jupyter.org/github/mowillia/dimer_self_assembly_code/blob/master/sadimer_biophys_calc.ipynb

**Numerical Solutions to Equilibrium Equations:** https://nbviewer.jupyter.org/github/mowillia/dimer_self_assembly_code/blob/master/sadimer_num_soln_sim.ipynb

**Parameter Space Exploration:** https://nbviewer.jupyter.org/github/mowillia/dimer_self_assembly_code/blob/master/sadimer_param_space.ipynb


# Self-Assembly of a Dimer System

In the self-assembly process which drives the formation of cellular membranes, micelles, and capsids, a collection of separated subunits spontaneously binds together to form functional and more ordered structures. But we can also study self-assembly in a simpler scenario: the formation of dimers from a system of monomers.

<p align="center">
<img src = "https://user-images.githubusercontent.com/8810308/113524506-1d4d7c00-957d-11eb-96ec-ecc29e694c52.png" width = "70%">
  </p>

The above figure depicts self-assembling biomolecular dimer systems. In (a) distinct single-stranded DNA (ssDNA) strands exist in a system with their complementary strands and with other double-stranded DNA (dsDNA). In (b) transcription factors (TFs) exist in a system with their binding sites on DNA and with already bound TF-DNA dimers. Since the binding sites are embedded in the much longer strand of an entire DNA molecule, the effective DNA molecules to which the TFs bind are much less motile than the TFs. In (c) distinct protein monomers exist in a system with the heterodimers formed from them. In all systems, we consider “fully correct assembly" or “fully correct dimerization" as the state where all monomers are bound to their correct monomer or binding site.
  
The combinatorial problem at the foundation of understanding the statistical physics of such systems is 

  <p align="center">
<img src = "https://user-images.githubusercontent.com/8810308/113524568-90ef8900-957d-11eb-9ecc-87e6344ca9a0.png" width = "70%">
  </p>
  
By answering the above question, we can formulate a statistical physics model that we can then use to answer questions such as "Under what conditions do the systems defined in the first figure settle into their fully correct configurations?" This question is answered in the [associated paper](https://www.researchgate.net/publication/332567914_Self-Assembly_of_a_Dimer_System). This repository contains the notebooks that reproduce the results therein. 


## Reproducing figures and tables

The notebooks that reproduce the figures and tables in the paper are as follows

- [`temp_vs_signorm.ipynb`](https://github.com/mowillia/largeNKP/blob/main/potential_landscape.ipynb): Reproduces Figure 3; Runs in < 1 sec
- [`sadimer_param_space.ipynb`](https://github.com/mowillia/largeNKP/blob/main/total_value_vs_temperature.ipynb): Reproduces Figure 4; Runs in < 5 minutes
- [`sadimer_num_soln_sim.ipynb`](https://github.com/mowillia/largeNKP/blob/main/algorithm_comparisons.ipynb): Reproduces Figure 5; Runs in < 1 sec


## References
[1] Williams, Mobolaji. "Self-assembly of a dimer system." *Physical Review E* 99.4 (2019): 042133.[[author's copy]](https://www.researchgate.net/publication/332567914_Self-Assembly_of_a_Dimer_System)

---

If you found this repository useful in your research, please consider citing
```
@article{williams2019self,
  title={Self-assembly of a dimer system},
  author={Williams, Mobolaji},
  journal={Physical Review E},
  volume={99},
  number={4},
  pages={042133},
  year={2019},
  publisher={APS}
}
```
