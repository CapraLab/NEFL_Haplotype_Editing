# NEFL Haplotype Editing

This repo contains the code used to calculate patient population coverage with haplotype editing as compared to mutation-targeted editing. It focuses on the NEFL window for CRISPR excision.

## Data:
1000 genomes phase 3 2019 release, which can be found [here](https://www.internationalgenome.org/data-portal/data-collection/phase-3).

## Code:
NEFL_het_combos.ipynb - Jupyter notebook that runs a greedy algorithm to select pairs of single nucleotide polymorphisms (SNPs) surrounding the NEFL gene that target the highest number of individuals in the Thousand Genomes database. This script also runs a greedy algorithm to select optimal SNPs to be paired with a single biallelic guide RNA that is held constant. Here, an optimal SNP or optimal SNP pair denotes SNPs that target the most individuals.

## Reference:
When using or referring to this code, please cite the following bioRxiv paper:
_Dua, P. H., Simon, B. M., Marley, C. B., Feliciano, C. M., Watry, H. L., Steury, D., ... & Judge, L. M. (2024). Haplotype editing with CRISPR/Cas9 as a therapeutic approach for dominant-negative missense mutations in NEFL. bioRxiv, 2024-12._
The code is most relevant to Figure 6 in the preprint.
