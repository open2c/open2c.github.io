# Welcome to the Open Chromosome Collective!

We are a group of computational biologists working chromosomes and interested in developing the tools, both for ourselves and for the wider community.

We are particularly interested in the 3D organization of chromosomes, and most of the tools are focused on the analysis of data obtained using Hi-C and related technologies. We like our tools to be easy to use, flexible to facilitate active developemnt of novel analytical approaches, and scalable.

For analysis of Hi-C (and related) data, we have a suite of tools:
 - [pairtools](https://www.github.com/mirnylab/pairtools) for analysis and filtering of mapped reads
 - [cooler](https://www.github.com/mirnylab/cooler) for generation, normalizatio and storage of interaction matrices
 - [distiller](https://www.github.com/mirnylab/distiller-nf) - a Nextflow pipeline for automation of Hi-C data processing, from reads to Cooler files
 - [cooltools](https://www.github.com/mirnylab/cooltools) for analysis of Hi-C data, including, but not limited to, compartment, insulation and peak calling
 - [coolpup.py](https://www.github.com/open2c/coolpuppy) for flexible pileup analysis
 - [quaich](https://www.github.com/open2c/quaich) - a Snakemake pipeline for automated Hi-C postprocessing using **cooltools** and **coolpup.py**
 
 Additionally,
  - [bioframe](https://www.github.com/mirnylab/bioframe) provides a framework for genomic data analysis using Pandas DataFrames, invluding genomic interval arithmetic
  - [polychrom](https://www.github.com/mirnylab/polychrom) simplifies polymer simulations for *in silico* experiments with chromosomes

Please interact with us on GitHub (we are open!), or join our [Slack](https://bit.ly/2UaOpAe) for more interactive discussions.
