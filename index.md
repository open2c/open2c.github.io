---
---
# Welcome to Open2C!

We are a group of computational biologists working on chromosome structure and interested in developing open source tools for the wider community.

We are particularly interested in the 3D organization of chromosomes, and most of the tools are focused on the analysis of data obtained using Hi-C and related technologies. We like our tools to be easy to use, flexible, to facilitate active development of novel analytical approaches, and scalable, to make use of the latest and largest datasets.

🛠️ For analysis of Hi-C (and related) data, we have a suite of tools:

- [cooler](https://www.github.com/open2c/cooler)* for generation, normalization and storage of interaction matrices

- [pairtools](https://www.github.com/open2c/pairtools)* for analysis and filtering of mapped reads

- [cooltools](https://www.github.com/open2c/cooltools)* for extracting and quantifying features from Hi-C data, including: contacts vs. distance, compartments and saddles, insulation, and peaks

- [coolpup.py](https://www.github.com/open2c/coolpuppy) for flexible pileup analysis

- [distiller](https://www.github.com/open2c/distiller-nf) - a Nextflow pipeline for automation of Hi-C data processing, from reads to Cooler files

- [quaich](https://www.github.com/open2c/quaich) - a Snakemake pipeline for automated Hi-C postprocessing using **cooltools** and **coolpup.py**
 
Additionally,

- [bioframe](https://www.github.com/open2c/bioframe)* provides a framework for genomic data analysis using Pandas DataFrames, including genomic interval arithmetic

- [polychrom](https://www.github.com/open2c/polychrom) simplifies polymer simulations for *in silico* experiments with chromosomes

❤️ Cooler, pairtools, cooltools, and bioframe are [NumFOCUS](https://numfocus.org/)-affiliated projects.

🧬 Interested in 3D genomics? Check out some of our Hi-C data analysis tutorials:

- Cooler [walkthrough](https://github.com/open2c/cooler-binder)
- Cooltools [tutorials](https://cooltools.readthedocs.io)
- Pairtools [tutorials](https://pairtools.readthedocs.io)


🤝 Please interact with us on [GitHub](https://www.github.com/open2c) (we are open!), or join our [Discord](https://discord.com/invite/qVfSbDYHNG) for more interactive discussions.

Legacy [Slack](https://bit.ly/2UaOpAe).

For contributors and community members:
 - [Authorship policy]({{ site.baseurl }}{% link authorship_policy.md %})
 - [Code of conduct]({{ site.baseurl }}{% link code_of_conduct.md %})

