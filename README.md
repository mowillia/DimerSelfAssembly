# Self-Assembly of a Dimer System

In the self-assembly process which drives the formation of cellular membranes, micelles, and capsids, a collection of separated subunits spontaneously binds together to form functional and more ordered structures. Such processes have features that are more easily studied in a much simpler scenario: the ordered formation of dimers from a system of distinguishable monomers.

<p align="center">
<img src = "https://user-images.githubusercontent.com/8810308/113524506-1d4d7c00-957d-11eb-96ec-ecc29e694c52.png" width = "80%">
  </p>

The above figure depicts self-assembling biomolecular dimer systems. In (a) distinct single-stranded DNA (ssDNA) strands exist in a system with their complementary strands and with other double-stranded DNA (dsDNA). In (b) transcription factors (TFs) exist in a system with their binding sites on DNA and with already bound TF-DNA dimers. Since the binding sites are embedded in the much longer strand of an entire DNA molecule, the effective DNA molecules to which the TFs bind are much less motile than the TFs. In (c) distinct protein monomers exist in a system with the heterodimers formed from them. In all systems, we consider “fully correct assembly" or “fully correct dimerization" as the state where all monomers are bound to their correct monomer or binding site.
  
The combinatorial problem at the foundation of understanding the statistical physics of such systems is 

  <p align="center">
<img src = "https://user-images.githubusercontent.com/8810308/113524568-90ef8900-957d-11eb-9ecc-87e6344ca9a0.png" width = "70%">
  </p>
  
By answering the above question, we can formulate a statistical physics model that we can then use to answer questions such as "Under what conditions do the systems defined in the first figure settle into their fully correct configurations?" This question is answered in the [associated paper](https://arxiv.org/pdf/1909.00455.pdf). This repository contains the notebooks that reproduce the results therein. 


## Reproducing figures and tables

The notebooks that reproduce the figures and tables in the paper are as follows

- [`degen_factors_checks.ipynb`](https://nbviewer.jupyter.org/github/mowillia/DimerSelfAssembly/blob/master/degen_factors_checks.ipynb): Checks analytical degeneracy factor calculations (in particular answers the dancing couples question); Runs in < 5 secs
- [`num_soln_sim.ipynb`](https://nbviewer.jupyter.org/github/mowillia/DimerSelfAssembly/blob/master/num_soln_sim.ipynb): Reproduces Figure 4; Runs in ~ 30 minutes
- [`param_space.ipynb`](https://nbviewer.jupyter.org/github/mowillia/DimerSelfAssembly/blob/master/param_space.ipynb): Reproduces Figure 5; Runs in < 5 secs
- [`biophys_calc.ipynb`](https://nbviewer.jupyter.org/github/mowillia/DimerSelfAssembly/blob/master/biophys_calc.ipynb): Reproduces computations from Section VI of paper; Runs in < 5 secs
- [`additional_param_space.ipynb`](https://nbviewer.jupyter.org/github/mowillia/DimerSelfAssembly/blob/master/additional_param_space.ipynb): Reproduces Figure S1 in Supplementary Materials; Runs in < 5 secs

## Data files
Data sheets contained within folder `data_files`
- `protein_DNA_affinity.csv`: Binding energies between proteins and DNA. 
  - From Table 1 in: Jen‐Jacobson, Linda. "Protein—DNA recognition complexes: Conservation of structure and binding energy in the transition state." *Biopolymers: Original Research on Biomolecules* 44.2 (1997): 153-180. 
- `protein_protein_affinity.csv`: Binding energies between proteins
  - From [Affinity](https://bmm.crick.ac.uk/~bmmadmin/Affinity/) linked to in: Kastritis, Panagiotis L., et al. "A structure‐based benchmark 
for protein–protein binding affinity." *Protein Science* 20.3 (2011): 482-491


## References
[1] Williams, Mobolaji. "Self-assembly of a dimer system." *Physical Review E* 99.4 (2019): 042133.

---
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
